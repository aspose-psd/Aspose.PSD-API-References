---
title: "SmartObjectLayer.ReplaceContents"
second_title: "Aspose.PSD for .NET API Referansı"
description: "SmartObjectLayer yöntemi. Akıllı nesne katmanına gömülü akıllı nesne içeriklerini değiştirir"
type: docs
weight: 160
url: /tr/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/
---
{{< psd/tize >}}
## ReplaceContents(Image) {#replacecontents}

Akıllı nesne katmanına gömülü akıllı nesne içeriğini değiştirir.

```csharp
public void ReplaceContents(Image image)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Görüntü. |

## Örnekler

Aşağıdaki kod, Gömülü Akıllı nesnelerin desteğini gösterir.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Bu örnek, PSD dosyasındaki akıllı nesne katmanını nasıl değiştireceğinizi ve akıllı nesnenin orijinal gömülü içeriğini dışa aktarma / güncelleme işlemini gösterir.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Gömülü akıllı nesne görüntüsünü PSD akıllı nesne katmanından dışa aktaralım
        smartObjectLayer.ExportContents(exportPath);

        // Orijinal görüntünün doğru kaydedildiğini kontrol edelim
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Orijinal akıllı nesne görüntüsünü ters çevirelim
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // PSD katmanındaki gömülü akıllı nesne görüntüsünü değiştirelim
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Güncellenen görüntünün doğru kaydedildiğini kontrol edelim
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ayrıca Bakınız

* class [Image](../../../aspose.psd/image/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(Image, ResolutionSetting) {#replacecontents_1}

Akıllı nesne katmanına gömülü akıllı nesne içeriğini değiştirir.

```csharp
public void ReplaceContents(Image image, ResolutionSetting resolution)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Görüntü. |
| çözünürlük | ResolutionSetting | Çözünürlük ayarları. Null ise görüntü çözünürlüğü kullanılacaktır. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Yalnızca gömülü akıllı nesne değiştirilebilir. |

## Örnekler

Bu örnek, yeni içerik dosyasının farklı bir çözünürlüğe sahip olduğunda ReplaceContents yönteminin doğru çalıştığını gösterir.

```csharp
[C#]

// Bu örnek, yeni içerik dosyasının farklı bir çözünürlüğe sahip olduğunda ReplaceContents yönteminin doğru çalıştığını gösterir.
string fileName = "CommonPsb.psd";
string filePath = baseFolder + fileName; // original PSD image
string newContentPath = baseFolder + "image.jpg"; // the new content file for the smart object
string outputFilePath = outputFolder + "ChangedPsd";
string pngOutputPath = outputFilePath + ".png"; // the output PNG file
string psdOutputPath = outputFilePath + ".psd"; // the output PSD file
using (PsdImage psd = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < psd.Layers.Length; i++)
    {
        var layer = psd.Layers[i];
        SmartObjectLayer smartObjectLayer = layer as SmartObjectLayer;
        if (smartObjectLayer != null)
        {
            smartObjectLayer.ReplaceContents(newContentPath);

            psd.Save(psdOutputPath);
            psd.Save(pngOutputPath, new PngOptions() { ColorType = Aspose.PSD.FileFormats.Png.PngColorType.TruecolorWithAlpha });
        }
    }
}
```

### Ayrıca Bakınız

* class [Image](../../../aspose.psd/image/)
* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting) {#replacecontents_3}

İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur.

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkedPath | String | Bağlantılı yol. |
| çözünürlük | ResolutionSetting | Çözünürlük ayarları. Null ise görüntü çözünürlüğü kullanılacaktır. |

### Ayrıca Bakınız

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting, bool) {#replacecontents_4}

İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur.

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution, bool isReplaceOnlyThis)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkedPath | String | Bağlantılı yol. |
| çözünürlük | ResolutionSetting | Çözünürlük ayarları. Null ise görüntü çözünürlüğü kullanılacaktır. |
| isReplaceOnlyThis | Boolean | Bayrak, bu Akıllı Katmandan içeriği değiştirmeyi mi yoksa bu içeriğe sahip tüm Akıllı Katmanlarda değiştirmeyi mi gösterir |

## Örnekler

Bu örnek, yeni içerik dosyasının farklı bir çözünürlüğe sahip olduğunda ReplaceContents yönteminin doğru çalıştığını gösterir.

```csharp
[C#]

// Bu örnek, yeni içerik dosyasının farklı bir çözünürlüğe sahip olduğunda ReplaceContents yönteminin doğru çalıştığını gösterir.
string fileName = "CommonPsb.psd";
string filePath = baseFolder + fileName; // original PSD image
string newContentPath = baseFolder + "image.jpg"; // the new content file for the smart object
string outputFilePath = outputFolder + "ChangedPsd";
string pngOutputPath = outputFilePath + ".png"; // the output PNG file
string psdOutputPath = outputFilePath + ".psd"; // the output PSD file
using (PsdImage psd = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < psd.Layers.Length; i++)
    {
        var layer = psd.Layers[i];
        SmartObjectLayer smartObjectLayer = layer as SmartObjectLayer;
        if (smartObjectLayer != null)
        {
            smartObjectLayer.ReplaceContents(newContentPath);

            psd.Save(psdOutputPath);
            psd.Save(pngOutputPath, new PngOptions() { ColorType = Aspose.PSD.FileFormats.Png.PngColorType.TruecolorWithAlpha });
        }
    }
}
```

Aşağıdaki kod, aynı kaynak referansına sahip birçok akıllı nesnede içeriğin değiştirilmesini desteklediğini gösterir.

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// Bu, aynı bağlantıya sahip tüm akıllı katmanlarda aynı bağlamı değiştirecektir.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Bu, aynı içeriği kullanan tüm SmartLayers'teki içeriği değiştirecektir.
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//Bu, yalnızca seçilen katmanın bağlamını değiştirecek, diğerlerini aynı bağlamda bırakacaktır.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Yalnızca seçilen SmartLayer'daki içeriği değiştirir.
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

### Ayrıca Bakınız

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string) {#replacecontents_2}

İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur.

```csharp
public void ReplaceContents(string linkedPath)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkedPath | String | Bağlantılı yol. |

### Ayrıca Bakınız

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, bool) {#replacecontents_5}

İçeriği bir dosyayla değiştirir. Sonrasında UpdateModifiedContent yöntemini çağırmaya gerek yoktur.

```csharp
public void ReplaceContents(string linkedPath, bool isReplaceOnlyThis)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkedPath | String | Bağlantılı yol. |
| isReplaceOnlyThis | Boolean | Bayrak, bu Akıllı Katmandan içeriği değiştirmeyi mi yoksa bu içeriğe sahip tüm Akıllı Katmanlarda değiştirmeyi mi gösterir |

## Örnekler

Aşağıdaki kod, aynı kaynak referansına sahip birçok akıllı nesnede içeriğin değiştirilmesini desteklediğini gösterir.

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// Bu, aynı bağlantıya sahip tüm akıllı katmanlarda aynı bağlamı değiştirecektir.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Bu, aynı içeriği kullanan tüm SmartLayers'teki içeriği değiştirecektir.
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//Bu, yalnızca seçilen katmanın bağlamını değiştirecek, diğerlerini aynı bağlamda bırakacaktır.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Yalnızca seçilen SmartLayer'daki içeriği değiştirir.
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

Aşağıdaki kod, Bağlı Akıllı nesnelerin güncellenmesini desteklediğini gösterir.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Bu örnek, bu yöntemleri kullanarak harici veya gömülü akıllı nesne katmanını nasıl güncelleyeceğinizi gösterir:
// RelinkToFile, UpdateModifiedContent, ExportContents
ExampleOfUpdatingSmartObjectLayer("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfUpdatingSmartObjectLayer("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfUpdatingSmartObjectLayer(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // Bu örnek, PSD dosyasındaki akıllı nesne katmanını nasıl değiştireceğinizi ve içeriğini dışa aktararak / güncelleyerek göstermek için hazırlanmıştır.
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "updating_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_modified.png";
    string png2OutputPath = dataDir + fileName + "_updated_modified.png";
    string psd2OutputPath = dataDir + fileName + "_updated_modified.psd";
    string exportPath = dataDir + fileName + "_exported." + GetFormatExt(format);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        var contentType = smartObjectLayer.ContentType;
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        if (contentType == SmartObjectType.AvailableLinked)
        {
            Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
            // Harici akıllı nesne görüntüsünü PSD akıllı nesne katmanından yeni bir konuma dışa aktaralım
            // çünkü onu değiştireceğiz.
            smartObjectLayer.ExportContents(exportPath);
            smartObjectLayer.RelinkToFile(exportPath);
        }

        // Akıllı nesnenin içeriğini tersine çevirelim: iç (önbelleğe alınmamış) görüntü
        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(new LoadOptions()))
        {
            InvertImage(innerImage);
            using (var stream = new MemoryStream())
            {
                innerImage.Save(stream);
                smartObjectLayer.Contents = stream.ToArray();
            }
        }

        // Değiştirilmiş içeriğin henüz renderlamayı etkilemediğini kontrol edelim.
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        smartObjectLayer.UpdateModifiedContent();

        // Güncellenmiş içeriğin renderlamayı etkileyip etkilemediğini ve PSD görüntüsünün doğru şekilde kaydedildiğini kontrol edelim
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// Bu örnek, gömülü akıllı nesneyi ConvertToLinked yöntemiyle harici bağlı içeriklere nasıl dönüştüreceğinizi gösterir.
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("new_panama-papers-4.psd", 0x10caa, 0, 0, 0x280, 0x169, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r3-embedded.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-tiff.psd", 0xca94, 0, 0, 0xb, 0x10, FileFormat.Tiff);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-bmp.psd", 0x278, 0, 0, 0xb, 0x10, FileFormat.Bmp);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-gif.psd", 0x3ec, 0, 0, 0xb, 0x10, FileFormat.Gif);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg.psd", 0x327, 0, 0, 0xb, 0x10, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg2000.psd", 0x519f, 0, 0, 0xb, 0x10, FileFormat.Jpeg2000);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-psd.psd", 0xc074, 0, 0, 0xb, 0x10, FileFormat.Psd);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfEmbeddedSmartObjectLayerToLinkedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // Bu, PSD dosyasındaki gömülü akıllı nesne katmanını harici bir katmana nasıl dönüştüreceğinizi gösterir.
    var formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_linked_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_external.png";
    string psdOutputPath = dataDir + fileName + "_to_external.psd";
    string externalPath = dataDir + fileName + "_external." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        Directory.CreateDirectory(Path.GetDirectoryName(externalPath));
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer.ConvertToLinked(externalPath);

        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        // Dönüştürülen görüntünün doğru şekilde kaydedilip kaydedilmediğini kontrol edelim
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);
    }
}

// Bu örnek, EmbedLinked yöntemiyle PSD dosyasına bir harici akıllı nesne katmanını veya tüm bağlı katmanları nasıl gömeceğinizi gösterir.
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
void ExampleOfLinkedSmartObjectLayerToEmbeddedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_embedded_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_embedded.png";
    string psdOutputPath = dataDir + fileName + "_to_embedded.psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer0 = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer0.EmbedLinked();
        AssertAreEqual(contentsLength, smartObjectLayer0.Contents.Length);
        AssertAreEqual(left, smartObjectLayer0.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer0.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer0.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer0.ContentsBounds.Bottom);
        if (image.Layers.Length >= 2)
        {
            var smartObjectLayer1 = (SmartObjectLayer)image.Layers[1];
            AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer0.ContentType);
            AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer1.ContentType);

            image.SmartObjectProvider.EmbedAllLinked();
            foreach (Layer layer in image.Layers)
            {
                var smartLayer = layer as SmartObjectLayer;
                if (smartLayer != null)
                {
                    AssertAreEqual(SmartObjectType.Embedded, smartLayer.ContentType);
                }
            }
        }

        Directory.CreateDirectory(Path.GetDirectoryName(psdOutputPath));
        // Dönüştürülen görüntünün doğru şekilde kaydedilip kaydedilmediğini kontrol edelim
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer.ContentType);
    }
}

// Bu örnek, Adobe® Photoshop® harici akıllı nesne katmanını nasıl değiştireceğinizi ve içeriğini dışa aktararak / güncelleyerek göstermek için hazırlanmıştır
// ExportContents ve ReplaceContents yöntemlerini kullanarak.
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked2.psd", 0x4aea, 0, 0, 10, 10, FileFormat.Psd);
void ExampleOfExternalSmartObjectLayerSupport(string filePath, int contentsLength, int left, int top, int right, int bottom, FileFormat format)
{
    string formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "external_support_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + ".png";
    string psdOutputPath = dataDir + fileName + ".psd";
    string linkOutputPath = dataDir + fileName + "_inverted." + formatExt;
    string png2OutputPath = dataDir + fileName + "_updated.png";
    string psd2OutputPath = dataDir + fileName + "_updated.psd";
    string exportPath = dataDir + fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[image.Layers.Length - 1];
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
        // Bağlı akıllı nesne görüntüsünü PSD akıllı nesne katmanından dışa aktaralım
        smartObjectLayer.ExportContents(exportPath);

        // Orijinal görüntünün doğru şekilde kaydedildiğini kontrol edelim
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Bağlı akıllı nesne görüntüsünü tersine çevirelim
            InvertImage(innerImage);
            innerImage.Save(linkOutputPath);

            // PSD katmanındaki bağlı akıllı nesne görüntüsünü değiştirelim
            smartObjectLayer.ReplaceContents(linkOutputPath);
        }

        // Güncellenen görüntünün doğru kaydedildiğini kontrol edelim
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// Görüntüyü tersine çevirir.
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// Raster görüntüyü tersine çevirir.
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

// Biçim uzantısını alır.
string GetFormatExt(FileFormat format)
{
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : format.ToString().ToLowerInvariant();
    return formatExt;
}
```

### Ayrıca Bakınız

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)



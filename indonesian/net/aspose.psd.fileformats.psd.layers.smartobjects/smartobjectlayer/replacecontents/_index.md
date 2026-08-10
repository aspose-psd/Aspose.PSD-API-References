---
title: "SmartObjectLayer.ReplaceContents"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode SmartObjectLayer. Mengganti konten objek pintar yang tertanam dalam lapisan objek pintar"
type: docs
weight: 160
url: /id/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/
---
{{< psd/tize >}}
## ReplaceContents(Image) {#replacecontents}

Mengganti konten objek pintar yang tertanam dalam lapisan objek pintar.

```csharp
public void ReplaceContents(Image image)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | Image | Gambar. |

## Contoh

Kode berikut menunjukkan dukungan objek pintar tertanam.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Contoh ini menunjukkan cara mengubah lapisan objek pintar dalam file PSD dan mengekspor / memperbarui konten asli objek pintar yang tertanam.
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

        // Mari ekspor gambar objek pintar tertanam dari lapisan objek pintar PSD
        smartObjectLayer.ExportContents(exportPath);

        // Mari periksa apakah gambar asli disimpan dengan benar
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Mari balikkan gambar objek pintar asli
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Mari ganti gambar objek pintar tertanam di lapisan PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Mari periksa apakah gambar yang diperbarui disimpan dengan benar
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Lihat Juga

* class [Image](../../../aspose.psd/image/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(Image, ResolutionSetting) {#replacecontents_1}

Mengganti konten objek pintar yang tertanam dalam lapisan objek pintar.

```csharp
public void ReplaceContents(Image image, ResolutionSetting resolution)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | Image | Gambar. |
| resolusi | ResolutionSetting | Pengaturan resolusi. Jika null, resolusi gambar akan digunakan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Hanya dapat mengganti objek pintar yang tertanam. |

## Contoh

Contoh ini menunjukkan bahwa metode ReplaceContents berfungsi dengan benar ketika file konten baru memiliki resolusi yang berbeda.

```csharp
[C#]

// Contoh ini menunjukkan bahwa metode ReplaceContents berfungsi dengan benar ketika file konten baru memiliki resolusi yang berbeda.
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

### Lihat Juga

* class [Image](../../../aspose.psd/image/)
* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting) {#replacecontents_3}

Mengganti konten dengan sebuah file. Tidak perlu memanggil metode UpdateModifiedContent setelahnya.

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linkedPath | String | Jalur tertaut. |
| resolusi | ResolutionSetting | Pengaturan resolusi. Jika null, resolusi gambar akan digunakan. |

### Lihat Juga

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, ResolutionSetting, bool) {#replacecontents_4}

Mengganti konten dengan sebuah file. Tidak perlu memanggil metode UpdateModifiedContent setelahnya.

```csharp
public void ReplaceContents(string linkedPath, ResolutionSetting resolution, bool isReplaceOnlyThis)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linkedPath | String | Jalur tertaut. |
| resolusi | ResolutionSetting | Pengaturan resolusi. Jika null, resolusi gambar akan digunakan. |
| isReplaceOnlyThis | Boolean | Bendera ini menunjukkan mengganti konten dari Smart Layer ini atau ke semua Smart Layer dengan konten ini |

## Contoh

Contoh ini menunjukkan bahwa metode ReplaceContents berfungsi dengan benar ketika file konten baru memiliki resolusi yang berbeda.

```csharp
[C#]

// Contoh ini menunjukkan bahwa metode ReplaceContents berfungsi dengan benar ketika file konten baru memiliki resolusi yang berbeda.
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

Kode berikut menunjukkan dukungan penggantian konten pada banyak objek pintar yang memiliki referensi sumber yang sama.

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// Ini akan mengganti konteks yang sama di semua lapisan pintar dengan tautan yang sama.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Ini akan mengganti konten di semua SmartLayers yang menggunakan konten yang sama.
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//Ini akan mengganti konteks hanya pada lapisan yang dipilih, meninggalkan semua lapisan lain dengan konteks yang sama.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Ini mengganti konten hanya pada SmartLayer yang dipilih.
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

### Lihat Juga

* class [ResolutionSetting](../../../aspose.psd/resolutionsetting/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string) {#replacecontents_2}

Mengganti konten dengan sebuah file. Tidak perlu memanggil metode UpdateModifiedContent setelahnya.

```csharp
public void ReplaceContents(string linkedPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linkedPath | String | Jalur tertaut. |

### Lihat Juga

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)

---

## ReplaceContents(string, bool) {#replacecontents_5}

Mengganti konten dengan sebuah file. Tidak perlu memanggil metode UpdateModifiedContent setelahnya.

```csharp
public void ReplaceContents(string linkedPath, bool isReplaceOnlyThis)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linkedPath | String | Jalur tertaut. |
| isReplaceOnlyThis | Boolean | Bendera ini menunjukkan mengganti konten dari Smart Layer ini atau ke semua Smart Layer dengan konten ini |

## Contoh

Kode berikut menunjukkan dukungan penggantian konten pada banyak objek pintar yang memiliki referensi sumber yang sama.

```csharp
[C#]

string srcFile = "Source.psd";
string replaceAll = "replaceAll.jpg";
string replaceOne = "replaceOne.jpg";
string outFileImgAll = "output_All.png";
string outFileImgOne = "output_one.png";

// Ini akan mengganti konteks yang sama di semua lapisan pintar dengan tautan yang sama.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Ini akan mengganti konten di semua SmartLayers yang menggunakan konten yang sama.
    smartObjectLayer.ReplaceContents(replaceAll, false);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgAll, new PngOptions());
}

//Ini akan mengganti konteks hanya pada lapisan yang dipilih, meninggalkan semua lapisan lain dengan konteks yang sama.
using (var image = (PsdImage)Image.Load(srcFile))
{
    var smartObjectLayer = (SmartObjectLayer)image.Layers[1];

    // Ini mengganti konten hanya pada SmartLayer yang dipilih.
    smartObjectLayer.ReplaceContents(replaceOne, true);
    smartObjectLayer.UpdateModifiedContent();

    image.Save(outFileImgOne, new PngOptions());
}
```

Kode berikut menunjukkan dukungan pembaruan objek pintar tertaut.

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

// Contoh ini menunjukkan cara memperbarui lapisan objek pintar eksternal atau tersemat menggunakan metode berikut:
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
    // Contoh ini menunjukkan cara mengubah lapisan objek pintar dalam file PSD dan mengekspor / memperbarui isinya.
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
            // Mari ekspor gambar objek pintar eksternal dari lapisan objek pintar PSD ke lokasi baru
            // karena kami akan memodifikasinya.
            smartObjectLayer.ExportContents(exportPath);
            smartObjectLayer.RelinkToFile(exportPath);
        }

        // Mari balikkan konten objek pintar: gambar internal (tidak di-cache)
        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(new LoadOptions()))
        {
            InvertImage(innerImage);
            using (var stream = new MemoryStream())
            {
                innerImage.Save(stream);
                smartObjectLayer.Contents = stream.ToArray();
            }
        }

        // Mari periksa apakah konten yang dimodifikasi belum memengaruhi rendering.
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        smartObjectLayer.UpdateModifiedContent();

        // Mari periksa apakah konten yang diperbarui memengaruhi rendering dan gambar PSD disimpan dengan benar
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// Contoh ini menunjukkan cara mengonversi objek pintar tersemat menjadi konten tertaut eksternal menggunakan metode ConvertToLinked.
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
    // Ini menunjukkan cara mengonversi lapisan objek pintar tersemat dalam file PSD menjadi eksternal.
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

        // Mari periksa apakah gambar yang dikonversi disimpan dengan benar
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

// Contoh ini menunjukkan cara menyematkan satu lapisan objek pintar eksternal atau semua lapisan tertaut dalam file PSD menggunakan metode EmbedLinked.
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
        // Mari periksa apakah gambar yang dikonversi disimpan dengan benar
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

// Contoh ini menunjukkan cara mengubah lapisan objek pintar eksternal Adobe® Photoshop® dan mengekspor / memperbarui isinya
// dengan menggunakan metode ExportContents dan ReplaceContents.
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
        // Mari ekspor gambar objek pintar tertaut dari lapisan objek pintar PSD
        smartObjectLayer.ExportContents(exportPath);

        // Mari periksa apakah gambar asli disimpan dengan benar
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Mari balikkan gambar objek pintar tertaut
            InvertImage(innerImage);
            innerImage.Save(linkOutputPath);

            // Mari ganti gambar objek pintar tertaut di lapisan PSD
            smartObjectLayer.ReplaceContents(linkOutputPath);
        }

        // Mari periksa apakah gambar yang diperbarui disimpan dengan benar
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// Membalikkan gambar.
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

// Membalikkan citra raster.
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

// Mendapatkan ekstensi format.
string GetFormatExt(FileFormat format)
{
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : format.ToString().ToLowerInvariant();
    return formatExt;
}
```

### Lihat Juga

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)



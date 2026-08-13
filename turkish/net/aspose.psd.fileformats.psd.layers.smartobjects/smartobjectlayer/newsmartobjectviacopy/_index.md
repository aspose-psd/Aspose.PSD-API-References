---
title: "SmartObjectLayer.NewSmartObjectViaCopy"
second_title: "Aspose.PSD for .NET API Referansı"
description: "SmartObjectLayer yöntemi. Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur. Adobe Photoshop'un Katman → Akıllı Nesneler → Kopya ile Yeni Akıllı Nesne işlevini yeniden üretir. Yalnızca gömülü akıllı nesneler için etkin olduğunu, çünkü gömülü görüntünün de kopyalandığını unutmayın. Gömülü görüntüyü paylaşmak istiyorsanız DuplicateLayer yöntemini kullanın"
type: docs
weight: 140
url: /tr/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectLayer.NewSmartObjectViaCopy method

Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur. Adobe Photoshop'un `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` işlevini yeniden üretir. Yalnızca gömülü akıllı nesneler için etkin olduğunu, çünkü gömülü görüntünün de kopyalandığını unutmayın. Gömülü görüntüyü paylaşmak istiyorsanız [`DuplicateLayer`](../duplicatelayer/) yöntemini kullanın.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### Dönüş Değeri

Klonlanmış [`SmartObjectLayer`](../) örneği.

## Örnekler

Bu örnekler, bir PSD görüntüsünde akıllı nesne katmanlarını nasıl kopyalayacağınızı gösterir.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Bu örnekler, bir PSD görüntüsünde akıllı nesne katmanlarını nasıl kopyalayacağınızı gösterir.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // Gömülü akıllı nesne görüntüsünü tersine çevirelim (iç içe bir PSD görüntüsü için yalnızca ilk katmanını tersine çeviririz)
            InvertImage(innerImage);

            // PSD katmanındaki gömülü akıllı nesne görüntüsünü değiştirelim
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Kopyalanan katman, gömülü görüntüyü orijinal akıllı nesneyle paylaşır
        // ve aksi takdirde render önbelleği değişmeden kalacağı için açıkça güncellenmelidir.
        // Yeni katmanın NewSmartObjectViaCopy tarafından oluşturulduğundan emin olmak için her akıllı nesneyi güncelliyoruz
        // gömülü görüntüyü diğerleriyle paylaşmaz.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// PSD görüntüsü dahil raster görüntüyü tersine çevirir.
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

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### Ayrıca Bakınız

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)



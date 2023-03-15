---
title: SmartObjectLayer.DuplicateLayer
second_title: Aspose.PSD for .NET API Referansı
description: SmartObjectLayer yöntem. Bunu kopyalayarak yeni bir akıllı nesne katmanı oluşturur. Katıştırılmış akıllı nesneler için katıştırılmış görüntünün paylaşıldığına dikkat edin. Katıştırılmış görüntüyü kopyalamak istiyorsanız şunu kullanınNewSmartObjectViaCopy yöntem.
type: docs
weight: 80
url: /tr/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
## SmartObjectLayer.DuplicateLayer method

Bunu kopyalayarak yeni bir akıllı nesne katmanı oluşturur. Katıştırılmış akıllı nesneler için katıştırılmış görüntünün paylaşıldığına dikkat edin. Katıştırılmış görüntüyü kopyalamak istiyorsanız şunu kullanın[`NewSmartObjectViaCopy`](../newsmartobjectviacopy/) yöntem.

```csharp
public SmartObjectLayer DuplicateLayer()
```

### Geri dönüş değeri

klonlanmış[`SmartObjectLayer`](../) örnek.

### Örnekler

Bu örnekler, akıllı nesne katmanlarının bir PSD görüntüsünde nasıl kopyalanacağını gösterir.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Bu örnekler, akıllı nesne katmanlarının bir PSD görüntüsüne nasıl kopyalanacağını gösterir.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // Kopyalanacak katman numarası
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
            // Gömülü akıllı nesne görüntüsünü ters çevirelim (iç PSD görüntüsü için yalnızca ilk katmanını ters çeviriyoruz)
            InvertImage(innerImage);

            // Gömülü akıllı nesne görüntüsünü PSD katmanında değiştirelim
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Çoğaltılan katman, gömülü görüntüsünü orijinal akıllı nesneyle paylaşır
        // ve açıkça güncellenmesi gerekir, aksi takdirde işleme önbelleği değişmeden kalır.
        // NewSmartObjectViaCopy tarafından oluşturulan yeni katmanın güncellendiğinden emin olmak için her akıllı nesneyi güncelliyoruz.
        // gömülü görüntüyü başkalarıyla paylaşmaz.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// PSD görüntüsü de dahil olmak üzere raster görüntüyü ters çevirir.
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

// Raster görüntüyü ters çevirir.
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

### Ayrıca bakınız

* class [SmartObjectLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* toplantı [Aspose.PSD](../../../)



---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD for .NET API Referansı
description: SmartObjectLayer mülk. Akıllı nesne katmanı içeriğini alır veya ayarlar. Katıştırılmış akıllı nesne içeriği katıştırılmış ham görüntü dosyasıdırData ve özellikleri. Bağlantılı akıllı nesne içeriği varsa bağlantılı görüntü dosyasının ham içeriğidir ve özellikleriLiFeDataSource . Adobe Photoshop  Graphics Libraryden yüklemeyi desteklemiyoruz.IsLibraryLink true. Normal bağlantı dosyaları için ilk başta şunu kullanırızRelativePath kaynak görüntü yoluna göre nispeten dosyasını aramak içinSourceImagePath  yoksa bakarızFullPath  değilse bağlantı dosyasını resmimizin bulunduğu dizinde ararızSourceImagePath .
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Akıllı nesne katmanı içeriğini alır veya ayarlar. Katıştırılmış akıllı nesne içeriği, katıştırılmış ham görüntü dosyasıdır:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) ve özellikleri. Bağlantılı akıllı nesne içeriği, varsa bağlantılı görüntü dosyasının ham içeriğidir ve özellikleri:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Adobe� Photoshop� �� Graphics Library'den yüklemeyi desteklemiyoruz.[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) true. Normal bağlantı dosyaları için ilk başta şunu kullanırız:[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) kaynak görüntü yoluna göre nispeten dosyasını aramak içinSourceImagePath , yoksa bakarız[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , değilse, bağlantı dosyasını resmimizin bulunduğu dizinde ararız:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Mülk değeri

byte[] akıllı nesne katmanı içeriği.

### istisnalar

| istisna | şart |
| --- | --- |
| NotSupportedException | Adobe� Photoshop� �� kitaplığından içerik alınamıyor. |

### Örnekler

Aşağıdaki kod, Katıştırılmış Akıllı nesnelerin desteğini gösterir.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Bu örnek, PSD dosyasındaki akıllı nesne katmanının nasıl değiştirileceğini ve akıllı nesne orijinal katıştırılmış içeriğinin nasıl dışa aktarılacağını / güncelleneceğini gösterir.
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

        // Orijinal görüntünün doğru kaydedilip kaydedilmediğini kontrol edelim
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Orijinal akıllı nesne görüntüsünü tersine çevirelim
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Gömülü akıllı nesne görüntüsünü PSD katmanında değiştirelim
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Güncellenen görüntünün doğru kaydedilip kaydedilmediğini kontrol edelim
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ayrıca bakınız

* class [SmartObjectLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* toplantı [Aspose.PSD](../../../)



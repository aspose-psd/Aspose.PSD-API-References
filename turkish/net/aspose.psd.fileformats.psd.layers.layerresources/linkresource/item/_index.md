---
title: LinkResource.Item
second_title: Aspose.PSD for .NET API Referansı
description: LinkResource mülk. Şunu alırLinkDataSource bağlantı veri kaynağı benzersiz tanımlayıcısı olan belirtilen dizinde..
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/
---
## LinkResource indexer

Şunu alır:[`LinkDataSource`](../../linkdatasource/) bağlantı veri kaynağı benzersiz tanımlayıcısı olan belirtilen dizinde..

```csharp
public LinkDataSource this[Guid index] { get; }
```

| Parametre | Tanım |
| --- | --- |
| index | Bağlantı veri kaynağı benzersiz tanımlayıcısı olarak dizin. |

### Geri dönüş değeri

[`LinkDataSource`](../../linkdatasource/) örnek.

### Mülk değeri

[`LinkDataSource`](../../linkdatasource/) .

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

* class [LinkDataSource](../../linkdatasource/)
* class [LinkResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../linkresource/)
* toplantı [Aspose.PSD](../../../)



---
title: "Arayüz ISmartObjectLayerResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ISmartObjectLayerResource arayüzü. PSD dosyasındaki akıllı nesne katman kaynağı hakkında bilgi içeren ISmartObjectLayerResource arayüzünü tanımlar. Ayrıca Adobe Photoshop görüntülerinde hem Sold hem de Sole kaynaklarını belirlemek için kullanılan bir işaretleme arayüzüdür."
type: docs
weight: 2830
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/
---
{{< psd/tize >}}
## ISmartObjectLayerResource interface

ISmartObjectLayerResource arayüzünü tanımlar; bu arayüz PSD dosyasındaki akıllı nesne katmanı kaynağı hakkında bilgi içerir. Adobe® Photoshop® görüntülerinde hem Sold hem de Sole kaynaklarını belirlemek için kullanılan bir işaretleme arayüzüdür.

```csharp
public interface ISmartObjectLayerResource : IPlacedLayerResource
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/) { get; set; } | Alır veya ayarlar bu akıllı nesne katman verisinin PSD görüntüsündeki benzersiz tanımlayıcısını. |

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

* interface [IPlacedLayerResource](../iplacedlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



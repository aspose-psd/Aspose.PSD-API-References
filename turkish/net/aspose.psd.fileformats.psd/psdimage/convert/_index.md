---
title: PsdImage.Convert
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage yöntem. Bu görüntü biçimini options. içinde belirtilene dönüştürür.
type: docs
weight: 500
url: /tr/net/aspose.psd.fileformats.psd/psdimage/convert/
---
## PsdImage.Convert method

Bu görüntü biçimini options. içinde belirtilene dönüştürür.

```csharp
public void Convert(PsdOptions newOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newOptions | PsdOptions | Yeni seçenekler. |

### Örnekler

Bu örnekler, PSD görüntü formatının diğer Renk Modlarına/BitDepth'e dönüştürülmesini göstermektedir.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Bu örnekler, PSD görüntü formatının diğer Renk Modlarına/BitDepth'e dönüştürülmesini göstermektedir.
ImageConversion(ColorModes.Grayscale, 16, 2);
ImageConversion(ColorModes.Grayscale, 8, 2);
ImageConversion(ColorModes.Grayscale, 8, 1);
ImageConversion(ColorModes.Rgb, 8, 4);
ImageConversion(ColorModes.Rgb, 16, 4);
ImageConversion(ColorModes.Cmyk, 8, 5);
ImageConversion(ColorModes.Cmyk, 16, 5);

void ImageConversion(ColorModes colorMode, short channelBitsCount, short channelsCount)
{
    var compression = channelBitsCount > 8 ? CompressionMethod.Raw : CompressionMethod.RLE;
    SaveToPsdThenLoadAndSaveToPng(
        "SheetColorHighlightExample",
        colorMode,
        channelBitsCount,
        channelsCount,
        compression,
        1);
    SaveToPsdThenLoadAndSaveToPng(
        "FillOpacitySample",
        colorMode,
        channelBitsCount,
        channelsCount,
        compression,
        2);
    SaveToPsdThenLoadAndSaveToPng(
        "ClippingMaskRegular",
        colorMode,
        channelBitsCount,
        channelsCount,
        compression,
        3);
}

// PSD'ye kaydeder, ardından kaydedilen dosyayı yükler ve PNG'ye kaydeder.
void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string srcFile = dataDir + file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "bits" + channelsCount + "channels" +
                     compression;
    string fileName = file + "_" + postfix + ".psd";
    string exportPath = outputDir + fileName;
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };
    using (var image = (PsdImage)Image.Load(srcFile))
    {
        image.Convert(psdOptions);

        RasterCachedImage raster = image.Layers.Length > 0 && layerNumber >= 0
            ? (RasterCachedImage)image.Layers[layerNumber]
            : image;
        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ayrıca bakınız

* class [PsdOptions](../../../aspose.psd.imageoptions/psdoptions/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)



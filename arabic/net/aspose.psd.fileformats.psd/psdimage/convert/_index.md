---
title: "PsdImage.Convert"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. تحول تنسيق هذه الصورة إلى التنسيق المحدد في الخيارات."
type: docs
weight: 560
url: /ar/net/aspose.psd.fileformats.psd/psdimage/convert/
---
{{< psd/tize >}}
## PsdImage.Convert method

يحوّل تنسيق هذه الصورة إلى التنسيق المحدد في الخيارات.

```csharp
public void Convert(PsdOptions newOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newOptions | PsdOptions | الخيارات الجديدة. |

## أمثلة

توضح هذه الأمثلة تحويل تنسيق صورة PSD إلى أوضاع لون/عمق بت أخرى.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// توضح هذه الأمثلة تحويل تنسيق صورة PSD إلى أوضاع لون/عمق بت أخرى.
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

// يحفظ إلى PSD ثم يحمل الملف المحفوظ ويحفظه إلى PNG.
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

### انظر أيضًا

* class [PsdOptions](../../../aspose.psd.imageoptions/psdoptions/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)



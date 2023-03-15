---
title: PsdImage.Convert
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. この画像形式を options. で指定されたものに変換します
type: docs
weight: 500
url: /ja/net/aspose.psd.fileformats.psd/psdimage/convert/
---
## PsdImage.Convert method

この画像形式を options. で指定されたものに変換します。

```csharp
public void Convert(PsdOptions newOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newOptions | PsdOptions | 新しいオプション。 |

### 例

これらの例は、PSD 画像形式を他のカラー モード/ビット深度に変換する方法を示しています。

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// これらの例は、PSD 画像フォーマットを他のカラー モード/ビット深度に変換する方法を示しています。
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

// PSD に保存し、保存したファイルをロードして PNG に保存します。
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

### 関連項目

* class [PsdOptions](../../../aspose.psd.imageoptions/psdoptions/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)



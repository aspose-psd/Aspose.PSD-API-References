---
title: Image.Load
second_title: Aspose.PSD for .NET API リファレンス
description: Image 方法. 指定したファイルから新しい画像を読み込みます
type: docs
weight: 20
url: /ja/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

指定したファイルから新しい画像を読み込みます。

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 画像の読み込み元のファイル パス。 |
| loadOptions | LoadOptions | 読み込みオプション。 |

### 戻り値

読み込まれた画像。

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

指定したファイルから新しい画像を読み込みます。

```csharp
public static Image Load(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | 画像を読み込むファイル パス。 |

### 戻り値

読み込まれた画像。

### 例

この例では、指定されたファイル パスを使用して既存のイメージ ファイルを Aspose.PSD.Image のインスタンスにロードする方法を示します。

```csharp
[C#]

// Image インスタンスを作成し、ディスクの場所にある既存のイメージ ファイルで初期化します
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    // 画像処理を行います
}
```

次の例は、右から左へ記述する言語の ITextPortion によるテキストの配置が正しく機能することを示しています。

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

次の例は、グレースケール 16 ビット PSD ファイルを読み込んでチャンネル RGB ごとに 16 ビットに保存すると、例外なく正しく動作することを示しています。

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // ここも例外ではありません。
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

次の例は、グレースケール 16 ビット PSD ファイルの読み取りと、チャネルあたり 8 ビットのグレースケールへの保存が例外なく正しく機能することを示しています。

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // ここも例外ではありません。
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

次の例は、ドキュメント変換の進行状況が例外なく正しく機能することを示しています。

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

次の例は、グレースケール 16 ビット PSD ファイルの読み取りと保存が例外なく正しく機能することを示しています。

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // ここも例外ではありません。
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### 関連項目

* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

指定されたストリームから新しい画像を読み込みます。

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 画像を読み込むストリーム。 |
| loadOptions | LoadOptions | 読み込みオプション。 |

### 戻り値

読み込まれた画像。

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

指定されたストリームから新しい画像を読み込みます。

```csharp
public static Image Load(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 画像をロードするストリーム。 |

### 戻り値

読み込まれた画像。

### 例

この例では、System.IO.Stream オブジェクトを使用して既存のイメージ ファイルをロードする方法を示します。

```csharp
[C#]

// FileStream のインスタンスを作成します
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    // Image クラスのインスタンスを作成し、Load メソッドを呼び出して FileStream オブジェクトを介して既存のファイルをロードします
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        //画像処理を行います。
    }
}
```

### 関連項目

* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)



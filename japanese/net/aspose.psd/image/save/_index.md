---
title: "Image.Save"
second_title: "Aspose.PSD for .NET API Reference"
description: "Image メソッド。画像データを基になるストリームに保存します。"
type: docs
weight: 240
url: /ja/net/aspose.psd/image/save/
---
{{< psd/tize >}}
## Save() {#save}

画像データを基になるストリームに保存します。

```csharp
public void Save()
```

### 関連項目

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルパス。 |
| オプション | ImageOptionsBase | オプションです。 |

## 例

次の例は、Adobe Illustrator ファイルを Aspose.PSD で PDF 形式にエクスポートする方法を示しています。

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

次の例は、AsposePSD が PSB ファイルの PSD 形式へのエクスポートをサポートしていることを示しています。

```csharp
[C#]

// PSB を PDF として保存することをサポートします
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

次のコードは、選択可能なテキストを含む PDF ドキュメントとして PsdImage を保存します。

```csharp
[C#]

// PSD を PDF に保存しても選択可能なテキストは提供されません
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

次の例は、Aspose.PSD で AI ファイルを PSD および PNG 形式にエクスポートする方法を示しています。

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

次の例は、右から左への言語に対して ITextPortion を使用したテキスト配置が正しく機能することを示しています。

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

この例では、画像を保存する簡単な手順を示します。この操作をデモするために、ディスク上の既存ファイルをロードし、画像に対して回転操作を行い、File Path を使用して JPEG ファイル形式で画像を保存します。

```csharp
[C#]

//画像クラスのインスタンスを作成し、File path を介して既存のファイルで初期化します。
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //画像を X 軸周りに 180 度回転させます。
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //デフォルトの JpegOptions 設定で、画像を JPEG として File Path に保存します。
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

次の例は、Aspose.PSD で LayerGroup の表示状態を変更する方法を示しています。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// レイヤー名を変更して保存します
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // グループ内のすべてをオフにします
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

以下の例は、Aspose.PSD でシンプルコンストラクタ バージョンを使用した場合に、新しく作成されたレイヤーに描画できる方法を示しています

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // ペンツールで矩形を描く
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Solid Brush を使用して青色で別の長方形を描画する
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

次の例は、グレースケール 16 ビット PSD ファイルをチャンネルごとに 16 ビットの RGB に読み込み保存することが正しく例外なく動作することを示しています。

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
    // ここでは例外は発生しないはずです。
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

次の例は、グレースケール 16 ビット PSD ファイルをチャンネルごとに 8 ビットのグレースケールに読み込み保存することが正しく例外なく動作することを示しています。

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
    // ここでは例外は発生しないはずです。
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

次の例は、Aspose.PSD で PassThrough レイヤー ブレンド モードを使用する方法を示しています。

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

次の例は、ドキュメント変換の進行状況が正しく例外なしで動作することを示しています。

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

次の例は、グレースケール 16 ビット PSD ファイルの読み取りと保存が正しく、例外なしで動作することを示しています。

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
        // ここでは例外は発生しないはずです。
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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

オブジェクトのデータを、保存オプションに従って指定されたファイル形式で、指定されたファイル位置に保存します。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルパス。 |
| オプション | ImageOptionsBase | オプションです。 |
| boundsRectangle | Rectangle | 対象画像の境界矩形です。空の矩形を設定してソース境界として使用します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | オプション |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 画像の保存に失敗しました。 |

### 関連項目

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 画像のデータを保存するストリーム。 |
| optionsBase | ImageOptionsBase | 保存オプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 現在サポートされていないため、指定された形式に保存できません。;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 画像のエクスポートに失敗しました。 |

## 例

この例では、画像を MemoryStream に保存するプロセスを示します。この操作をデモするために、ディスク上の既存ファイルをロードし、画像に対して回転操作を行い、Gif 形式で画像を保存します。

```csharp
[C#]

//MemoryStream のインスタンスを作成します。
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //画像クラスのインスタンスを作成し、File path を介して既存のファイルで初期化します。
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //画像を X 軸周りに 180 度回転させます。
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //デフォルトの GifOptions 設定で、画像を PSD として MemoryStream に保存します。
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### 関連項目

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

画像のデータを、保存オプションに従って指定されたファイル形式で、指定されたストリームに保存します。

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 画像のデータを保存するストリーム。 |
| optionsBase | ImageOptionsBase | 保存オプション。 |
| boundsRectangle | Rectangle | 対象画像の境界矩形です。空の矩形を設定するとソースの境界が使用されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 現在サポートされていないため、指定された形式に保存できません。;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 画像のエクスポートに失敗しました。 |

### 関連項目

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



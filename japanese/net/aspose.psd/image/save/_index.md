---
title: Image.Save
second_title: Aspose.PSD for .NET API リファレンス
description: Image 方法. 画像データを基になるストリームに保存します
type: docs
weight: 230
url: /ja/net/aspose.psd/image/save/
---
## Save() {#save}

画像データを基になるストリームに保存します。

```csharp
public void Save()
```

### 関連項目

* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス. |
| options | ImageOptionsBase | オプション. |

### 例

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

// PSB を PDF として保存することをサポート
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

// PSD を PDF に保存しても、選択可能なテキストは提供されません
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

この例では、イメージを保存する簡単な手順を示します。この操作を説明するために、ディスクの場所から既存のファイルをロードし、画像に対して回転操作を実行し、ファイル パスを使用して画像を Jpeg ファイル形式で保存します。

```csharp
[C#]

//画像クラスのインスタンスを作成し、ファイル パスを介して既存のファイルで初期化します
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // X 軸を中心に画像を 180 度回転
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //デフォルトの JpegOptions 設定を使用して、画像を Jpeg としてファイル パスに保存します
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

次の例は、Aspose.PSD で LayerGroup の可視性を変更する方法を示しています。

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// レイヤー名を変更して保存
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // グループ内のすべてを無効にする
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

次の例は、単純なコンストラクター バージョンが Aspose.PSD で使用されている場合に、新しく作成されたレイヤーに描画する方法を示しています。

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

    // ペンツールで長方形を描く
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 青色のソリッド ブラシで別の四角形を描画します
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
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

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル パス。 |
| options | ImageOptionsBase | オプション。 |
| boundsRectangle | Rectangle | 宛先画像の境界矩形。ソース境界を使用するための空の四角形を設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | オプション |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 画像の保存に失敗しました。 |

### 関連項目

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 画像のデータを保存するストリーム。 |
| optionsBase | ImageOptionsBase | 保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 現時点ではサポートされていないため、指定された形式に保存できません。;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 画像のエクスポートに失敗しました。 |

### 例

この例では、イメージを MemoryStream に保存するプロセスを示します。この操作を説明するために、例ではディスクの場所から既存のファイルをロードし、画像に対して回転操作を実行し、画像を Gif 形式で保存します。

```csharp
[C#]

//MemoryStream のインスタンスを作成する
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //画像クラスのインスタンスを作成し、ファイル パスを介して既存のファイルで初期化します
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        // X 軸を中心に画像を 180 度回転
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //デフォルトの GifOptions 設定で画像を PSD として MemoryStream に保存します
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### 関連項目

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | 画像のデータを保存するストリーム。 |
| optionsBase | ImageOptionsBase | 保存オプション。 |
| boundsRectangle | Rectangle | 宛先画像の境界矩形。ソース境界を使用するための空の四角形を設定します。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 現時点ではサポートされていないため、指定された形式に保存できません。;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 画像のエクスポートに失敗しました。 |

### 関連項目

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* 名前空間 [Aspose.PSD](../../image/)
* 組み立て [Aspose.PSD](../../../)



---
title: "クラス PngOptions"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.ImageOptions.PngOptions クラス。png ファイル形式の作成オプションです。"
type: docs
weight: 5370
url: /ja/net/aspose.psd.imageoptions/pngoptions/
---
{{< psd/tize >}}
## PngOptions class

png ファイル形式の作成オプション。

```csharp
public class PngOptions : ImageOptionsBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | `PngOptions` クラスの新しいインスタンスを初期化します。 |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | `PngOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | ビット深度です。 |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | すべての内部バッファに対して定義された最大許容サイズであるバッファサイズヒントを取得または設定します。 |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | 色のタイプを取得または設定します。 |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | 0〜9 の範囲の png 画像圧縮レベルで、9 が最大圧縮、0 が保存モードです。 |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートするときにテキスト描画に使用されるフォント）。デフォルトフォント名を取得するには、次のコードスニペットを使用できます: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | png ファイル保存プロセスで使用されるフィルタタイプを取得または設定します。 |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | フルフレームかどうかを示す値を取得または設定します。 |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | マルチページオプション |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | カラーパレットを取得または設定します。 |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 取得または設定するのは、進行状況イベント ハンドラーです。 |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | この `PngOptions` がプログレッシブかどうかを示す値を取得または設定します。 |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 解像度設定を取得または設定します。 |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 画像を作成するソースを取得または設定します。 |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | ベクターラスタライズオプションを取得または設定します。 |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | XMP メタデータ コンテナを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | このインスタンスをクローンします。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | デフォルトの圧縮レベルです。 |

## 例

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

この例は、エクスポート目的で SaveOptions 名前空間のさまざまなクラスの使用方法を示しています。Psd タイプの画像が Image のインスタンスにロードされ、複数の形式にエクスポートされます。

```csharp
[C#]

//既存の画像を Image クラスのインスタンスにロードします
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //デフォルト オプションを使用して BMP ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //デフォルト オプションを使用して JPEG ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //デフォルト オプションを使用して JPEG 2000 ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //デフォルト オプションを使用して PNG ファイル形式にエクスポートします
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //デフォルト オプションを使用して TIFF ファイル形式にエクスポートします
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
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

この例では Graphics クラスを使用して画像表面上に基本形状を作成します。操作を示すために、例では PSD 形式の新しい Image を作成し、Graphics クラスが提供する Draw メソッドを使用して画像表面上に基本形状を描画し、最後に PSD ファイル形式へエクスポートします。

```csharp
[C#]

//Image のインスタンスを作成します。
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics クラスのインスタンスを作成し、初期化します。
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics のサーフェスをクリアします。
    graphics.Clear(Color.Wheat);

    //Pen オブジェクトで黒色を指定して円弧を描画します、
    //円弧を囲む矩形、開始角度およびスイープ角度
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Pen オブジェクトで青色と座標ポイントを指定してベジェ曲線を描画します。
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Pen オブジェクトで緑色とポイントの配列を指定して曲線を描画します
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen オブジェクトとそれを囲む矩形を使用して楕円を描画します
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //直線を描画します
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //パイセグメントを描画します
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Pen オブジェクトで赤色とポイントの配列を指定して多角形を描画します
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //矩形を描画します
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush オブジェクトを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush オブジェクトと Font を使用して、特定の Point で文字列を描画します
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions のインスタンスを作成し、そのさまざまなプロパティを設定します
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // すべての変更を保存します。
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 関連項目

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)



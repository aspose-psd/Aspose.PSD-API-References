---
title: Class AiImage
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Ai.AiImage クラス. Adobe Illustrator AI Image
type: docs
weight: 1260
url: /ja/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

Adobe Illustrator (AI) Image

```csharp
public sealed class AiImage : Image
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [AiImage](aiimage/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | パレットを自動調整するかどうかを示す値を取得または設定します。 |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 背景色の値を取得または設定します。 |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | ピクセルあたりの画像ビット数を取得します。 |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 画像の境界を取得します。 |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | すべての内部バッファーの最大許容サイズが定義されているバッファー サイズのヒントを取得または設定します。 |
| [Container](../../aspose.psd/image/container/) { get; } | を取得します[`Image`](../../aspose.psd/image/)コンテナ. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | データ部を取得します。 |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | オブジェクトのデータ ストリームを取得します。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | ファイル形式の値を取得 |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | ファイナライズ セクションを取得します。 |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 画像に背景色があるかどうかを示す値を取得または設定します. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | ヘッダーを取得します。 |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | 画像の高さを取得します. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 割り込みモニターを取得または設定します。 |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要かどうかを示す値を取得します。 |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | レイヤー セクションを取得します。 |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | カラー パレットを取得または設定します。ピクセルが直接表現されている場合、カラー パレットは使用されません。 |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | セットアップセクションを取得します。 |
| [Size](../../aspose.psd/image/size/) { get; } | 画像サイズを取得します。 |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Adobe Illustrator のバージョンを取得します format |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | 画像の幅を取得します. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | AI レイヤー セクションを追加します。 |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | データをキャッシュし、基盤から追加のデータ読み込みが実行されないようにします[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 渡された保存オプションで表される指定されたファイル形式で画像を保存できるかどうかを決定します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | デフォルトのオプションを取得します。 |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 元のファイル設定に基づいてオプションを取得します. これは、元の画像のビット深度やその他のパラメーターを変更しないで保持するのに役立ちます. たとえば、1 ビットあたり 1 ビットの白黒 PNG 画像をロードし、 the を使用して保存します[`Save`](../../aspose.psd/datastreamsupporter/save/) これを回避し、1 ピクセルあたり 1 ビットの PNG 画像を保存するには、このメソッドを使用して対応する保存オプションを取得し、 を[`Save`](../../aspose.psd/image/save/) 番目のパラメーターとしてのメソッド。 |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 画像のサイズを変更します。デフォルトLeftTopToLeftTop使用されています. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | 画像のサイズを変更します。 |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | 画像のサイズを変更します。 |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 高さを比例してサイズ変更します。 |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 高さを比例してサイズ変更します。 |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 幅を比例してサイズ変更します。 |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 幅を比例してサイズ変更します。 |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | 画像を回転、反転、または回転して反転します。 |
| [Save](../../aspose.psd/image/save/)() | 画像データを基になるストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | オブジェクトのデータを指定されたストリームに保存します。 |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | オブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でイメージのデータを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイルの場所に保存します。 |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | 画像パレットを設定します。 |

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

次の例は、PSD、PNG、JPG、GIF、および TIF 形式への Ai 形式のエクスポートのサポートを示しています。

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### 関連項目

* class [Image](../../aspose.psd/image/)
* 名前空間 [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* 組み立て [Aspose.PSD](../../)



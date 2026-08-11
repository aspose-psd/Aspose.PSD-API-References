---
title: "クラス AiLayerSection"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Ai.AiLayerSection クラス。AI 形式のレイヤーセクションです。"
type: docs
weight: 1280
url: /ja/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

Ai フォーマットのレイヤーセクション

```csharp
public sealed class AiLayerSection : AiDataSection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | 青色成分を取得または設定します。 |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | 色のインデックスを取得または設定します。この引数は –1 から 26 の間の値を取ります。各整数は、ユーザー識別用にレイヤーに割り当てられる色を表します。 |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | カラー番号を取得または設定します。-1 は、赤、緑、青プロパティからのカスタムカラー値です。レイヤーのカラー設定を指定します。 |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | ディム値をパーセンテージで取得または設定します。レイヤーに含まれるリンク画像およびビットマップ画像の強度を指定されたパーセンテージに減少させます。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | 緑色成分を取得または設定します。 |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します。 |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | このレイヤーが暗くなるかどうかを示す値を取得または設定します。レイヤーに含まれるリンク画像およびビットマップ画像の強度を減少させます。 |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | このレイヤーがロックされているかどうかを示す値を取得または設定します。アイテムへの変更を防止します。 |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | このレイヤーがプレビューかどうかを示す値を取得または設定します。レイヤーに含まれるアートワークを輪郭ではなくカラーで表示します。 |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | このレイヤーが印刷されるかどうかを示す値を取得または設定します。true の場合、レイヤーに含まれるアートワークを印刷可能にします。 |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | このレイヤーが表示されるかどうかを示す値を取得または設定します。true の場合、レイヤーに含まれるすべてのアートワークをアートボードに表示します。 |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | このレイヤーがテンプレートレイヤーかどうかを示す値を取得または設定します。 |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | レイヤー名を取得または設定します。レイヤーパネルに表示されるアイテムの名前を指定します。 |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | ラスタ画像を取得します。 |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | 赤色成分を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | ラスタ画像を追加します。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 現在のインスタンスを破棄します。 |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | 文字列データを取得します。 |

## 例

以下のコードは、AI 形式ファイルのラスタ画像設定をロードする方法を示しています。

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### 関連項目

* class [AiDataSection](../aidatasection/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



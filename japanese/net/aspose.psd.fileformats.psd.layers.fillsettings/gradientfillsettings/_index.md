---
title: Class GradientFillSettings
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientFillSettings クラス. グラデーション塗りつぶし効果の設定.
type: docs
weight: 1960
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---
## GradientFillSettings class

グラデーション塗りつぶし効果の設定.

```csharp
public class GradientFillSettings : BaseFillSettings, IGradientFillSettings
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GradientFillSettings](gradientfillsettings/)() | の新しいインスタンスを初期化します`GradientFillSettings`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/alignwithlayer/) { get; set; } | [レイヤーに合わせる]かどうかを示す値を取得または設定します. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/angle/) { get; set; } | 角度を取得または設定します。 |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/color/) { get; set; } | 色を取得または設定します。 |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/colorpoints/) { get; set; } | カラー ポイントを取得または設定します。 |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/dither/) { get; set; } | これが`GradientFillSettings`ディザです。 |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/filltype/) { get; } | 塗りつぶしタイプ |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradientname/) { get; set; } | グラデーションの名前を取得または設定します。 |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/) { get; set; } | グラデーションのタイプを取得または設定します。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/horizontaloffset/) { get; set; } | 水平オフセットをパーセンテージで取得または設定します。 |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/reverse/) { get; set; } | これが`GradientFillSettings`逆です. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/scale/) { get; set; } | スケールを取得または設定します。 |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/transparencypoints/) { get; set; } | 透明度ポイントを取得または設定します。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/verticaloffset/) { get; set; } | 垂直方向のオフセットをパーセンテージで取得または設定します. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addcolorpoint/)() | カラーポイントを追加します。 |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addtransparencypoint/)() | カラーポイントを追加します。 |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removecolorpoint/)(IGradientColorPoint) | カラー ポイントを削除します。 |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removetransparencypoint/)(IGradientTransparencyPoint) | 透過ポイントを削除します。 |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/generatelfx2resourcenodes/)() | LFX2 リソース ノードを生成します。 |

### 例

次のコードは、塗りつぶしタイプ - グラデーションを使用したストローク エフェクト レイヤーのサポートを示しています。

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}
void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokeGradientChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientStroke.BlendMode);
    AssertAreEqual((byte)255, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // カラーポイント
    var colorPoints = fillSettings.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(Color.Black, colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.White, colorPoints[1].Color);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // 透明度ポイント
    var transparencyPoints = fillSettings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // テスト編集
    fillSettings.Color = Color.Green;

    gradientStroke.Opacity = 127;
    gradientStroke.BlendMode = BlendMode.Color;

    fillSettings.AlignWithLayer = false;
    fillSettings.GradientType = GradientType.Radial;
    fillSettings.Angle = 45;
    fillSettings.Dither = true;
    fillSettings.HorizontalOffset = 15;
    fillSettings.VerticalOffset = 11;
    fillSettings.Reverse = true;

    // 新しいカラーポイントを追加
    var colorPoint = fillSettings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // 前のポイントの位置を変更
    fillSettings.ColorPoints[1].Location = 1899;

    // 新しい透過ポイントを追加
    var transparencyPoint = fillSettings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // 前の透過ポイントの位置を変更
    fillSettings.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// 編集後のテストファイル
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Green, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // カラーポイントをチェック
    AssertAreEqual(3, fillSettings.ColorPoints.Length);

    var point = fillSettings.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Black, point.Color);
    AssertAreEqual(0, point.Location);

    point = fillSettings.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.White, point.Color);
    AssertAreEqual(1899, point.Location);

    point = fillSettings.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // 透過ポイントをチェック
    AssertAreEqual(3, fillSettings.TransparencyPoints.Length);

    var transparencyPoint = fillSettings.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### 関連項目

* class [BaseFillSettings](../basefillsettings/)
* interface [IGradientFillSettings](../igradientfillsettings/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* 組み立て [Aspose.PSD](../../)



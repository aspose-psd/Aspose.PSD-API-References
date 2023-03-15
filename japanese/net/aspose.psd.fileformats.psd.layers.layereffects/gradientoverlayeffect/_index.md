---
title: Class GradientOverlayEffect
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.GradientOverlayEffect クラス. グラデーションレイヤー効果
type: docs
weight: 2130
url: /ja/net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/
---
## GradientOverlayEffect class

グラデーションレイヤー効果

```csharp
public class GradientOverlayEffect : ILayerEffect
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/blendmode/) { get; set; } | ブレンド モードを取得または設定します。 |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/) { get; } | エフェクトのタイプを取得します |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/isvisible/) { get; set; } | このインスタンスが表示されるかどうかを示す値を取得または設定します. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/opacity/) { get; set; } | 不透明度を取得または設定します。 |
| [Settings](../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/settings/) { get; set; } | 設定を取得または設定します。 |

### 例

次のコードは、グラデーション オーバーレイ効果のサポートを示しています。

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

string sourceFileName = "GradientOverlay.psd";
string exportPath = "GradientOverlayChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientOverlay = (GradientOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientOverlay.BlendMode);
    AssertAreEqual((byte)255, gradientOverlay.Opacity);
    AssertAreEqual(true, gradientOverlay.IsVisible);

    var settings = gradientOverlay.Settings;
    AssertAreEqual(Color.Empty, settings.Color);
    AssertAreEqual(FillType.Gradient, settings.FillType);
    AssertAreEqual(true, settings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, settings.GradientType);
    AssertIsTrue(Math.Abs(33 - settings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, settings.Dither);
    AssertIsTrue(Math.Abs(129 - settings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(156 - settings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, settings.Reverse);

    // カラーポイント
    var colorPoints = settings.ColorPoints;
    AssertAreEqual(3, colorPoints.Length);

    AssertAreEqual(Color.FromArgb(9, 0, 178), colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.Red, colorPoints[1].Color);
    AssertAreEqual(2048, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    AssertAreEqual(Color.FromArgb(255, 252, 0), colorPoints[2].Color);
    AssertAreEqual(4096, colorPoints[2].Location);
    AssertAreEqual(50, colorPoints[2].MedianPointLocation);

    // 透明度ポイント
    var transparencyPoints = settings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // テスト編集
    settings.Color = Color.Green;

    gradientOverlay.Opacity = 193;
    gradientOverlay.BlendMode = BlendMode.Lighten;

    settings.AlignWithLayer = false;
    settings.GradientType = GradientType.Radial;
    settings.Angle = 45;
    settings.Dither = true;
    settings.HorizontalOffset = 15;
    settings.VerticalOffset = 11;
    settings.Reverse = true;

    // 新しいカラーポイントを追加
    var colorPoint = settings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // 前のポイントの位置を変更
    settings.ColorPoints[2].Location = 3000;

    // 新しい透過ポイントを追加
    var transparencyPoint = settings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // 前の透過ポイントの位置を変更
    settings.TransparencyPoints[1].Location = 2315;
    im.Save(exportPath);
}

// 編集後のテストファイル
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientOverlay = (GradientOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Lighten, gradientOverlay.BlendMode);
    AssertAreEqual((byte)193, gradientOverlay.Opacity);
    AssertAreEqual(true, gradientOverlay.IsVisible);

    var fillSettings = gradientOverlay.Settings;
    AssertAreEqual(Color.Empty, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // カラーポイントをチェック
    AssertAreEqual(4, fillSettings.ColorPoints.Length);

    var point = fillSettings.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.FromArgb(9, 0, 178), point.Color);
    AssertAreEqual(0, point.Location);

    point = fillSettings.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Red, point.Color);
    AssertAreEqual(2048, point.Location);

    point = fillSettings.ColorPoints[2];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.FromArgb(255, 252, 0), point.Color);
    AssertAreEqual(3000, point.Location);

    point = fillSettings.ColorPoints[3];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // 透過ポイントをチェック
    AssertAreEqual(3, fillSettings.TransparencyPoints.Length);

    var transparencyPoint = fillSettings.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.0, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.0, transparencyPoint.Opacity);
    AssertAreEqual(2315, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.0, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### 関連項目

* interface [ILayerEffect](../ilayereffect/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 組み立て [Aspose.PSD](../../)



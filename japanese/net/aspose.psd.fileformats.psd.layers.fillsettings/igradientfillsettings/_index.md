---
title: "インターフェイス IGradientFillSettings"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings インターフェイス。 グラデーション塗り設定の基本インターフェイス"
type: docs
weight: 2130
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
{{< psd/tize >}}
## IGradientFillSettings interface

グラデーション塗り設定の基本インターフェイスです。

```csharp
public interface IGradientFillSettings : IFillSettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | [align with layer] かどうかを示す値を取得または設定します。 |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | 取得または設定します。角度。 |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | この `IGradientFillSettings` がディザリングかどうかを示す値を取得または設定します。 |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradient/) { get; set; } | 特定のグラデーション定義インスタンス（Solid/Noise）を取得または設定します。 |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | グラデーションのタイプを取得または設定します。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | 取得または設定します。水平オフセット。 |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/) { get; set; } | グラデーションの補間方法を取得または設定します。 |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | この `IGradientFillSettings` が逆方向かどうかを示す値を取得または設定します。 |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | **normalized** グラデーションスケール（パーセンテージ）を取得または設定します。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | 取得または設定します。垂直オフセット。 |

## 例

次の例は、グラデーション FillLayer のサポートと IGradientFillSettings の編集オプションを示しています。

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string outputFile = "ComplexGradientFillLayer_output.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Gradient)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (GradientFillSettings)fillLayer.FillSettings;
            var solidGradient = (SolidGradient)settings.Gradient;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             solidGradient.TransparencyPoints.Length != 3 ||
             solidGradient.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - solidGradient.TransparencyPoints[0].Opacity) > 0.25 ||
             solidGradient.TransparencyPoints[0].Location != 0 ||
             solidGradient.TransparencyPoints[0].MedianPointLocation != 50 ||
             solidGradient.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             solidGradient.ColorPoints[0].Location != 0 ||
             solidGradient.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(solidGradient.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(solidGradient.TransparencyPoints);
            colorPoints.Add(new GradientColorPoint()
            {
                Color = Color.Violet,
                Location = 4096,
                MedianPointLocation = 75
            });
            colorPoints[1].Location = 3000;
            transparencyPoints.Add(new GradientTransparencyPoint()
            {
                Opacity = 80.0,
                Location = 4096,
                MedianPointLocation = 25
            });
            transparencyPoints[2].Location = 3000;
            solidGradient.ColorPoints = colorPoints.ToArray();
            solidGradient.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### 関連項目

* interface [IFillSettings](../ifillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)



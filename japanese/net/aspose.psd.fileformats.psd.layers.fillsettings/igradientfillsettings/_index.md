---
title: Interface IGradientFillSettings
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings インターフェース. 塗りつぶし設定のベース インターフェイス
type: docs
weight: 2010
url: /ja/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
## IGradientFillSettings interface

塗りつぶし設定のベース インターフェイス

```csharp
public interface IGradientFillSettings : IFillSettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | [レイヤーに合わせる]かどうかを示す値を取得または設定します. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | 角度を取得または設定します。 |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/color/) { get; set; } | 色を取得または設定します。 |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/colorpoints/) { get; set; } | カラー ポイントを取得します。 |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | これが`IGradientFillSettings`ディザです。 |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradientname/) { get; set; } | グラデーションの名前を取得または設定します。 |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | グラデーションのタイプを取得または設定します。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | 水平オフセットを取得または設定します。 |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | これが`IGradientFillSettings`逆です. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | スケールを取得または設定します。 |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/transparencypoints/) { get; set; } | 透過ポイントを取得します。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | 垂直オフセットを取得または設定します。 |

### 例

次の例は、Gradient FillLayer のサポートと IGradientFillSettings 編集オプションを示しています。

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
            var settings = (IGradientFillSettings)fillLayer.FillSettings;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             settings.TransparencyPoints.Length != 3 ||
             settings.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - settings.TransparencyPoints[0].Opacity) > 0.25 ||
             settings.TransparencyPoints[0].Location != 0 ||
             settings.TransparencyPoints[0].MedianPointLocation != 50 ||
             settings.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             settings.ColorPoints[0].Location != 0 ||
             settings.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(settings.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(settings.TransparencyPoints);
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
            settings.ColorPoints = colorPoints.ToArray();
            settings.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### 関連項目

* interface [IFillSettings](../ifillsettings/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* 組み立て [Aspose.PSD](../../)



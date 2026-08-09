---
title: "接口 IGradientFillSettings"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings 接口。 Gradient 填充设置的基础接口"
type: docs
weight: 2130
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
{{< psd/tize >}}
## IGradientFillSettings interface

基础渐变填充设置接口。

```csharp
public interface IGradientFillSettings : IFillSettings
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | 获取或设置一个值，指示是否 [align with layer]。 |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | 获取或设置角度。 |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | 获取或设置一个值，指示此 `IGradientFillSettings` 是否抖动。 |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradient/) { get; set; } | 获取或设置特定的渐变定义实例（Solid/Noise）。 |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | 获取或设置渐变的类型。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | 获取或设置水平偏移。 |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/) { get; set; } | 获取或设置渐变的插值方法。 |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | 获取或设置一个值，指示此 `IGradientFillSettings` 是否反向。 |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | 获取或设置 **normalized** 渐变比例（百分比）。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | 获取或设置垂直偏移。 |

## 示例

以下示例演示了 Gradient FillLayer 的支持以及 IGradientFillSettings 的编辑选项。

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

### 另请参阅

* interface [IFillSettings](../ifillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)



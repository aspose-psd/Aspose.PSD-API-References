---
title: Interface IGradientFillSettings
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings 界面. 填充设置的基本界面
type: docs
weight: 2010
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
## IGradientFillSettings interface

填充设置的基本界面

```csharp
public interface IGradientFillSettings : IFillSettings
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | 获取或设置一个值，指示是否[与图层对齐]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | 获取或设置角度。 |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/color/) { get; set; } | 获取或设置颜色。 |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/colorpoints/) { get; set; } | 获取颜色点。 |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | 获取或设置一个值，指示是否这`IGradientFillSettings`是抖动. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradientname/) { get; set; } | 获取或设置渐变的名称。 |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | 获取或设置渐变的类型。 |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | 获取或设置水平偏移量。 |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | 获取或设置一个值，指示是否这`IGradientFillSettings`是反向的. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | 获取或设置比例。 |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/transparencypoints/) { get; set; } | 获取透明度点。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | 获取或设置垂直偏移量。 |

### 例子

以下示例演示了 Gradient FillLayer 支持和 IGradientFillSettings 编辑选项。

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

### 也可以看看

* interface [IFillSettings](../ifillsettings/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* 部件 [Aspose.PSD](../../)



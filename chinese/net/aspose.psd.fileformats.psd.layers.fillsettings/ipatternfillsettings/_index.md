---
title: Interface IPatternFillSettings
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IPatternFillSettings 界面. 图案填充设置界面
type: docs
weight: 2030
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/
---
## IPatternFillSettings interface

图案填充设置界面

```csharp
public interface IPatternFillSettings : IFillSettings
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/horizontaloffset/) { get; set; } | 获取或设置水平偏移量。 |
| [Linked](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/linked/) { get; set; } | 获取或设置一个值，指示是否这`IPatternFillSettings`链接. |
| [PatternData](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patterndata/) { get; set; } | 获取或设置模式数据。 |
| [PatternHeight](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternheight/) { get; set; } | 获取或设置图案的高度。 |
| [PatternId](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternid/) { get; set; } | 获取或设置模式标识符。 |
| [PatternName](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternname/) { get; set; } | 获取或设置模式的名称。 |
| [PatternWidth](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/patternwidth/) { get; set; } | 获取或设置图案的宽度。 |
| [PointType](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/pointtype/) { get; set; } | 获取或设置点的类型。 |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/scale/) { get; set; } | 获取或设置比例。 |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings/verticaloffset/) { get; set; } | 获取或设置垂直偏移量。 |

### 例子

下面的代码保存带有图案填充图层的图像，并演示 Aspose.PSD 如何渲染图案。

```csharp
[C#]

string sourceFile = "sample.psd";
string outputFile = "sample_out.psd";
string outputPngFile = "sample_out.png";

// 将现有图像加载到 PsdImage 类的实例中
using (var image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var layer in image.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var settings = (IPatternFillSettings)fillLayer.FillSettings;
            settings.HorizontalOffset = -5;
            settings.VerticalOffset = 12;
            settings.Scale = 300;
            settings.Linked = true;
            settings.PatternData = new int[]
                                       {
                                           Color.Black.ToArgb(), Color.Red.ToArgb(),
                                           Color.Green.ToArgb(), Color.Blue.ToArgb(),
                                           Color.White.ToArgb(), Color.AliceBlue.ToArgb(),
                                           Color.Violet.ToArgb(), Color.Chocolate.ToArgb(),
                                           Color.IndianRed.ToArgb(), Color.DarkOliveGreen.ToArgb(),
                                           Color.CadetBlue.ToArgb(), Color.YellowGreen.ToArgb(),
                                           Color.Black.ToArgb(), Color.Azure.ToArgb(),
                                           Color.ForestGreen.ToArgb(), Color.Sienna.ToArgb(),
                                       };

            settings.PatternHeight = 4;
            settings.PatternWidth = 4;

            settings.PatternName = "$$$/Presets/Patterns/ColorfulSquare=Colorful Square New\0";
            settings.PatternId = Guid.NewGuid().ToString() + "\0";

            fillLayer.Update();
            break;
        }
    }

    image.Save(outputFile, new PsdOptions(image));
    image.Save(outputPngFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 也可以看看

* interface [IFillSettings](../ifillsettings/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* 部件 [Aspose.PSD](../../)



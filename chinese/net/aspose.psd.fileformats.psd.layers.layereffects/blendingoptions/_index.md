---
title: Class BlendingOptions
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions 班级. 混合选项它是 Lfx2Resource 的包装器为图层 effects 提供 api
type: docs
weight: 2100
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
## BlendingOptions class

混合选项。它是 Lfx2Resource 的包装器，为图层 effects 提供 api

```csharp
public class BlendingOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; } | 获取效果。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | 添加颜色叠加。 |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | 添加阴影效果。 |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | 添加渐变叠加。 |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | 添加内阴影效果。 |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | 添加外发光效果。 |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | 添加图案覆盖。 |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | 添加描边效果。 |

### 例子

以下代码演示了如何更改内阴影图层效果的设置。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// 将现有图像加载到 PsdImage 类的实例中
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 部件 [Aspose.PSD](../../)



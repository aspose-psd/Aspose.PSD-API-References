---
title: Class DropShadowEffect
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.DropShadowEffect 班级. 投影图层效果
type: docs
weight: 2120
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

投影图层效果

```csharp
public class DropShadowEffect : IShadowEffect
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/) { get; set; } | 获取或设置角度（以度为单位）。 |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/) { get; set; } | 获取或设置混合模式。 |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/) { get; set; } | 获取或设置颜色。 |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance/) { get; set; } | 获取或设置以像素为单位的距离。 |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/) { get; } | 获取一种效果 |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/) { get; set; } | 获取或设置一个值，指示此实例是否可见。 |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout/) { get; set; } | 获取或设置一个值，指示是否 [knocks out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise/) { get; set; } | 获取或设置噪声。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity/) { get; set; } | 获取或设置不透明度。 |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size/) { get; set; } | 获取或设置以像素为单位的模糊值。 |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread/) { get; set; } | 获取或设置百分比形式的强度。 |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight/) { get; set; } | 获取或设置一个值，指示是否[在所有图层效果中使用此角度]。 |

### 例子

以下代码演示了对 PsdImage.GlobalAngle 属性的支持以更改全局角度值。

```csharp
[C#]

// 当 DropShadowEffect.UseGlobalLight 属性为“true”时，DropShadowEffect 对象使用 PsdImage.GlobalAngle 属性中的角度值。

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

以下代码演示了如何使用 DropShadowEffect 的 Opacity 属性。

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // 不透明度 = 20 的示例
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // 不透明度 = 20 的示例0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### 也可以看看

* interface [IShadowEffect](../ishadoweffect/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 部件 [Aspose.PSD](../../)



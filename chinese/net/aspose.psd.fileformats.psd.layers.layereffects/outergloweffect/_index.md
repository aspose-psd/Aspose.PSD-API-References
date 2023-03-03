---
title: Class OuterGlowEffect
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect 班级. 外发光层效果
type: docs
weight: 2170
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
## OuterGlowEffect class

外发光层效果

```csharp
public class OuterGlowEffect : ILayerEffect
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | 获取或设置混合模式。 |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | 获取类型效果type |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | 获取或设置颜色。 |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | 获取或设置角度（以度为单位）。 |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | 获取或设置启用的抗锯齿效果 |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | 获取或设置一个值，指示是否 [knocks out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | 获取或设置一个值，指示此实例是否可见。 |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | 获取或设置噪声。 |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | 获取或设置噪声。 |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | 获取或设置不透明度。 |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | 获取或设置噪声。 |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; } | 获取以像素为单位的模糊值。 |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | 获取或设置百分比形式的强度。 |

### 例子

以下代码演示了 OuterGlowEffect 支持。

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### 也可以看看

* interface [ILayerEffect](../ilayereffect/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 部件 [Aspose.PSD](../../)



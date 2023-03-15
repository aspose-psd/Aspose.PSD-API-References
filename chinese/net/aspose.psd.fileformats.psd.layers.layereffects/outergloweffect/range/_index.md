---
title: OuterGlowEffect.Range
second_title: Aspose.PSD for .NET API 参考
description: OuterGlowEffect 财产. 获取或设置噪声
type: docs
weight: 110
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/
---
## OuterGlowEffect.Range property

获取或设置噪声。

```csharp
public int Range { get; set; }
```

### 适当的价值

噪音.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 噪声必须指定为 0 到 100 范围内的百分比 |

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

* class [OuterGlowEffect](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* 部件 [Aspose.PSD](../../../)



---
title: OuterGlowEffect.Intensity
second_title: Aspose.PSD for .NET API 参考
description: OuterGlowEffect 财产. 获取或设置角度以度为单位
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

获取或设置角度（以度为单位）。

```csharp
public int Intensity { get; set; }
```

### 适当的价值

角度.

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



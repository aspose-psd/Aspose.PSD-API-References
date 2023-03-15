---
title: OuterGlowEffect.Spread
second_title: Aspose.PSD for .NET API 参考
description: OuterGlowEffect 财产. 获取或设置百分比形式的强度
type: docs
weight: 130
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
## OuterGlowEffect.Spread property

获取或设置百分比形式的强度。

```csharp
public int Spread { get; set; }
```

### 适当的价值

价差.

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



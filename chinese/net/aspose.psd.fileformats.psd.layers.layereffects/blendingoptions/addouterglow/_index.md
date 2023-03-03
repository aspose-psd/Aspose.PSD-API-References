---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD for .NET API 参考
description: BlendingOptions 方法. 添加外发光效果
type: docs
weight: 60
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

添加外发光效果。

```csharp
public OuterGlowEffect AddOuterGlow()
```

### 返回值

已创建[`OuterGlowEffect`](../../outergloweffect/)对象

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* 部件 [Aspose.PSD](../../../)



---
title: "BlendingOptions.AddOuterGlow"
second_title: "Aspose.PSD for .NET API 参考"
description: "BlendingOptions 方法。添加外发光效果"
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

添加外发光效果。

```csharp
public OuterGlowEffect AddOuterGlow()
```

### 返回值

已创建 [`OuterGlowEffect`](../../outergloweffect/) 对象

## 示例

以下代码演示了对 OuterGlowEffect 的支持。

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

### 另请参阅

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



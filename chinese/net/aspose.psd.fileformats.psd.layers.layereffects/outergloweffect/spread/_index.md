---
title: "OuterGlowEffect.Spread"
second_title: "Aspose.PSD for .NET API 参考"
description: "OuterGlowEffect 属性。获取或设置以百分比表示的强度"
type: docs
weight: 130
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
{{< psd/tize >}}
## OuterGlowEffect.Spread property

获取或设置强度（百分比）。

```csharp
public int Spread { get; set; }
```

### Property Value

扩散。

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

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



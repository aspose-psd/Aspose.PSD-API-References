---
title: "OuterGlowEffect.Jitter"
second_title: "Aspose.PSD for .NET API 参考"
description: "OuterGlowEffect 属性。获取或设置噪声"
type: docs
weight: 80
url: /zh/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
{{< psd/tize >}}
## OuterGlowEffect.Jitter property

获取或设置噪声。

```csharp
public int Jitter { get; set; }
```

### Property Value

噪声。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 噪声必须以百分比形式指定，范围为 0 到 100 |

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



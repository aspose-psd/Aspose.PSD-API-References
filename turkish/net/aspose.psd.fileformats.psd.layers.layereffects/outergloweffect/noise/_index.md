---
title: "OuterGlowEffect.Noise"
second_title: "Aspose.PSD for .NET API Referansı"
description: "OuterGlowEffect özelliği. Gürültüyü alır veya ayarlar"
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
{{< psd/tize >}}
## OuterGlowEffect.Noise property

Gürültüyü alır veya ayarlar.

```csharp
public int Noise { get; set; }
```

### Property Value

Gürültü.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Gürültü, yüzde olarak 0 ile 100 arasında belirtilmelidir |

## Örnekler

Aşağıdaki kod, OuterGlowEffect desteğini gösterir.

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

### Ayrıca Bakınız

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



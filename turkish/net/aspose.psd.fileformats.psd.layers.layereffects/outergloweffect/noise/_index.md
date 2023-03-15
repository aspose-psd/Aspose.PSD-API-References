---
title: OuterGlowEffect.Noise
second_title: Aspose.PSD for .NET API Referansı
description: OuterGlowEffect mülk. Gürültüyü alır veya ayarlar.
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
## OuterGlowEffect.Noise property

Gürültüyü alır veya ayarlar.

```csharp
public int Noise { get; set; }
```

### Mülk değeri

Gürültü.

### istisnalar

| istisna | şart |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Gürültü, 0 ila 100 aralığında yüzde olarak belirtilmelidir |

### Örnekler

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

### Ayrıca bakınız

* class [OuterGlowEffect](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* toplantı [Aspose.PSD](../../../)



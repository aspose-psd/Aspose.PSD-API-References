---
title: OuterGlowEffect.Spread
second_title: Aspose.PSD untuk Referensi .NET API
description: OuterGlowEffect Properti. Mendapat atau menetapkan intensitas sebagai persen.
type: docs
weight: 130
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
## OuterGlowEffect.Spread property

Mendapat atau menetapkan intensitas sebagai persen.

```csharp
public int Spread { get; set; }
```

### Nilai properti

Spread.

### Contoh

Kode berikut menunjukkan dukungan OuterGlowEffect.

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

### Lihat juga

* class [OuterGlowEffect](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* perakitan [Aspose.PSD](../../../)



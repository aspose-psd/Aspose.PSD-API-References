---
title: OuterGlowEffect.BlendMode
second_title: Aspose.PSD untuk Referensi .NET API
description: OuterGlowEffect Properti. Mendapat atau menyetel mode campuran.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

Mendapat atau menyetel mode campuran.

```csharp
public BlendMode BlendMode { get; set; }
```

### Nilai properti

Mode campuran.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* perakitan [Aspose.PSD](../../../)



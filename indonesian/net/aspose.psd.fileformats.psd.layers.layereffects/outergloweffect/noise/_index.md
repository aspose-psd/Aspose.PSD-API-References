---
title: OuterGlowEffect.Noise
second_title: Aspose.PSD untuk Referensi .NET API
description: OuterGlowEffect Properti. Mendapat atau mengatur kebisingan.
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
## OuterGlowEffect.Noise property

Mendapat atau mengatur kebisingan.

```csharp
public int Noise { get; set; }
```

### Nilai properti

Kebisingan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Kebisingan harus ditentukan sebagai persentase dalam rentang dari 0 hingga 100 |

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



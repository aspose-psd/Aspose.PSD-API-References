---
title: OuterGlowEffect.Intensity
second_title: Aspose.PSD untuk Referensi .NET API
description: OuterGlowEffect Properti. Mendapatkan atau mengatur sudut dalam derajat.
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

Mendapatkan atau mengatur sudut dalam derajat.

```csharp
public int Intensity { get; set; }
```

### Nilai properti

Sudut.

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



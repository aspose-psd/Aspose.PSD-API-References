---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD untuk Referensi .NET API
description: BlendingOptions metode. Menambahkan efek cahaya luar.
type: docs
weight: 60
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Menambahkan efek cahaya luar.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Nilai Pengembalian

Dibuat[`OuterGlowEffect`](../../outergloweffect/) objek

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* perakitan [Aspose.PSD](../../../)



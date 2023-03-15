---
title: OuterGlowEffect.Size
second_title: Aspose.PSD untuk Referensi .NET API
description: OuterGlowEffect Properti. Mendapat nilai buram dalam piksel.
type: docs
weight: 120
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

Mendapat nilai buram dalam piksel.

```csharp
public int Size { get; }
```

### Nilai properti

Ukuran.

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



---
title: "OuterGlowEffect.Intensity"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "OuterGlowEffect property. Mendapatkan atau mengatur sudut dalam derajat"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
{{< psd/tize >}}
## OuterGlowEffect.Intensity property

Mendapatkan atau mengatur sudut dalam derajat.

```csharp
public int Intensity { get; set; }
```

### Property Value

Sudut.

## Contoh

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

### Lihat Juga

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



---
title: OuterGlowEffect.Jitter
second_title: Aspose.PSD για Αναφορά API .NET
description: OuterGlowEffect ιδιοκτησία. Λαμβάνει ή ρυθμίζει το θόρυβο.
type: docs
weight: 80
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
## OuterGlowEffect.Jitter property

Λαμβάνει ή ρυθμίζει το θόρυβο.

```csharp
public int Jitter { get; set; }
```

### Αξία περιουσίας

Ο θόρυβος.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Ο θόρυβος πρέπει να προσδιορίζεται ως ποσοστό στην περιοχή από 0 έως 100 |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη OuterGlowEffect.

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

### Δείτε επίσης

* class [OuterGlowEffect](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* συνέλευση [Aspose.PSD](../../../)



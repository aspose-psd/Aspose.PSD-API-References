---
title: "OuterGlowEffect.Jitter"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "OuterGlowEffect ιδιότητα. Λαμβάνει ή ορίζει τον θόρυβο"
type: docs
weight: 80
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
{{< psd/tize >}}
## OuterGlowEffect.Jitter property

Λαμβάνει ή ορίζει τον θόρυβο.

```csharp
public int Jitter { get; set; }
```

### Property Value

Ο θόρυβος.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Ο θόρυβος πρέπει να καθορίζεται ως ποσοστό στο εύρος από 0 έως 100 |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του OuterGlowEffect.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



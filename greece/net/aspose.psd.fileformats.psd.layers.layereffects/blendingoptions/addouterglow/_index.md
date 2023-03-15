---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD για Αναφορά API .NET
description: BlendingOptions μέθοδος. Προσθέτει το εφέ εξωτερικής λάμψης.
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Προσθέτει το εφέ εξωτερικής λάμψης.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Επιστρεφόμενη Αξία

Δημιουργήθηκε[`OuterGlowEffect`](../../outergloweffect/) αντικείμενο

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* συνέλευση [Aspose.PSD](../../../)



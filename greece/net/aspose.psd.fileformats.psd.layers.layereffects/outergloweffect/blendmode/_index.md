---
title: OuterGlowEffect.BlendMode
second_title: Aspose.PSD για Αναφορά API .NET
description: OuterGlowEffect ιδιοκτησία. Λαμβάνει ή ρυθμίζει τη λειτουργία ανάμειξης.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

Λαμβάνει ή ρυθμίζει τη λειτουργία ανάμειξης.

```csharp
public BlendMode BlendMode { get; set; }
```

### Αξία περιουσίας

Η λειτουργία ανάμειξης.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* συνέλευση [Aspose.PSD](../../../)



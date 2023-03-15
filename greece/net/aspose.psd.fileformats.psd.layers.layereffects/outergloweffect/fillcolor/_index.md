---
title: OuterGlowEffect.FillColor
second_title: Aspose.PSD για Αναφορά API .NET
description: OuterGlowEffect ιδιοκτησία. Παίρνει ή ρυθμίζει το χρώμα.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/
---
## OuterGlowEffect.FillColor property

Παίρνει ή ρυθμίζει το χρώμα.

```csharp
public IFillSettings FillColor { get; set; }
```

### Αξία περιουσίας

Το χρώμα.

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

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [OuterGlowEffect](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* συνέλευση [Aspose.PSD](../../../)



---
title: OuterGlowEffect.Size
second_title: Aspose.PSD για Αναφορά API .NET
description: OuterGlowEffect ιδιοκτησία. Λαμβάνει την τιμή θαμπώματος σε pixel.
type: docs
weight: 120
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
## OuterGlowEffect.Size property

Λαμβάνει την τιμή θαμπώματος σε pixel.

```csharp
public int Size { get; }
```

### Αξία περιουσίας

Το μέγεθος.

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



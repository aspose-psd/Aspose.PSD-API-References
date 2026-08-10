---
title: "BlendingOptions.AddOuterGlow"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "BlendingOptions μέθοδος. Προσθέτει το εφέ εξωτερικής λάμψης"
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

Προσθέτει το εξωτερικό εφέ λάμψης.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Τιμή Επιστροφής

Δημιουργήθηκε [`OuterGlowEffect`](../../outergloweffect/) αντικείμενο

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



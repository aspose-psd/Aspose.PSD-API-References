---
title: "OuterGlowEffect.Intensity"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "OuterGlowEffect ιδιότητα. Λαμβάνει ή ορίζει τη γωνία σε μοίρες"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
{{< psd/tize >}}
## OuterGlowEffect.Intensity property

Λαμβάνει ή ορίζει τη γωνία σε μοίρες.

```csharp
public int Intensity { get; set; }
```

### Property Value

Η γωνία.

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



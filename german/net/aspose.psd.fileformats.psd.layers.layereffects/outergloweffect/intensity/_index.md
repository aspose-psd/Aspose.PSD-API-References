---
title: OuterGlowEffect.Intensity
second_title: Aspose.PSD für .NET-API-Referenz
description: OuterGlowEffect eigendom. Ruft den Winkel in Grad ab oder legt ihn fest.
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

Ruft den Winkel in Grad ab oder legt ihn fest.

```csharp
public int Intensity { get; set; }
```

### Eigentumswert

Der Winkel.

### Beispiele

Der folgende Code demonstriert die OuterGlowEffect-Unterstützung.

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

### Siehe auch

* class [OuterGlowEffect](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* Montage [Aspose.PSD](../../../)



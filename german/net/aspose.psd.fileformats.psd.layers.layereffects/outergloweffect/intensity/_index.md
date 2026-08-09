---
title: "OuterGlowEffect.Intensity"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "OuterGlowEffect Eigenschaft. Gibt den Winkel in Grad zurück oder legt ihn fest"
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
{{< psd/tize >}}
## OuterGlowEffect.Intensity property

Liest oder setzt den Winkel in Grad.

```csharp
public int Intensity { get; set; }
```

### Property Value

Der Winkel.

## Beispiele

Der folgende Code demonstriert die Unterstützung von OuterGlowEffect.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



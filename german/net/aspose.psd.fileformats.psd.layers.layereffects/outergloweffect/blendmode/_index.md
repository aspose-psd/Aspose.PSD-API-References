---
title: "OuterGlowEffect.BlendMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "OuterGlowEffect property. Gibt einen Wert zurück oder legt ihn fest, der den Mischmodus angibt."
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
{{< psd/tize >}}
## OuterGlowEffect.BlendMode property

Liest oder setzt den Mischmodus.

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

Der Mischmodus.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)



---
title: "OuterGlowEffect.Noise"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "OuterGlowEffect Eigenschaft. Gibt das Rauschen zurück oder legt es fest"
type: docs
weight: 90
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/
---
{{< psd/tize >}}
## OuterGlowEffect.Noise property

Liest oder setzt das Rauschen.

```csharp
public int Noise { get; set; }
```

### Property Value

Das Rauschen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Rauschen muss als Prozentsatz im Bereich von 0 bis 100 angegeben werden. |

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



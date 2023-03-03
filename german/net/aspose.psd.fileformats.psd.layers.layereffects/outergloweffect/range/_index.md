---
title: OuterGlowEffect.Range
second_title: Aspose.PSD für .NET-API-Referenz
description: OuterGlowEffect eigendom. Ruft das Rauschen ab oder legt es fest.
type: docs
weight: 110
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/
---
## OuterGlowEffect.Range property

Ruft das Rauschen ab oder legt es fest.

```csharp
public int Range { get; set; }
```

### Eigentumswert

Der Lärm.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Das Rauschen muss in Prozent im Bereich von 0 bis 100 angegeben werden |

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



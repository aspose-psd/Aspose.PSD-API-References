---
title: VibranceLayer.Vibrance
second_title: Aspose.PSD voor .NET API-referentie
description: VibranceLayer eigendom. Krijgt of stelt de levendigheid in.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

Krijgt of stelt de levendigheid in.

```csharp
public int Vibrance { get; set; }
```

### Eigendoms-waarde

De levendigheid.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | Levendigheid moet binnen het bereik van -180 tot +180 liggen |

### Voorbeelden

Het volgende codevoorbeeld demonstreert de ondersteuning van de VibranceLayer-laag en de mogelijkheid om deze aanpassing te bewerken.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Een nieuwe VibranceLayer maken
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Zie ook

* class [VibranceLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* montage [Aspose.PSD](../../../)



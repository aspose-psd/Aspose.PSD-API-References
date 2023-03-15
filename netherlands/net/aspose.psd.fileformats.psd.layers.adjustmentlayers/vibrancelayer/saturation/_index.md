---
title: VibranceLayer.Saturation
second_title: Aspose.PSD voor .NET API-referentie
description: VibranceLayer eigendom. Verkrijgt of stelt de verzadiging in.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

Verkrijgt of stelt de verzadiging in.

```csharp
public int Saturation { get; set; }
```

### Eigendoms-waarde

De verzadiging.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | De verzadiging moet tussen -100 en +100 liggen |

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



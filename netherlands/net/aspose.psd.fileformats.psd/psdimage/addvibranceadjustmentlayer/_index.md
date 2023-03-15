---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD voor .NET API-referentie
description: PsdImage methode. Voegt de aanpassingslaag Levendigheid toe.
type: docs
weight: 430
url: /nl/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Voegt de aanpassingslaag Levendigheid toe.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Winstwaarde

Een nieuw gemaakte Vibrance-laag.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* montage [Aspose.PSD](../../../)



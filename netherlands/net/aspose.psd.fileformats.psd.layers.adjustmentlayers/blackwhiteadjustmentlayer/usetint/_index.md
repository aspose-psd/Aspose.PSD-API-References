---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD voor .NET API-referentie
description: BlackWhiteAdjustmentLayer eigendom. Haalt of stelt een waarde in die aangeeft of tintkleur wordt gebruikt.
type: docs
weight: 120
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

Haalt of stelt een waarde in die aangeeft of [tintkleur] wordt gebruikt.

```csharp
public bool UseTint { get; set; }
```

### Eigendoms-waarde

`WAAR` indien gebruikt [tintkleur]; anders,`vals` .

### Voorbeelden

Het volgende voorbeeld laat zien hoe u de eigenschappen van de zwart-wit aanpassingslaag in Aspose.PSD kunt manipuleren

```csharp
[C#]

sourceFileName = "BlackWhiteAdjustmentLayerStripesMask.psd";
outputFileName = "OutputBlackWhiteAdjustmentLayerStripesMask.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    var blwhLayer = (BlackWhiteAdjustmentLayer)image.Layers[1];

    blwhLayer.Reds = 15;
    blwhLayer.Yellows = 25;
    blwhLayer.Greens = 35;
    blwhLayer.Cyans = 10;
    blwhLayer.Blues = 50;
    blwhLayer.Magentas = 105;
    blwhLayer.UseTint = true;
    blwhLayer.BwPresetKind = 4;
    blwhLayer.BlackAndWhitePresetFileName = "bwPresetFileName";
    blwhLayer.TintColorRed = 60;
    blwhLayer.TintColorGreen = 80;
    blwhLayer.TintColorBlue = 200;

    image.Save(outputFileName, new PsdOptions());
}
```

### Zie ook

* class [BlackWhiteAdjustmentLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* montage [Aspose.PSD](../../../)



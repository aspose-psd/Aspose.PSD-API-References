---
title: BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName
second_title: Aspose.PSD voor .NET API-referentie
description: BlackWhiteAdjustmentLayer eigendom. Haalt de bestandsnaam van de zwartwitvoorinstelling op of stelt deze in.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/blackandwhitepresetfilename/
---
## BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName property

Haalt de bestandsnaam van de zwart-witvoorinstelling op of stelt deze in.

```csharp
public string BlackAndWhitePresetFileName { get; set; }
```

### Eigendoms-waarde

De bestandsnaam van de zwart-witvoorinstelling.

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



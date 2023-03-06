---
title: BlackWhiteAdjustmentLayer.Magentas
second_title: Aspose.PSD voor .NET API-referentie
description: BlackWhiteAdjustmentLayer eigendom. Haalt de magentaswaarde op of stelt deze in.
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/magentas/
---
## BlackWhiteAdjustmentLayer.Magentas property

Haalt de magentaswaarde op of stelt deze in.

```csharp
public int Magentas { get; set; }
```

### Eigendoms-waarde

De magenta waarde.

### Voorbeelden

Het volgende voorbeeld laat zien hoe u de zwart-witte aanpassingslaag tijdens runtime kunt toevoegen in Aspose.PSD

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

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



---
title: BlackWhiteAdjustmentLayer.BwPresetKind
second_title: Aspose.PSD för .NET API-referens
description: BlackWhiteAdjustmentLayer fast egendom. Hämtar eller ställer in det svartvita förinställda sortvärdet.
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
## BlackWhiteAdjustmentLayer.BwPresetKind property

Hämtar eller ställer in det svartvita förinställda sortvärdet.

```csharp
public int BwPresetKind { get; set; }
```

### Fastighetsvärde

Det svartvita förinställda sortvärdet.

### Exempel

Följande exempel visar hur du kan manipulera egenskaperna för justeringslager för svartvitt i Aspose.PSD

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

### Se även

* class [BlackWhiteAdjustmentLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* hopsättning [Aspose.PSD](../../../)



---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD för .NET API-referens
description: BlackWhiteAdjustmentLayer fast egendom. Hämtar eller ställer in ett värde som anger om tint color används.
type: docs
weight: 120
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

Hämtar eller ställer in ett värde som anger om [tint color] används.

```csharp
public bool UseTint { get; set; }
```

### Fastighetsvärde

`Sann` om den används [nyansfärg]; annat,`falsk` .

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



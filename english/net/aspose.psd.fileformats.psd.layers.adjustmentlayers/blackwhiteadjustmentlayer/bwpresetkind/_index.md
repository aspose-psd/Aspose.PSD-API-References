---
title: BlackWhiteAdjustmentLayer.BwPresetKind
second_title: Aspose.PSD for .NET API Reference
description: BlackWhiteAdjustmentLayer property. Gets or sets the black and white preset kind value
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.BwPresetKind property

Gets or sets the black and white preset kind value.

```csharp
public int BwPresetKind { get; set; }
```

### Property Value

The black and white preset kind value.

## Examples

The following example demonstrates how you can manipulate the black white adjustment layer properties in Aspose.PSD

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

### See Also

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)



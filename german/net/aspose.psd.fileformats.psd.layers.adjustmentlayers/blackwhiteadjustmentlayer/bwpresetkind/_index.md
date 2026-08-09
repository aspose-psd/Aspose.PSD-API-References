---
title: "BlackWhiteAdjustmentLayer.BwPresetKind"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BlackWhiteAdjustmentLayer-Eigenschaft. Ruft den Schwarz-und-Weiß-Voreinstellungs-Typ ab oder legt ihn fest."
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.BwPresetKind property

Liest oder setzt den black and white Voreinstellungsart Wert.

```csharp
public int BwPresetKind { get; set; }
```

### Property Value

Der Wert des Schwarz-und-Weiß-Voreinstellungs-Typs.

## Beispiele

Das folgende Beispiel zeigt, wie Sie die Eigenschaften des Schwarz-Weiß-Anpassungslayers in Aspose.PSD manipulieren können.

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

### Siehe auch

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)



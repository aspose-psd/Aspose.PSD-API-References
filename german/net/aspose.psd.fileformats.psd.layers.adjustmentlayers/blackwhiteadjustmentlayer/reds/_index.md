---
title: BlackWhiteAdjustmentLayer.Reds
second_title: Aspose.PSD für .NET-API-Referenz
description: BlackWhiteAdjustmentLayer eigendom. Ruft den Rotwert ab oder legt ihn fest.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/reds/
---
## BlackWhiteAdjustmentLayer.Reds property

Ruft den Rotwert ab oder legt ihn fest.

```csharp
public int Reds { get; set; }
```

### Eigentumswert

Der Rotwert.

### Beispiele

Das folgende Beispiel zeigt, wie Sie die Schwarz-Weiß-Anpassungsebene zur Laufzeit in Aspose.PSD hinzufügen können

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

Das folgende Beispiel zeigt, wie Sie die Eigenschaften der Schwarz-Weiß-Anpassungsebene in Aspose.PSD bearbeiten können

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
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* Montage [Aspose.PSD](../../../)



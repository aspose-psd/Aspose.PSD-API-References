---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD für .NET-API-Referenz
description: BlackWhiteAdjustmentLayer eigendom. Ruft einen Wert ab oder legt einen Wert fest der angibt ob Tönungsfarbe verwendet wird.
type: docs
weight: 120
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Tönungsfarbe] verwendet wird.

```csharp
public bool UseTint { get; set; }
```

### Eigentumswert

`WAHR` falls verwendet [Tönungsfarbe]; ansonsten,`FALSCH` .

### Beispiele

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



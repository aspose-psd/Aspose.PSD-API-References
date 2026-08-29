---
title: "BlackWhiteAdjustmentLayer.UseTint"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BlackWhiteAdjustmentLayer Eigenschaft. Gibt einen Wert zurück, der angibt, ob die Tönungsfarbe verwendet wird, oder legt ihn fest"
type: docs
weight: 120
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.UseTint property

Liest oder setzt einen Wert, der angibt, ob [tint color] verwendet wird.

```csharp
public bool UseTint { get; set; }
```

### Property Value

`true` wenn verwendet [tint color]; andernfalls `false`.

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



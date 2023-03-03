---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD per riferimento API .NET
description: BlackWhiteAdjustmentLayer proprietà. Ottiene o imposta un valore che indica se tinta colore viene utilizzato.
type: docs
weight: 120
url: /it/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

Ottiene o imposta un valore che indica se [tinta colore] viene utilizzato.

```csharp
public bool UseTint { get; set; }
```

### Valore della proprietà

`VERO` se usato [tinta colore]; Altrimenti,`falso` .

### Esempi

L'esempio seguente mostra come manipolare le proprietà del livello di regolazione bianco nero in Aspose.PSD

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

### Guarda anche

* class [BlackWhiteAdjustmentLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* assemblea [Aspose.PSD](../../../)



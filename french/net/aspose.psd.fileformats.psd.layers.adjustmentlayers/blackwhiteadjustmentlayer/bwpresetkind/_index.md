---
title: BlackWhiteAdjustmentLayer.BwPresetKind
second_title: Référence de l'API Aspose.PSD pour .NET
description: BlackWhiteAdjustmentLayer propriété. Obtient ou définit la valeur de type prédéfini noir et blanc.
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
## BlackWhiteAdjustmentLayer.BwPresetKind property

Obtient ou définit la valeur de type prédéfini noir et blanc.

```csharp
public int BwPresetKind { get; set; }
```

### Valeur de la propriété

La valeur de genre prédéfinie en noir et blanc.

### Exemples

L'exemple suivant montre comment vous pouvez manipuler les propriétés du calque de réglage noir blanc dans Aspose.PSD

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

### Voir également

* class [BlackWhiteAdjustmentLayer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* Assemblée [Aspose.PSD](../../../)



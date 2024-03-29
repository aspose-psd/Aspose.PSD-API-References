---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Référence de l'API Aspose.PSD pour .NET
description: BlackWhiteAdjustmentLayer propriété. Obtient ou définit une valeur indiquant si la couleur de teinte est utilisée.
type: docs
weight: 120
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

Obtient ou définit une valeur indiquant si la [couleur de teinte] est utilisée.

```csharp
public bool UseTint { get; set; }
```

### Valeur de la propriété

`vrai` si utilisé [couleur de teinte] ; sinon,`FAUX` .

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



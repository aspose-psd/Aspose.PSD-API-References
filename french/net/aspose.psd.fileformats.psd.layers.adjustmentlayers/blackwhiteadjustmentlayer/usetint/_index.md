---
title: "BlackWhiteAdjustmentLayer.UseTint"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BlackWhiteAdjustmentLayer. Obtient ou définit une valeur indiquant si la couleur de teinte est utilisée"
type: docs
weight: 120
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.UseTint property

Obtient ou définit une valeur indiquant si [tint color] est utilisé.

```csharp
public bool UseTint { get; set; }
```

### Property Value

`true` si utilisé [tint color] ; sinon, `false`.

## Exemples

L'exemple suivant montre comment vous pouvez manipuler les propriétés du calque d'ajustement noir et blanc dans Aspose.PSD

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

### Voir aussi

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)



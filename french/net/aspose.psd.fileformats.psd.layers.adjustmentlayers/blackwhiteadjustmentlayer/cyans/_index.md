---
title: "BlackWhiteAdjustmentLayer.Cyans"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété BlackWhiteAdjustmentLayer. Obtient ou définit la valeur des cyans"
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/cyans/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.Cyans property

Obtient ou définit la valeur des cyan.

```csharp
public int Cyans { get; set; }
```

### Property Value

La valeur des cyans.

## Exemples

L'exemple suivant montre comment vous pouvez ajouter le calque d'ajustement noir et blanc à l'exécution dans Aspose.PSD

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



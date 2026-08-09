---
title: "PsdImage.AddBlackWhiteAdjustmentLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PsdImage. Ajoute le calque de réglage noir et blanc."
type: docs
weight: 300
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddBlackWhiteAdjustmentLayer method

Ajoute le calque de réglage noir et blanc.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Valeur de retour

Le calque de réglage noir et blanc créé.

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

### Voir aussi

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)



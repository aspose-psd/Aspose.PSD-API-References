---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdImage méthode. Ajoute le calque de réglage noir blanc.
type: docs
weight: 290
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

Ajoute le calque de réglage noir blanc.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Return_Value

Le calque de réglage noir blanc créé.

### Exemples

L'exemple suivant montre comment vous pouvez ajouter le calque de réglage noir blanc lors de l'exécution dans Aspose.PSD

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

### Voir également

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)



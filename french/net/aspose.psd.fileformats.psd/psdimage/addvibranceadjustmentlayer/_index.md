---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdImage méthode. Ajoute le calque de réglage Vibrance.
type: docs
weight: 430
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Ajoute le calque de réglage Vibrance.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Return_Value

Un calque Vibrance nouvellement créé.

### Exemples

L'exemple de code suivant illustre la prise en charge de la couche VibranceLayer et la possibilité de modifier cet ajustement.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Création d'un nouveau VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Voir également

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)



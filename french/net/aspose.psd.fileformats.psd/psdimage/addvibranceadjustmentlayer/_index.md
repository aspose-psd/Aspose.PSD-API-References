---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PsdImage. Ajoute le calque d'ajustement Vibrance"
type: docs
weight: 490
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

Ajoute le calque de réglage de la vibrance.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Valeur de retour

Un calque Vibrance nouvellement créé.

## Exemples

L'exemple de code suivant démontre la prise en charge du calque VibranceLayer et la capacité à modifier cet ajustement.

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

### Voir aussi

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)



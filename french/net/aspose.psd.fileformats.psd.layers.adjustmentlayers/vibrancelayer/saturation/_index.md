---
title: VibranceLayer.Saturation
second_title: Référence de l'API Aspose.PSD pour .NET
description: VibranceLayer propriété. Obtient ou définit la saturation.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

Obtient ou définit la saturation.

```csharp
public int Saturation { get; set; }
```

### Valeur de la propriété

La saturation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | La saturation doit être comprise entre -100 et +100 |

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

* class [VibranceLayer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* Assemblée [Aspose.PSD](../../../)



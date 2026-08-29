---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété VibranceLayer. Obtient ou définit la saturation"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

Obtient ou définit la saturation.

```csharp
public int Saturation { get; set; }
```

### Property Value

La saturation.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | La saturation doit être comprise entre -100 et +100 |

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

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)



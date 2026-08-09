---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété VibranceLayer. Obtient ou définit la vibrance"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Obtient ou définit la vibrance.

```csharp
public int Vibrance { get; set; }
```

### Property Value

La vibrance.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | La vibrance doit être comprise entre -180 et +180 |

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



---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PsdImage. Ajoute un calque d'ajustement d'inversion"
type: docs
weight: 380
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Ajoute un calque de réglage d'inversion.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Valeur de retour

Le calque d'inversion créé

## Exemples

Le code suivant montre la prise en charge de l'InvertAdjustmentLayer et comment ajouter InvertAdjustmentLayer.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### Voir aussi

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)



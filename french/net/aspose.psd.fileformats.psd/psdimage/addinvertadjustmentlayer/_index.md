---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdImage méthode. Ajoute un calque de réglage inversé.
type: docs
weight: 360
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Ajoute un calque de réglage inversé.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Return_Value

Le calque inversé créé

### Exemples

Le code suivant montre la prise en charge de InvertAdjustmentLayer et comment ajouter InvertAdjustmentLayer.

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

### Voir également

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)



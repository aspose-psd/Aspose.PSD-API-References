---
title: "PsdImage.AddPosterizeAdjustmentLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "PsdImage méthode. Ajoute la couche Posterize Adjustment"
type: docs
weight: 430
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddPosterizeAdjustmentLayer method

Ajoute le calque de réglage Posterize.

```csharp
public PosterizeLayer AddPosterizeAdjustmentLayer()
```

### Valeur de retour

Instance PosterizeLayer.

## Exemples

Le code suivant montre la capacité d'ajouter PosterizeAdjustmentLayer via PsdImage.

```csharp
[C#]

string srcFile = "zendeya.psd";
string outFile = "zendeya.psd.out.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    psdImage.AddPosterizeAdjustmentLayer();
    psdImage.Save(outFile);
}

// Vérifier les modifications enregistrées
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    AssertAreEqual(2, image.Layers.Length);

    PosterizeLayer posterizeLayer = (PosterizeLayer)image.Layers[1];

    AssertAreEqual(true, posterizeLayer is PosterizeLayer);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Voir aussi

* class [PosterizeLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)



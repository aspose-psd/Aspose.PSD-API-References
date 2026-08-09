---
title: "TextLayer.Resize"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode TextLayer. Redimensionne l'image. La valeur par défaut LeftTopToLeftTop est utilisée"
type: docs
weight: 100
url: /fr/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Redimensionne l'image. Le défaut LeftTopToLeftTop est utilisé.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| resizeType | ResizeType | Le type de transformation de redimensionnement [`ResizeType`](../../../aspose.psd/resizetype/) |

## Exemples

Le code suivant démontre la fonction TextLayer.Resize avec le paramètre permettant de choisir le mécanisme de redimensionnement.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Il définit la nouvelle taille du calque texte
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Il définit le mécanisme selon lequel la fonction de redimensionnement redimensionnera le calque (valeur par défaut)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Nouveau mécanisme de redimensionnement pour le calque texte utilisé ici
    // Non seulement le calque mais aussi la matrice de transformation du calque texte seront modifiés
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // La raison du delta est une police par défaut différente
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Tout est OK
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Voir aussi

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)



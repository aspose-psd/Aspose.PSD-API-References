---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété TextLayer. Obtient ou définit la matrice de transformation"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

Obtient ou définit la matrice de transformation

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

La matrice de transformation

## Exemples

Le code suivant montre comment obtenir la taille de police pour n'importe quelle portion de texte dans le calque de texte.

```csharp
[C#]

// Taille de police extraite incorrecte 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Ancienne API (Utilisation de la police du premier paragraphe)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Vérification de la taille de police de base
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Vérification de la taille de police réelle
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Nouvelle API (Une couche de texte peut contenir n'importe quelle quantité de tailles de police)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Vérification de la taille de police de la partie de base
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Vérification de la taille de police de la partie réelle
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Voir aussi

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)



---
title: Class AiLayerSection
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Ai.AiLayerSection classe. La section de couche au format Ai
type: docs
weight: 1270
url: /fr/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

La section de couche au format Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Obtient ou définit la composante de couleur bleue. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Obtient ou définit le numéro de couleur. -1 est la valeur de couleur personnalisée des propriétés Rouge, Vert, Bleu. Spécifie le paramètre de couleur du calque. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Obtient ou définit la valeur dim sous forme de pourcentage. Réduit l'intensité des images liées et des images bitmap contenues dans le calque au pourcentage spécifié. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Obtient ou définit le composant de couleur verte. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est estompé. Réduit l'intensité des images liées et des images bitmap contenues dans le calque. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est verrouillé. Empêche les modifications de l'élément. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est un aperçu. Affiche l'illustration contenue dans le calque en couleur plutôt qu'en contours. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est imprimé. Rend l'illustration contenue dans le calque imprimable si vrai. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est affiché. Affiche toutes les illustrations contenues dans le calque sur la planche graphique si vrai. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est un calque de modèle. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Obtient ou définit le nom du calque. Spécifie le nom de l'élément tel qu'il apparaît dans le panneau Calques. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Obtient les images raster. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Obtient ou définit le composant de couleur rouge. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Ajoute l'image raster. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Supprime l'instance actuelle. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Obtient les données de chaîne. |

### Exemples

Le code suivant montre comment charger les paramètres des images raster dans des fichiers au format AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Voir également

* class [AiDataSection](../aidatasection/)
* espace de noms [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* Assemblée [Aspose.PSD](../../)



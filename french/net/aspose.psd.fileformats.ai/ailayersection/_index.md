---
title: "Classe AiLayerSection"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.FileFormats.Ai.AiLayerSection. La section de calque du format Ai"
type: docs
weight: 1280
url: /fr/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

La section de calque du format Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Obtient ou définit le composant couleur bleu. |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | Obtient ou définit l'index de la couleur. Cet argument peut prendre des valeurs entre –1 et 26. Chaque entier représente une couleur qui peut être attribuée au calque à des fins d'identification par l'utilisateur. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Obtient ou définit le numéro de couleur. -1 correspond à la valeur de couleur personnalisée provenant des propriétés Rouge, Vert, Bleu. Spécifie le réglage de couleur du calque. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Obtient ou définit la valeur d'assombrissement en pourcentage. Réduit l'intensité des images liées et des images bitmap contenues dans le calque au pourcentage spécifié. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Obtient ou définit le composant couleur vert. |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est assombri. Réduit l'intensité des images liées et des images bitmap contenues dans le calque. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est verrouillé. Empêche les modifications de l'élément. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est en aperçu. Affiche le dessin contenu dans le calque en couleur au lieu de le présenter en contours. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est imprimé. Rend le dessin contenu dans le calque imprimable si vrai. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est affiché. Affiche tout le dessin contenu dans le calque sur le plan de travail si vrai. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Obtient ou définit une valeur indiquant si ce calque est un calque modèle. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Obtient ou définit le nom du calque. Spécifie le nom de l'élément tel qu'il apparaît dans le panneau Calques. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Obtient les images raster. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Obtient ou définit le composant de couleur rouge. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Ajoute l'image raster. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Obtient les données de chaîne. |

## Exemples

Le code suivant montre comment charger les paramètres des images raster dans les fichiers au format AI.

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

### Voir aussi

* class [AiDataSection](../aidatasection/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



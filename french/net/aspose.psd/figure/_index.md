---
title: Class Figure
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Figure classe. Le chiffre. Un conteneur pour les formes.
type: docs
weight: 1200
url: /fr/net/aspose.psd/figure/
---
## Figure class

Le chiffre. Un conteneur pour les formes.

```csharp
public class Figure : ObjectWithBounds
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Figure](figure/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Obtient ou définit les limites de l'objet. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Obtient ou définit une valeur indiquant si ce chiffre est fermé. Une figure fermée fera une différence uniquement dans le cas où les formes de la première et de la dernière figure sont des formes continues. Dans ce cas, le premier point de la première forme sera relié par une ligne droite à partir du dernier point de la dernière forme. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Obtient les segments entiers de la figure. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Obtient les formes de la figure. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Ajoute une forme à la figure. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Ajoute une gamme de formes à la figure. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Supprime une forme de la figure. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Supprime une plage de formes de la figure. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Inverse l'ordre des formes de cette figure et l'ordre des points de formes. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |

### Exemples

Ces exemples utilisent GraphicsPath et la classe Graphics pour créer et manipuler des figures sur une surface Image. L'exemple crée une nouvelle image et dessine des chemins à l'aide de la classe GraphicsPath. À la fin, la méthode DrawPath exposée par la classe Graphics est appelée pour restituer les chemins sur la surface. Enfin, l'image est exportée au format de fichier Tiff.

```csharp
[C#]

//Créer une instance de Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créer et initialiser une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Effacer la surface graphique
    graphics.Clear(Color.Wheat);

    //Créer une instance de la classe GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Créer une instance de la classe Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Ajouter des formes à l'objet Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Ajouter un objet Figure à GraphicsPath
    graphicspath.AddFigure(figure);

    // Dessine un chemin avec un objet Pen de couleur noire
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Créer une instance de TiffOptions et définir ses différentes propriétés
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Enregistrer toutes les modifications.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Voir également

* class [ObjectWithBounds](../objectwithbounds/)
* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)



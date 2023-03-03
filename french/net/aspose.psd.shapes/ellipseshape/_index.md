---
title: Class EllipseShape
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Shapes.EllipseShape classe. Représente une forme dellipse.
type: docs
weight: 5490
url: /fr/net/aspose.psd.shapes/ellipseshape/
---
## EllipseShape class

Représente une forme d'ellipse.

```csharp
public class EllipseShape : RectangleShape
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | Initialise une nouvelle instance du`EllipseShape` classe. |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | Initialise une nouvelle instance du`EllipseShape` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Obtient les limites de l'objet. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Obtient le centre de la forme. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Obtient une valeur indiquant si la forme a des segments. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Obtient le point du rectangle inférieur gauche. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Obtient le point du rectangle supérieur gauche. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Obtient la hauteur du rectangle. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Obtient la largeur du rectangle. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Obtient le point du rectangle inférieur droit. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Obtient le point du rectangle supérieur droit. |
| override [Segments](../../aspose.psd.shapes/ellipseshape/segments/) { get; } | Obtient les segments de forme. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Obtient les limites de l'objet. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |

### Exemples

Cet exemple crée une nouvelle Image et dessine une variété de formes en utilisant Figures et GraphicsPath sur la surface Image

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
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    // Ajouter une forme à l'objet Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Créer une instance de la classe Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    // Ajouter une forme à l'objet Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Ajouter un objet Figure à GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // Dessine un chemin avec un objet Pen de couleur noire
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Créer des options d'exportation et les initialiser.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Enregistrer toutes les modifications.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Voir également

* class [RectangleShape](../rectangleshape/)
* espace de noms [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* Assemblée [Aspose.PSD](../../)



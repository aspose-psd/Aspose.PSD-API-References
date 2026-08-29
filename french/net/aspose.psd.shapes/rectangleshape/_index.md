---
title: "Classe RectangleShape"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Shapes.RectangleShape. Représente une forme rectangulaire"
type: docs
weight: 6030
url: /fr/net/aspose.psd.shapes/rectangleshape/
---
{{< psd/tize >}}
## RectangleShape class

Représente une forme rectangulaire.

```csharp
public class RectangleShape : RectangleProjectedShape
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | Initialise une nouvelle instance de la classe `RectangleShape`. |
| [RectangleShape](rectangleshape/#constructor_1)(RectangleF) | Initialise une nouvelle instance de la classe `RectangleShape`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Obtient les limites de l'objet. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Obtient le centre de la forme. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Obtient une valeur indiquant si la forme possède des segments. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Obtient le point inférieur gauche du rectangle. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Obtient le point supérieur gauche du rectangle. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Obtient la hauteur du rectangle. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Obtient la largeur du rectangle. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Obtient le point inférieur droit du rectangle. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Obtient le point supérieur droit du rectangle. |
| override [Segments](../../aspose.psd.shapes/rectangleshape/segments/) { get; } | Obtient les segments de la forme. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Obtient les limites de l'objet. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |

## Exemples

Cet exemple crée une nouvelle Image et dessine une variété de formes en utilisant Figures et GraphicsPath sur la surface de l'Image

```csharp
[C#]

//Créez une instance d'Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez et initialisez une instance de la classe Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics.
    graphics.Clear(Color.Wheat);

    //Créez une instance de la classe GraphicsPath.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Créez une instance de la classe Figure.
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Ajouter une forme à l'objet Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Créez une instance de la classe Figure.
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Ajouter une forme à l'objet Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Ajoutez l'objet Figure à GraphicsPath.
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Dessinez le chemin avec l'objet Pen de couleur Noir.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Créez des options d'exportation et initialisez-les.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Enregistrez toutes les modifications.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Voir aussi

* class [RectangleProjectedShape](../rectangleprojectedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



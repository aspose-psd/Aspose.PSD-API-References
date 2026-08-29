---
title: "Classe PolygonShape"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Shapes.PolygonShape. Représente une forme polygonale"
type: docs
weight: 6010
url: /fr/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

Représente une forme de polygone.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Initialise une nouvelle instance de la classe `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Initialise une nouvelle instance de la classe `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Initialise une nouvelle instance de la classe `PolygonShape`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Obtient les limites de l'objet. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Obtient le centre de la forme. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Obtient le point final de la forme. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Obtient une valeur indiquant si la forme possède des segments. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Obtient ou définit une valeur indiquant si la forme est fermée. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Obtient ou définit les points de la courbe. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Obtient les segments de la forme. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Obtient le point de départ de la forme. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Inverse l'ordre des points pour cette forme. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



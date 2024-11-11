---
title: Class PolygonShape
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Shapes.PolygonShape class. Represents a polygon shape
type: docs
weight: 5890
url: /net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

Represents a polygon shape.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Constructors

| Name | Description |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Initializes a new instance of the `PolygonShape` class. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Initializes a new instance of the `PolygonShape` class. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Initializes a new instance of the `PolygonShape` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Gets the object's bounds. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Gets the shape's center. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Gets the ending shape point. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Gets a value indicating whether shape has segments. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Gets or sets a value indicating whether shape is closed. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Gets or sets the curve points. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Gets the shape segments. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Gets the starting shape point. |

## Methods

| Name | Description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Gets the object's bounds. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Reverses the order of points for this shape. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Applies the specified transformation to the shape. |

## Examples

This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath on the Image surface

```csharp
[C#]

//Create an instance of Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Create and initialize an instance of Graphics class
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Clear Graphics surface
    graphics.Clear(Color.Wheat);

    //Create an instance of GraphicsPath class
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Create an instance of Figure class
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Add Shape to Figure object
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Create an instance of Figure class
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Add Shape to Figure object
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Add Figure object to GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Draw path with Pen object of color Black
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Create export options and initialize them.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // save all changes.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### See Also

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



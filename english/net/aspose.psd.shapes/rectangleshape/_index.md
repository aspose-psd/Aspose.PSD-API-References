---
title: Class RectangleShape
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Shapes.RectangleShape class. Represents a rectangular shape
type: docs
weight: 5900
url: /net/aspose.psd.shapes/rectangleshape/
---
{{< psd/tize >}}
## RectangleShape class

Represents a rectangular shape.

```csharp
public class RectangleShape : RectangleProjectedShape
```

## Constructors

| Name | Description |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | Initializes a new instance of the `RectangleShape` class. |
| [RectangleShape](rectangleshape/#constructor_1)(RectangleF) | Initializes a new instance of the `RectangleShape` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Gets the object's bounds. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Gets the shape's center. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Gets a value indicating whether shape has segments. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Gets the left bottom rectangle point. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Gets the left top rectangle point. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Gets the rectangle height. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Gets the rectangle width. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Gets the right bottom rectangle point. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Gets the right top rectangle point. |
| override [Segments](../../aspose.psd.shapes/rectangleshape/segments/) { get; } | Gets the shape segments. |

## Methods

| Name | Description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Gets the object's bounds. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Applies the specified transformation to the shape. |

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

* class [RectangleProjectedShape](../rectangleprojectedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



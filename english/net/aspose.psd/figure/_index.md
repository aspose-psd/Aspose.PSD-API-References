---
title: Class Figure
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Figure class. The figure. A container for shapes
type: docs
weight: 1200
url: /net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

The figure. A container for shapes.

```csharp
public class Figure : ObjectWithBounds
```

## Constructors

| Name | Description |
| --- | --- |
| [Figure](figure/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Gets or sets the object's bounds. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Gets or sets a value indicating whether this figure is closed. A closed figure will make a difference only in case where the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be connected by a straight line from the last point of the last shape. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Gets the whole figure segments. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Gets the figure shapes. |

## Methods

| Name | Description |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Adds a shape to the figure. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Adds a range of shapes to the figure. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Gets the object's bounds. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Removes a shape from the figure. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Removes a range of shapes from the figure. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Reverses this figure shapes order and shapes point order. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Applies the specified transformation to the shape. |

## Examples

This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface. Example creates a new Image and draws paths with the help of GraphicsPath class. At the end DrawPath method exposed by Graphics class is called to render the paths on surface. Finally image is exported to Tiff file format.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Add Shapes to Figure object
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Add Figure object to GraphicsPath
    graphicspath.AddFigure(figure);

    //Draw path with Pen object of color Black
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Create an instance of TiffOptions and set its various properties
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // save all changes.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### See Also

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



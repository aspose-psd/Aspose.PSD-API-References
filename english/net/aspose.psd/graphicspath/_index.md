---
title: Class GraphicsPath
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.GraphicsPath class. Represents a series of connected lines and curves. This class cannot be inherited
type: docs
weight: 4620
url: /net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Represents a series of connected lines and curves. This class cannot be inherited.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Initializes a new instance of the `GraphicsPath` class. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Initializes a new instance of the `GraphicsPath` class. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Initializes a new instance of the `GraphicsPath` class. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Initializes a new instance of the `GraphicsPath` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Gets or sets the object's bounds. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Gets the path figures. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Gets or sets a [`FillMode`](../fillmode/) enumeration that determines how the interiors of shapes in this `GraphicsPath` are filled. |

## Methods

| Name | Description |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Adds a new figure. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Adds new figures. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Appends the specified `GraphicsPath` to this path. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Appends the specified `GraphicsPath` to this path. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Performs a deep clone of this graphics path. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Converts each curve in this path into a sequence of connected line segments. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Applies the specified transform and then converts each curve in this `GraphicsPath` into a sequence of connected line segments. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Converts each curve in this `GraphicsPath` into a sequence of connected line segments. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Gets the object's bounds. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/) and using the specified [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/) and using the specified [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/) and using the specified [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this `GraphicsPath` when drawn with the specified [`Pen`](../pen/) and using the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Indicates whether the specified point is contained within this `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Indicates whether the specified point is contained within this `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Indicates whether the specified point is contained within this `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Indicates whether the specified point is contained within this `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Indicates whether the specified point is contained within this `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Indicates whether the specified point is contained within this `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Indicates whether the specified point is contained within this `GraphicsPath` in the visible clip region of the specified [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Indicates whether the specified point is contained within this `GraphicsPath`, using the specified [`Graphics`](../graphics/). |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Removes a figure. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Removes figures. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Empties the graphics path and sets the [`FillMode`](../fillmode/) to Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Reverses the order of figures, shapes, and points in each shape of this `GraphicsPath`. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Applies the specified transformation to the shape. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Applies a warp transform, defined by a rectangle and a parallelogram, to this `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Adds an additional outline to the path. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Adds an additional outline to the `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Replaces this `GraphicsPath` with curves that enclose the area that is filled when this path is drawn by the specified pen. |

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



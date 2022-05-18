---
title: GraphicsPath
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 4170
url: /net/aspose.psd/graphicspath/
---
## GraphicsPath class

Represents a series of connected lines and curves. This class cannot be inherited.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructors

| Name | Description |
| --- | --- |
| [GraphicsPath](graphicspath)() | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath)(Figure[]) | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath)(FillMode) | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |
| [GraphicsPath](graphicspath)(Figure[], FillMode) | Initializes a new instance of the [`GraphicsPath`](../graphicspath) class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds) { get; } | Gets or sets the object's bounds. |
| [Figures](../../aspose.psd/graphicspath/figures) { get; } | Gets the path figures. |
| [FillMode](../../aspose.psd/graphicspath/fillmode) { get; set; } | Gets or sets a [`FillMode`](../fillmode) enumeration that determines how the interiors of shapes in this [`GraphicsPath`](../graphicspath) are filled. |

## Methods

| Name | Description |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure)(Figure) | Adds a new figure. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures)(Figure[]) | Adds new figures. |
| [AddPath](../../aspose.psd/graphicspath/addpath)(GraphicsPath) | Appends the specified [`GraphicsPath`](../graphicspath) to this path. |
| [AddPath](../../aspose.psd/graphicspath/addpath)(GraphicsPath, bool) | Appends the specified [`GraphicsPath`](../graphicspath) to this path. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone)() | Performs a deep clone of this graphics path. |
| [Flatten](../../aspose.psd/graphicspath/flatten)() | Converts each curve in this path into a sequence of connected line segments. |
| [Flatten](../../aspose.psd/graphicspath/flatten)(Matrix) | Applies the specified transform and then converts each curve in this [`GraphicsPath`](../graphicspath) into a sequence of connected line segments. |
| [Flatten](../../aspose.psd/graphicspath/flatten)(Matrix, float) | Converts each curve in this [`GraphicsPath`](../graphicspath) into a sequence of connected line segments. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds)(Matrix, Pen) | Gets the object's bounds. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(Point, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(PointF, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(float, float, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(int, int, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(Point, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(PointF, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(float, float, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible)(int, int, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(Point) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(PointF) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(float, float) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(int, int) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(Point, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(PointF, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(float, float, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath) in the visible clip region of the specified [`Graphics`](../graphics). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible)(int, int, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath), using the specified [`Graphics`](../graphics). |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure)(Figure) | Removes a figure. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures)(Figure[]) | Removes figures. |
| [Reset](../../aspose.psd/graphicspath/reset)() | Empties the graphics path and sets the [`FillMode`](../fillmode) to Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse)() | Reverses the order of figures, shapes, and points in each shape of this [`GraphicsPath`](../graphicspath). |
| override [Transform](../../aspose.psd/graphicspath/transform)(Matrix) | Applies the specified transformation to the shape. |
| [Warp](../../aspose.psd/graphicspath/warp)(PointF[], RectangleF) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](../../aspose.psd/graphicspath/warp)(PointF[], RectangleF, Matrix) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](../../aspose.psd/graphicspath/warp)(PointF[], RectangleF, Matrix, WarpMode) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](../../aspose.psd/graphicspath/warp)(PointF[], RectangleF, Matrix, WarpMode, float) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Widen](../../aspose.psd/graphicspath/widen)(Pen) | Adds an additional outline to the path. |
| [Widen](../../aspose.psd/graphicspath/widen)(Pen, Matrix) | Adds an additional outline to the [`GraphicsPath`](../graphicspath). |
| [Widen](../../aspose.psd/graphicspath/widen)(Pen, Matrix, float) | Replaces this [`GraphicsPath`](../graphicspath) with curves that enclose the area that is filled when this path is drawn by the specified pen. |

### Examples

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

* class [ObjectWithBounds](../objectwithbounds)
* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

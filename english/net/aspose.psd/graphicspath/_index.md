---
title: GraphicsPath
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 4120
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
| override [Bounds](bounds) { get; } | Gets or sets the object's bounds. |
| [Figures](figures) { get; } | Gets the path figures. |
| [FillMode](fillmode) { get; set; } | Gets or sets a [`FillMode`](../fillmode) enumeration that determines how the interiors of shapes in this [`GraphicsPath`](../graphicspath) are filled. |

## Methods

| Name | Description |
| --- | --- |
| [AddFigure](addfigure)(Figure) | Adds a new figure. |
| [AddFigures](addfigures)(Figure[]) | Adds new figures. |
| [AddPath](addpath)(GraphicsPath) | Appends the specified [`GraphicsPath`](../graphicspath) to this path. |
| [AddPath](addpath)(GraphicsPath, bool) | Appends the specified [`GraphicsPath`](../graphicspath) to this path. |
| [DeepClone](deepclone)() | Performs a deep clone of this graphics path. |
| [Flatten](flatten)() | Converts each curve in this path into a sequence of connected line segments. |
| [Flatten](flatten)(Matrix) | Applies the specified transform and then converts each curve in this [`GraphicsPath`](../graphicspath) into a sequence of connected line segments. |
| [Flatten](flatten)(Matrix, float) | Converts each curve in this [`GraphicsPath`](../graphicspath) into a sequence of connected line segments. |
| override [GetBounds](getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](getbounds)(Matrix, Pen) | Gets the object's bounds. |
| [IsOutlineVisible](isoutlinevisible)(Point, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](isoutlinevisible)(PointF, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](isoutlinevisible)(float, float, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](isoutlinevisible)(int, int, Pen) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen). |
| [IsOutlineVisible](isoutlinevisible)(Point, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](isoutlinevisible)(PointF, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](isoutlinevisible)(float, float, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsOutlineVisible](isoutlinevisible)(int, int, Pen, Graphics) | Indicates whether the specified point is contained within (under) the outline of this [`GraphicsPath`](../graphicspath) when drawn with the specified [`Pen`](../pen) and using the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(Point) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](isvisible)(PointF) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](isvisible)(float, float) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](isvisible)(int, int) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](isvisible)(Point, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](isvisible)(PointF, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath). |
| [IsVisible](isvisible)(float, float, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath) in the visible clip region of the specified [`Graphics`](../graphics). |
| [IsVisible](isvisible)(int, int, Graphics) | Indicates whether the specified point is contained within this [`GraphicsPath`](../graphicspath), using the specified [`Graphics`](../graphics). |
| [RemoveFigure](removefigure)(Figure) | Removes a figure. |
| [RemoveFigures](removefigures)(Figure[]) | Removes figures. |
| [Reset](reset)() | Empties the graphics path and sets the [`FillMode`](../fillmode) to Alternate. |
| [Reverse](reverse)() | Reverses the order of figures, shapes, and points in each shape of this [`GraphicsPath`](../graphicspath). |
| override [Transform](transform)(Matrix) | Applies the specified transformation to the shape. |
| [Warp](warp)(PointF[], RectangleF) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](warp)(PointF[], RectangleF, Matrix) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](warp)(PointF[], RectangleF, Matrix, WarpMode) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Warp](warp)(PointF[], RectangleF, Matrix, WarpMode, float) | Applies a warp transform, defined by a rectangle and a parallelogram, to this [`GraphicsPath`](../graphicspath). |
| [Widen](widen)(Pen) | Adds an additional outline to the path. |
| [Widen](widen)(Pen, Matrix) | Adds an additional outline to the [`GraphicsPath`](../graphicspath). |
| [Widen](widen)(Pen, Matrix, float) | Replaces this [`GraphicsPath`](../graphicspath) with curves that enclose the area that is filled when this path is drawn by the specified pen. |

### See Also

* class [ObjectWithBounds](../objectwithbounds)
* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

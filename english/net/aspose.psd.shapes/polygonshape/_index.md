---
title: PolygonShape
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5310
url: /net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

Represents a polygon shape.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Constructors

| Name | Description |
| --- | --- |
| [PolygonShape](polygonshape)() | Initializes a new instance of the [`PolygonShape`](../polygonshape) class. |
| [PolygonShape](polygonshape)(PointF[]) | Initializes a new instance of the [`PolygonShape`](../polygonshape) class. |
| [PolygonShape](polygonshape)(PointF[], bool) | Initializes a new instance of the [`PolygonShape`](../polygonshape) class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](bounds) { get; } | Gets the object's bounds. |
| override [Center](center) { get; } | Gets the shape's center. |
| virtual [EndPoint](endpoint) { get; } | Gets the ending shape point. |
| override [HasSegments](hassegments) { get; } | Gets a value indicating whether shape has segments. |
| [IsClosed](isclosed) { get; set; } | Gets or sets a value indicating whether shape is closed. |
| [Points](points) { get; set; } | Gets or sets the curve points. |
| override [Segments](segments) { get; } | Gets the shape segments. |
| virtual [StartPoint](startpoint) { get; } | Gets the starting shape point. |

## Methods

| Name | Description |
| --- | --- |
| override [GetBounds](getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](getbounds)(Matrix, Pen) | Gets the object's bounds. |
| [Reverse](reverse)() | Reverses the order of points for this shape. |
| override [Transform](transform)(Matrix) | Applies the specified transformation to the shape. |

### See Also

* class [Shape](../../aspose.psd/shape)
* interface [IOrderedShape](../../aspose.psd/iorderedshape)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
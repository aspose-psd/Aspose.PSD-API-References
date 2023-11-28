---
title: Class CurveShape
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Shapes.CurveShape class. Represents a curved spline shape
type: docs
weight: 5720
url: /net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

Represents a curved spline shape.

```csharp
public sealed class CurveShape : PolygonShape
```

## Constructors

| Name | Description |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | Initializes a new instance of the `CurveShape` class. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | Initializes a new instance of the `CurveShape` class. The default tension of 0.5 is used. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | Initializes a new instance of the `CurveShape` class. The default tension of 0.5 is used. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | Initializes a new instance of the `CurveShape` class. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | Initializes a new instance of the `CurveShape` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | Gets the object's bounds. |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | Gets the shape's center. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Gets the ending shape point. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Gets a value indicating whether shape has segments. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Gets or sets a value indicating whether shape is closed. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Gets or sets the curve points. |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | Gets the shape segments. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Gets the starting shape point. |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | Gets or sets the curve tension. |

## Methods

| Name | Description |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | Gets the object's bounds. |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | Gets the object's bounds. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Reverses the order of points for this shape. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Applies the specified transformation to the shape. |

### See Also

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



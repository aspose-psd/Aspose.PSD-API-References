---
title: Struct RectangleF
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.RectangleF struct. Stores a set of four floatingpoint numbers that represent the location and size of a rectangle
type: docs
weight: 5550
url: /net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Stores a set of four floating-point numbers that represent the location and size of a rectangle.

```csharp
public struct RectangleF
```

## Constructors

| Name | Description |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initializes a new instance of the `RectangleF` structure with the specified location and size. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initializes a new instance of the `RectangleF` structure with the specified location and size. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Gets a new instance of the `RectangleF` structure that has [`X`](./x/), [`Y`](./y/), [`Width`](./width/) and [`Height`](./height/) values set to zero. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Gets or sets the y-coordinate that is the sum of [`Y`](./y/) and [`Height`](./height/) of this `RectangleF` structure. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Gets or sets the height of this `RectangleF` structure. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Gets a value indicating whether the [`Width`](./width/) or [`Height`](./height/) property of this `RectangleF` has a value of zero. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Gets or sets the x-coordinate of the left edge of this `RectangleF` structure. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Gets or sets the coordinates of the upper-left corner of this `RectangleF` structure. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x/) and [`Width`](./width/) of this `RectangleF` structure. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Gets or sets the size of this `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Gets or sets the y-coordinate of the top edge of this `RectangleF` structure. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Gets or sets the width of this `RectangleF` structure. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this `RectangleF` structure. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this `RectangleF` structure. |

## Methods

| Name | Description |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Creates a `RectangleF` structure with upper-left corner and lower-right corner at the specified locations. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Creates a new [`Rectangle`](../rectangle/) from two points specified. Two verticles of the created [`Rectangle`](../rectangle/) will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Creates and returns an inflated copy of the specified `RectangleF` structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Returns a `RectangleF` structure that represents the intersection of two rectangles. If there is no intersection, and empty `RectangleF` is returned. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Determines if the specified point is contained within this `RectangleF` structure. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Determines if the rectangular region represented by *rect* is entirely contained within this `RectangleF` structure. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Determines if the specified point is contained within this `RectangleF` structure. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Tests whether *obj* is a `RectangleF` with the same location and size of this `RectangleF`. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Gets the hash code for this `RectangleF` structure. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Inflates this `RectangleF` by the specified amount. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Inflates this `RectangleF` structure by the specified amount. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Replaces this `RectangleF` structure with the intersection of itself and the specified `RectangleF` structure. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Determines if this rectangle intersects with *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Adjusts the location of this rectangle by the specified amount. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Adjusts the location of this rectangle by the specified amount. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Converts the attributes of this `RectangleF` to a human-readable string. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implements the operator /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Tests whether two `RectangleF` structures have equal location and size. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Converts the specified [`Rectangle`](../rectangle/) structure to a `RectangleF` structure. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Tests whether two `RectangleF` structures differ in location or size. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implements the operator *. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: RectangleF
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5200
url: /net/aspose.psd/rectanglef/
---
## RectangleF structure

Stores a set of four floating-point numbers that represent the location and size of a rectangle.

```csharp
public struct RectangleF
```

## Constructors

| Name | Description |
| --- | --- |
| [RectangleF](rectanglef)(PointF, SizeF) | Initializes a new instance of the [`RectangleF`](../rectanglef) structure with the specified location and size. |
| [RectangleF](rectanglef)(float, float, float, float) | Initializes a new instance of the [`RectangleF`](../rectanglef) structure with the specified location and size. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty) { get; } | Gets a new instance of the [`RectangleF`](../rectanglef) structure that has [`X`](./x), [`Y`](./y), [`Width`](./width) and [`Height`](./height) values set to zero. |
| [Bottom](../../aspose.psd/rectanglef/bottom) { get; set; } | Gets or sets the y-coordinate that is the sum of [`Y`](./y) and [`Height`](./height) of this [`RectangleF`](../rectanglef) structure. |
| [Height](../../aspose.psd/rectanglef/height) { get; set; } | Gets or sets the height of this [`RectangleF`](../rectanglef) structure. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty) { get; } | Gets a value indicating whether the [`Width`](./width) or [`Height`](./height) property of this [`RectangleF`](../rectanglef) has a value of zero. |
| [Left](../../aspose.psd/rectanglef/left) { get; set; } | Gets or sets the x-coordinate of the left edge of this [`RectangleF`](../rectanglef) structure. |
| [Location](../../aspose.psd/rectanglef/location) { get; set; } | Gets or sets the coordinates of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |
| [Right](../../aspose.psd/rectanglef/right) { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x) and [`Width`](./width) of this [`RectangleF`](../rectanglef) structure. |
| [Size](../../aspose.psd/rectanglef/size) { get; set; } | Gets or sets the size of this [`RectangleF`](../rectanglef). |
| [Top](../../aspose.psd/rectanglef/top) { get; set; } | Gets or sets the y-coordinate of the top edge of this [`RectangleF`](../rectanglef) structure. |
| [Width](../../aspose.psd/rectanglef/width) { get; set; } | Gets or sets the width of this [`RectangleF`](../rectanglef) structure. |
| [X](../../aspose.psd/rectanglef/x) { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |
| [Y](../../aspose.psd/rectanglef/y) { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this [`RectangleF`](../rectanglef) structure. |

## Methods

| Name | Description |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Creates a [`RectangleF`](../rectanglef) structure with upper-left corner and lower-right corner at the specified locations. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints)(PointF, PointF) | Creates a new [`Rectangle`](../rectangle) from two points specified. Two verticles of the created [`Rectangle`](../rectangle) will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| static [Inflate](../../aspose.psd/rectanglef/inflate)(RectangleF, float, float) | Creates and returns an inflated copy of the specified [`RectangleF`](../rectanglef) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| static [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF, RectangleF) | Returns a [`RectangleF`](../rectanglef) structure that represents the intersection of two rectangles. If there is no intersection, and empty [`RectangleF`](../rectanglef) is returned. |
| static [Union](../../aspose.psd/rectanglef/union)(RectangleF, RectangleF) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |
| [Contains](../../aspose.psd/rectanglef/contains)(PointF) | Determines if the specified point is contained within this [`RectangleF`](../rectanglef) structure. |
| [Contains](../../aspose.psd/rectanglef/contains)(RectangleF) | Determines if the rectangular region represented by *rect* is entirely contained within this [`RectangleF`](../rectanglef) structure. |
| [Contains](../../aspose.psd/rectanglef/contains)(float, float) | Determines if the specified point is contained within this [`RectangleF`](../rectanglef) structure. |
| override [Equals](../../aspose.psd/rectanglef/equals)(object) | Tests whether *obj* is a [`RectangleF`](../rectanglef) with the same location and size of this [`RectangleF`](../rectanglef). |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode)() | Gets the hash code for this [`RectangleF`](../rectanglef) structure. |
| [Inflate](../../aspose.psd/rectanglef/inflate)(SizeF) | Inflates this [`RectangleF`](../rectanglef) by the specified amount. |
| [Inflate](../../aspose.psd/rectanglef/inflate)(float, float) | Inflates this [`RectangleF`](../rectanglef) structure by the specified amount. |
| [Intersect](../../aspose.psd/rectanglef/intersect)(RectangleF) | Replaces this [`RectangleF`](../rectanglef) structure with the intersection of itself and the specified [`RectangleF`](../rectanglef) structure. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith)(RectangleF) | Determines if this rectangle intersects with *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize)() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [Offset](../../aspose.psd/rectanglef/offset)(PointF) | Adjusts the location of this rectangle by the specified amount. |
| [Offset](../../aspose.psd/rectanglef/offset)(float, float) | Adjusts the location of this rectangle by the specified amount. |
| override [ToString](../../aspose.psd/rectanglef/tostring)() | Converts the attributes of this [`RectangleF`](../rectanglef) to a human-readable string. |
| [operator /](../../aspose.psd/rectanglef/op_division) | Implements the operator /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality) | Tests whether two [`RectangleF`](../rectanglef) structures have equal location and size. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit) | Converts the specified [`Rectangle`](../rectangle) structure to a [`RectangleF`](../rectanglef) structure. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality) | Tests whether two [`RectangleF`](../rectanglef) structures differ in location or size. |
| [operator *](../../aspose.psd/rectanglef/op_multiply) | Implements the operator *. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

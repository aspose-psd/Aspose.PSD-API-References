---
title: Rectangle
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5190
url: /net/aspose.psd/rectangle/
---
## Rectangle structure

Stores a set of four integers that represent the location and size of a rectangle.

```csharp
public struct Rectangle
```

## Constructors

| Name | Description |
| --- | --- |
| [Rectangle](rectangle)(Point, Size) | Initializes a new instance of the [`Rectangle`](../rectangle) structure with the specified location and size. |
| [Rectangle](rectangle)(int, int, int, int) | Initializes a new instance of the [`Rectangle`](../rectangle) structure with the specified location and size. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty) { get; } | Gets a new instance of the [`Rectangle`](../rectangle) structure that has [`X`](./x), [`Y`](./y), [`Width`](./width) and [`Height`](./height) values set to zero. |
| [Bottom](../../aspose.psd/rectangle/bottom) { get; set; } | Gets or sets the y-coordinate that is the sum of the [`Y`](./y) and [`Height`](./height) property values of this [`Rectangle`](../rectangle) structure. |
| [Height](../../aspose.psd/rectangle/height) { get; set; } | Gets or sets the height of this [`Rectangle`](../rectangle) structure. |
| [IsEmpty](../../aspose.psd/rectangle/isempty) { get; } | Gets a value indicating whether all numeric properties of this [`Rectangle`](../rectangle) have values of zero. |
| [Left](../../aspose.psd/rectangle/left) { get; set; } | Gets or sets the x-coordinate of the left edge of this [`Rectangle`](../rectangle) structure. |
| [Location](../../aspose.psd/rectangle/location) { get; set; } | Gets or sets the coordinates of the upper-left corner of this [`Rectangle`](../rectangle) structure. |
| [Right](../../aspose.psd/rectangle/right) { get; set; } | Gets or sets the x-coordinate that is the sum of [`X`](./x) and [`Width`](./width) property values of this [`Rectangle`](../rectangle) structure. |
| [Size](../../aspose.psd/rectangle/size) { get; set; } | Gets or sets the size of this [`Rectangle`](../rectangle). |
| [Top](../../aspose.psd/rectangle/top) { get; set; } | Gets or sets the y-coordinate of the top edge of this [`Rectangle`](../rectangle) structure. |
| [Width](../../aspose.psd/rectangle/width) { get; set; } | Gets or sets the width of this [`Rectangle`](../rectangle) structure. |
| [X](../../aspose.psd/rectangle/x) { get; set; } | Gets or sets the x-coordinate of the upper-left corner of this [`Rectangle`](../rectangle) structure. |
| [Y](../../aspose.psd/rectangle/y) { get; set; } | Gets or sets the y-coordinate of the upper-left corner of this [`Rectangle`](../rectangle) structure. |

## Methods

| Name | Description |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling)(RectangleF) | Converts the specified [`RectangleF`](../rectanglef) structure to a [`Rectangle`](../rectangle) structure by rounding the [`RectangleF`](../rectanglef) values to the next higher integer values. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom)(int, int, int, int) | Creates a [`Rectangle`](../rectangle) structure with the specified edge locations. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints)(Point, Point) | Creates a new [`Rectangle`](../rectangle) from two points specified. Two verticales of the created [`Rectangle`](../rectangle) will be equal to the passed *point1* and *point2*. These would be typically the opposite vertices. |
| static [Inflate](../../aspose.psd/rectangle/inflate)(Rectangle, int, int) | Creates and returns an inflated copy of the specified [`Rectangle`](../rectangle) structure. The copy is inflated by the specified amount. The original [`Rectangle`](../rectangle) structure remains unmodified. |
| static [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle, Rectangle) | Returns a third [`Rectangle`](../rectangle) structure that represents the intersection of two other [`Rectangle`](../rectangle) structures. If there is no intersection, an empty [`Rectangle`](../rectangle) is returned. |
| static [Round](../../aspose.psd/rectangle/round)(RectangleF) | Converts the specified [`RectangleF`](../rectanglef) to a [`Rectangle`](../rectangle) by rounding the [`RectangleF`](../rectanglef) values to the nearest integer values. |
| static [Truncate](../../aspose.psd/rectangle/truncate)(RectangleF) | Converts the specified [`RectangleF`](../rectanglef) to a [`Rectangle`](../rectangle) by truncating the [`RectangleF`](../rectanglef) values. |
| static [Union](../../aspose.psd/rectangle/union)(Rectangle, Rectangle) | Gets a [`Rectangle`](../rectangle) structure that contains the union of two [`Rectangle`](../rectangle) structures. |
| [Contains](../../aspose.psd/rectangle/contains)(Point) | Determines if the specified point is contained within this [`Rectangle`](../rectangle) structure. |
| [Contains](../../aspose.psd/rectangle/contains)(Rectangle) | Determines if the rectangular region represented by *rect* is entirely contained within this [`Rectangle`](../rectangle) structure. |
| [Contains](../../aspose.psd/rectangle/contains)(int, int) | Determines if the specified point is contained within this [`Rectangle`](../rectangle) structure. |
| override [Equals](../../aspose.psd/rectangle/equals)(object) | Tests whether *obj* is a [`Rectangle`](../rectangle) structure with the same location and size of this [`Rectangle`](../rectangle) structure. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode)() | Returns the hash code for this [`Rectangle`](../rectangle) structure. |
| [Inflate](../../aspose.psd/rectangle/inflate)(Size) | Inflates this [`Rectangle`](../rectangle) by the specified amount. |
| [Inflate](../../aspose.psd/rectangle/inflate)(int, int) | Inflates this [`Rectangle`](../rectangle) by the specified amount. |
| [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle) | Replaces this [`Rectangle`](../rectangle) with the intersection of itself and the specified [`Rectangle`](../rectangle). |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith)(Rectangle) | Determines if this rectangle intersects with *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize)() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [Offset](../../aspose.psd/rectangle/offset)(Point) | Adjusts the location of this rectangle by the specified amount. |
| [Offset](../../aspose.psd/rectangle/offset)(int, int) | Adjusts the location of this rectangle by the specified amount. |
| override [ToString](../../aspose.psd/rectangle/tostring)() | Converts the attributes of this [`Rectangle`](../rectangle) to a human-readable string. |
| [operator ==](../../aspose.psd/rectangle/op_equality) | Tests whether two [`Rectangle`](../rectangle) structures have equal location and size. |
| [operator !=](../../aspose.psd/rectangle/op_inequality) | Tests whether two [`Rectangle`](../rectangle) structures differ in location or size. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

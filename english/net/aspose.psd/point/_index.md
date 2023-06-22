---
title: Struct Point
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Point struct. Represents an ordered pair of integer x and ycoordinates that defines a point in a twodimensional plane
type: docs
weight: 5450
url: /net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

```csharp
public struct Point
```

## Constructors

| Name | Description |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initializes a new instance of the `Point` structure using coordinates specified by an integer value. |
| [Point](point/#constructor)(Size) | Initializes a new instance of the `Point` structure from the [`Size`](../size/) structure. |
| [Point](point/#constructor_2)(int, int) | Initializes a new instance of the `Point` structure with the specified coordinates. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Gets a new instance of the `Point` structure that has [`X`](./x/) and [`Y`](./y/) values set to zero. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Gets a value indicating whether this `Point` is empty. |
| [X](../../aspose.psd/point/x/) { get; set; } | Gets or sets the x-coordinate of this `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Gets or sets the y-coordinate of this `Point`. |

## Methods

| Name | Description |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Adds the specified [`Size`](../size/) to the specified `Point`. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` by rounding the values of the [`PointF`](../pointf/) to the next higher integer values. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` object by rounding the `Point` values to the nearest integer. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Returns the result of subtracting specified [`Size`](../size/) from the specified `Point`. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Converts the specified [`PointF`](../pointf/) to a `Point` by truncating the values of the `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Specifies whether this `Point` contains the same coordinates as the specified Object. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Returns a hash code for this `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Translates this `Point` by the specified `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Translates this `Point` by the specified amount. |
| override [ToString](../../aspose.psd/point/tostring/)() | Converts this `Point` to a human-readable string. |
| [operator +](../../aspose.psd/point/op_addition/) | Translates a `Point` by a given [`Size`](../size/). |
| [operator ==](../../aspose.psd/point/op_equality/) | Compares two `Point` objects. The result specifies whether the values of the [`X`](./x/) and [`Y`](./y/) properties of the two `Point` objects are equal. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Converts the specified `Point` structure to a [`Size`](../size/) structure. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Converts the specified `Point` structure to the [`PointF`](../pointf/) structure. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Compares two `Point` objects. The result specifies whether the values of the [`X`](./x/) or [`Y`](./y/) properties of the two `Point` objects are unequal. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Translates a `Point` by the negative of a given [`Size`](../size/). |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



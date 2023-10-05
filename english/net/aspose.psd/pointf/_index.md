---
title: Struct PointF
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.PointF struct. Represents an ordered pair of floatingpoint x and ycoordinates that defines a point in a twodimensional plane
type: docs
weight: 5470
url: /net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

```csharp
public struct PointF
```

## Constructors

| Name | Description |
| --- | --- |
| [PointF](pointf/)(float, float) | Initializes a new instance of the `PointF` structure with the specified coordinates. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | Gets a new instance of the `PointF` structure that has [`X`](./x/) and [`Y`](./y/) values set to zero. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | Gets a value indicating whether this `PointF` is empty. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | Gets or sets the x-coordinate of this `PointF`. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | Gets or sets the y-coordinate of this `PointF`. |

## Methods

| Name | Description |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | Translates a given `PointF` by the specified [`Size`](../size/). |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | Translates a given `PointF` by a specified [`SizeF`](../sizef/). |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | Translates a `PointF` by the negative of a specified size. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | Translates a `PointF` by the negative of a specified size. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | Specifies whether this `PointF` contains the same coordinates as the specified Object. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | Returns a hash code for this `PointF` structure. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | Converts this `PointF` to a human readable string. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | Translates a `PointF` by a given [`Size`](../size/). (2 operators) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | Compares two `PointF` structures. The result specifies whether the values of the [`X`](./x/) and [`Y`](./y/) properties of the two `PointF` structures are equal. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | Determines whether the coordinates of the specified points are not equal. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | Translates a `PointF` by the negative of a given [`Size`](../size/). (2 operators) |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



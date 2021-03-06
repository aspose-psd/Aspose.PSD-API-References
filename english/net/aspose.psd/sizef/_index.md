---
title: SizeF
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5410
url: /net/aspose.psd/sizef/
---
## SizeF structure

Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

```csharp
public struct SizeF
```

## Constructors

| Name | Description |
| --- | --- |
| [SizeF](sizef)(PointF) | Initializes a new instance of the [`SizeF`](../sizef) structure from the specified [`PointF`](../pointf). |
| [SizeF](sizef)(SizeF) | Initializes a new instance of the [`SizeF`](../sizef) structure from the specified [`SizeF`](../sizef). |
| [SizeF](sizef)(float, float) | Initializes a new instance of the [`SizeF`](../sizef) structure from the specified dimensions. |

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty) { get; } | Gets a new instance of the [`SizeF`](../sizef) structure that has [`Width`](./width) and [`Height`](./height) values set to zero. |
| [Height](../../aspose.psd/sizef/height) { get; set; } | Gets or sets the vertical component of this [`SizeF`](../sizef). |
| [IsEmpty](../../aspose.psd/sizef/isempty) { get; } | Gets a value indicating whether this [`SizeF`](../sizef) has zero width and height. |
| [Width](../../aspose.psd/sizef/width) { get; set; } | Gets or sets the horizontal component of this [`SizeF`](../sizef). |

## Methods

| Name | Description |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add)(SizeF, SizeF) | Adds the width and height of one [`SizeF`](../sizef) structure to the width and height of another [`SizeF`](../sizef) structure. |
| static [Subtract](../../aspose.psd/sizef/subtract)(SizeF, SizeF) | Subtracts the width and height of one [`SizeF`](../sizef) structure from the width and height of another [`SizeF`](../sizef) structure. |
| override [Equals](../../aspose.psd/sizef/equals)(object) | Tests to see whether the specified object is a [`SizeF`](../sizef) with the same dimensions as this [`SizeF`](../sizef). |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode)() | Returns a hash code for this [`Size`](../size) structure. |
| [ToPointF](../../aspose.psd/sizef/topointf)() | Converts a [`SizeF`](../sizef) to a [`PointF`](../pointf). |
| [ToSize](../../aspose.psd/sizef/tosize)() | Converts a [`SizeF`](../sizef) to a [`Size`](../size) structure with truncated size values. |
| override [ToString](../../aspose.psd/sizef/tostring)() | Creates a human-readable string that represents this [`SizeF`](../sizef). |
| [operator +](../../aspose.psd/sizef/op_addition) | Adds the width and height of one [`SizeF`](../sizef) structure to the width and height of another [`SizeF`](../sizef) structure. |
| [operator ==](../../aspose.psd/sizef/op_equality) | Tests whether two [`SizeF`](../sizef) structures are equal. |
| [explicit operator](../../aspose.psd/sizef/op_explicit) | Converts the specified [`SizeF`](../sizef) to a [`PointF`](../pointf). |
| [operator !=](../../aspose.psd/sizef/op_inequality) | Tests whether two [`SizeF`](../sizef) structures are different. |
| [operator -](../../aspose.psd/sizef/op_subtraction) | Subtracts the width and height of one [`SizeF`](../sizef) structure from the width and height of another [`SizeF`](../sizef) structure. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

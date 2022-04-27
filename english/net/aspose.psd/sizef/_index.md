---
title: SizeF
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5360
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
| static [Empty](empty) { get; } | Gets a new instance of the [`SizeF`](../sizef) structure that has [`Width`](./width) and [`Height`](./height) values set to zero. |
| [Height](height) { get; set; } | Gets or sets the vertical component of this [`SizeF`](../sizef). |
| [IsEmpty](isempty) { get; } | Gets a value indicating whether this [`SizeF`](../sizef) has zero width and height. |
| [Width](width) { get; set; } | Gets or sets the horizontal component of this [`SizeF`](../sizef). |

## Methods

| Name | Description |
| --- | --- |
| static [Add](add)(SizeF, SizeF) | Adds the width and height of one [`SizeF`](../sizef) structure to the width and height of another [`SizeF`](../sizef) structure. |
| static [Subtract](subtract)(SizeF, SizeF) | Subtracts the width and height of one [`SizeF`](../sizef) structure from the width and height of another [`SizeF`](../sizef) structure. |
| override [Equals](equals)(object) | Tests to see whether the specified object is a [`SizeF`](../sizef) with the same dimensions as this [`SizeF`](../sizef). |
| override [GetHashCode](gethashcode)() | Returns a hash code for this [`Size`](../size) structure. |
| [ToPointF](topointf)() | Converts a [`SizeF`](../sizef) to a [`PointF`](../pointf). |
| [ToSize](tosize)() | Converts a [`SizeF`](../sizef) to a [`Size`](../size) structure with truncated size values. |
| override [ToString](tostring)() | Creates a human-readable string that represents this [`SizeF`](../sizef). |
| [operator +](op_addition) | Adds the width and height of one [`SizeF`](../sizef) structure to the width and height of another [`SizeF`](../sizef) structure. |
| [operator ==](op_equality) | Tests whether two [`SizeF`](../sizef) structures are equal. |
| [explicit operator](op_explicit) | Converts the specified [`SizeF`](../sizef) to a [`PointF`](../pointf). |
| [operator !=](op_inequality) | Tests whether two [`SizeF`](../sizef) structures are different. |
| [operator -](op_subtraction) | Subtracts the width and height of one [`SizeF`](../sizef) structure from the width and height of another [`SizeF`](../sizef) structure. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
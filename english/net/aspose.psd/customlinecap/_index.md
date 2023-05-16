---
title: Class CustomLineCap
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.CustomLineCap class. Encapsulates a custom userdefined line cap
type: docs
weight: 700
url: /net/aspose.psd/customlinecap/
---
{{< psd/tize >}}
## CustomLineCap class

Encapsulates a custom user-defined line cap.

```csharp
public class CustomLineCap
```

## Constructors

| Name | Description |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | Initializes a new instance of the `CustomLineCap` class with the specified outline and fill. |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | Initializes a new instance of the `CustomLineCap` class from the specified existing [`LineCap`](../linecap/) enumeration with the specified outline and fill. |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | Initializes a new instance of the `CustomLineCap` class from the specified existing [`LineCap`](../linecap/) enumeration with the specified outline, fill, and inset. |

## Properties

| Name | Description |
| --- | --- |
| [BaseCap](../../aspose.psd/customlinecap/basecap/) { get; set; } | Gets or sets the [`LineCap`](../linecap/) enumeration on which this `CustomLineCap` is based. |
| [BaseInset](../../aspose.psd/customlinecap/baseinset/) { get; set; } | Gets or sets the distance between the cap and the line. |
| [FillPath](../../aspose.psd/customlinecap/fillpath/) { get; set; } | Gets or sets the object that defines the fill for the custom cap. |
| [StrokeJoin](../../aspose.psd/customlinecap/strokejoin/) { get; set; } | Gets or sets the [`LineJoin`](../linejoin/) enumeration that determines how lines that compose this `CustomLineCap` object are joined. |
| [StrokePath](../../aspose.psd/customlinecap/strokepath/) { get; set; } | Gets or sets the object that defines the outline of the custom cap. |
| [WidthScale](../../aspose.psd/customlinecap/widthscale/) { get; set; } | Gets or sets the amount by which to scale this `CustomLineCap` Class object with respect to the width of the Pen object. |

## Methods

| Name | Description |
| --- | --- |
| [GetStrokeCaps](../../aspose.psd/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | Gets the caps used to start and end lines that make up this custom cap. |
| [SetStrokeCaps](../../aspose.psd/customlinecap/setstrokecaps/)(LineCap, LineCap) | Sets the caps used to start and end lines that make up this custom cap. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



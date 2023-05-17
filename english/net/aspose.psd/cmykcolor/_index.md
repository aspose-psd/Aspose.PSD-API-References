---
title: Struct CmykColor
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.CmykColor struct. The CMYK color of pixel
type: docs
weight: 270
url: /net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

The CMYK color of pixel.

```csharp
public struct CmykColor
```

## Properties

| Name | Description |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Gets the empty. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Gets the cyan component value of this [`Color`](../color/) structure. |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Gets a value indicating whether this [`Color`](../color/) structure is uninitialized. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Gets the black component value of this [`Color`](../color/) structure. |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Gets the magenta component value of this [`Color`](../color/) structure. |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Gets the yellow component value of this [`Color`](../color/) structure. |

## Methods

| Name | Description |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Creates a `CmykColor` structure from a 32-bit cyan, magenta, yellow and black values. This method is deprecated. Please use more effective [`FromComponents`](../cmykcolorhelper/fromcomponents/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | The conversion from 32-bit ARGB to CMYKColor. This method is deprecated. Please use more effective [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Determines whether the specified Object, is equal to this instance. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | The get hash code. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | The to value. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | The conversion from CMYKColor to 32-bit ARGB Color using icc conversion with default profiles. This method is deprecated. Please use more effective [`ToArgb32`](../cmykcolorhelper/toargb32/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | The conversion from 32-bit ARGB color to CMYKColor. This method is deprecated. Please use more effective [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | The conversion from CMYKColor to Color. This method is deprecated. Please use more effective [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | The conversion from CMYKColor to Color using icc conversion. This method is deprecated. Please use more effective [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | The conversion from CMYKColor to Color using icc conversion. This method is deprecated. Please use more effective [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



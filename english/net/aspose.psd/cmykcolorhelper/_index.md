---
title: Class CmykColorHelper
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.CmykColorHelper class. Helper methods to work with CMYK color presented as a signed 32bit integer value. Provides the similar API as the CmykColor struct. Its more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields. Please prefer to use static methods of this class when possible instead of the deprecated CmykColor struct
type: docs
weight: 280
url: /net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

Helper methods to work with CMYK color presented as a signed 32-bit integer value. Provides the similar API as the [`CmykColor`](../cmykcolor/) struct. It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields. Please prefer to use static methods of this class when possible instead of the deprecated [`CmykColor`](../cmykcolor/) struct.

```csharp
public static class CmykColorHelper
```

## Methods

| Name | Description |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Creates CMYK from a 32-bit cyan, magenta, yellow and black values. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Gets the cyan component value. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Gets the black component value. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Gets the magenta component value. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Gets the yellow component value. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | The conversion from CMYK color to ARGB color. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | The conversion from CMYK colors to ARGB colors. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | The conversion from CMYK colors to ARGB colors. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | The conversion from CMYK color to ARGB Color using Icc conversion with default profiles. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | The conversion from CMYK color to ARGB color using Icc conversion with custom profile. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | The conversion from ARGB color to CMYK color. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | The conversion from ARGB colors to CMYK colors. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | The conversion from ARGB color to CMYK color. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | The conversion from ARGB colors to CMYK colors. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Converts RGB to CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Converts RGB to CMYK using custom ICC profiles. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



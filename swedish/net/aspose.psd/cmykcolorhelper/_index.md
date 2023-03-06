---
title: Class CmykColorHelper
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.CmykColorHelper klass. Hjälpmetoder för att arbeta med CMYKfärg presenteras som ett signerat 32bitars heltalsvärde. Tillhandahåller liknande API somCmykColorstruct. Den är mer lättviktig eftersom CMYKfärg presenteras precis som Int32 snarare än struktur med interna fält. Föredrar att använda statiska metoder av denna klass när det är möjligt istället för deprecated CmykColor struct.
type: docs
weight: 280
url: /sv/net/aspose.psd/cmykcolorhelper/
---
## CmykColorHelper class

Hjälpmetoder för att arbeta med CMYK-färg presenteras som ett signerat 32-bitars heltalsvärde. Tillhandahåller liknande API som[`CmykColor`](../cmykcolor/)struct. Den är mer lättviktig eftersom CMYK-färg presenteras precis som Int32 snarare än struktur med interna fält. Föredrar att använda statiska metoder av denna klass när det är möjligt istället för deprecated [`CmykColor`](../cmykcolor/) struct.

```csharp
public static class CmykColorHelper
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Skapar CMYK från 32-bitars cyan, magenta, gult och svart värden. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Hämtar värdet för cyankomponenten. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Får det svarta komponentvärdet. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Hämtar magenta komponentvärdet. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Får det gula komponentvärdet. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | Omvandlingen från CMYK-färg till ARGB-färg. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | Omvandlingen från CMYK-färger till ARGB-färger. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | Omvandlingen från CMYK-färger till ARGB-färger. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering med standardprofiler. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering med standardprofiler. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering med anpassad profil. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | Konverteringen från CMYK-färger till ARGB-färger med hjälp av Icc-konvertering med anpassade profiler. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | Omvandlingen från ARGB-färg till CMYK-färg. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | Omvandlingen från ARGB-färger till CMYK-färger. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | Omvandlingen från ARGB-färg till CMYK-färg. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | Omvandlingen från ARGB-färger till CMYK-färger. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Konverterar RGB till CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering med standardprofiler. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering med standardprofiler. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering med anpassade profiler. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Omvandlingen från ARGB-färger till CMYK-färger med Icc-konvertering med anpassade profiler. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Konverterar RGB till CMYK med hjälp av anpassade ICC-profiler. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)



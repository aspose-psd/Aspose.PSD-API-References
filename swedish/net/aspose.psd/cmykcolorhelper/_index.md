---
title: "Klassen CmykColorHelper"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.CmykColorHelper-klass. Hjälpmetoder för att arbeta med CMYK-färg som presenteras som ett signerat 32‑bitars heltal. Tillhandahåller ett liknande API som CmykColor‑strukturen. Den är mer lättviktig eftersom CMYK-färg presenteras bara som Int32 snarare än en struktur med interna fält. Föredra att använda de statiska metoderna i denna klass när det är möjligt istället för den föråldrade CmykColor‑strukturen."
type: docs
weight: 280
url: /sv/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

Hjälpmetoder för att arbeta med CMYK-färg som presenteras som ett signerat 32‑bitars heltal. Tillhandahåller ett liknande API som [`CmykColor`](../cmykcolor/) strukturen. Den är mer lättviktig eftersom CMYK-färg presenteras bara som Int32 snarare än en struktur med interna fält. Föredra att använda de statiska metoderna i denna klass när det är möjligt istället för den föråldrade [`CmykColor`](../cmykcolor/) strukturen.

```csharp
public static class CmykColorHelper
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Skapar CMYK från 32‑bitars cyan-, magenta-, gul- och svartvärden. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Hämtar cyan-komponentens värde. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Hämtar svart-komponentens värde. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Hämtar magenta-komponentens värde. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Hämtar gul-komponentens värde. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | Konverteringen från CMYK-färg till ARGB-färg. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | Konverteringen från CMYK-färger till ARGB-färger. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | Konverteringen från CMYK-färger till ARGB-färger. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och standardprofiler. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och anpassad profil. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | Konverteringen från ARGB-färg till CMYK-färg. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | Konverteringen från ARGB-färger till CMYK-färger. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | Konverteringen från ARGB-färg till CMYK-färg. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | Konverteringen från ARGB-färger till CMYK-färger. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Konverterar RGB till CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Konverterar RGB till CMYK med anpassade ICC-profiler. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



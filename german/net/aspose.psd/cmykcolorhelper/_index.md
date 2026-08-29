---
title: "Klasse CmykColorHelper"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.CmykColorHelper class. Hilfsmethoden zur Arbeit mit CMYK-Farben, die als vorzeichenbehafteter 32‑Bit‑Integerwert dargestellt werden. Bietet eine ähnliche API wie die CmykColor‑Struktur. Sie ist leichter, weil die CMYK‑Farbe nur als Int32 und nicht als Struktur mit internen Feldern dargestellt wird. Bitte verwenden Sie nach Möglichkeit die statischen Methoden dieser Klasse anstelle der veralteten CmykColor‑Struktur."
type: docs
weight: 280
url: /de/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

Hilfsmethoden zur Arbeit mit CMYK-Farben, die als vorzeichenbehafteter 32‑Bit‑Integerwert dargestellt werden. Bietet eine ähnliche API wie die [`CmykColor`](../cmykcolor/) Struktur. Sie ist leichter, weil die CMYK‑Farbe nur als Int32 und nicht als Struktur mit internen Feldern dargestellt wird. Bitte verwenden Sie nach Möglichkeit die statischen Methoden dieser Klasse anstelle der veralteten [`CmykColor`](../cmykcolor/) Struktur.

```csharp
public static class CmykColorHelper
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Erstellt CMYK aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Liefert den Cyan-Komponentenwert. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Liefert den Schwarz-Komponentenwert. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Liefert den Magenta-Komponentenwert. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Liefert den Gelb-Komponentenwert. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | Die Umwandlung von CMYK-Farbe zu ARGB-Farbe. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | Die Umwandlung von CMYK-Farbe zu ARGB Color mittels Icc-Konvertierung mit Standardprofilen. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | Die Umwandlung von CMYK-Farbe zu ARGB-Farbe mittels Icc-Konvertierung mit benutzerdefiniertem Profil. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Konvertiert RGB zu CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



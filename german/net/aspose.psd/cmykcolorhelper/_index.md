---
title: Class CmykColorHelper
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.CmykColorHelper klas. Hilfsmethoden zum Arbeiten mit CMYKFarben die als vorzeichenbehafteter 32BitGanzzahlwert dargestellt werden. Bietet eine ähnliche API wie dieCmykColorstruct. Es ist einfacher da CMYKFarben nur als Int32 dargestellt werden und nicht als Struktur mit internen Feldern. Bitte verwenden Sie nach Möglichkeit statische Methoden dieser Klasse anstelle der veralteten CmykColor struct.
type: docs
weight: 280
url: /de/net/aspose.psd/cmykcolorhelper/
---
## CmykColorHelper class

Hilfsmethoden zum Arbeiten mit CMYK-Farben, die als vorzeichenbehafteter 32-Bit-Ganzzahlwert dargestellt werden. Bietet eine ähnliche API wie die[`CmykColor`](../cmykcolor/)struct. Es ist einfacher, da CMYK-Farben nur als Int32 dargestellt werden und nicht als Struktur mit internen Feldern. Bitte verwenden Sie nach Möglichkeit statische Methoden dieser Klasse anstelle der veralteten [`CmykColor`](../cmykcolor/) struct.

```csharp
public static class CmykColorHelper
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | Erstellt CMYK aus 32-Bit-Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | Ruft den Cyan-Komponentenwert ab. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | Ruft den Schwarzkomponentenwert ab. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | Ruft den Magenta-Komponentenwert ab. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | Ruft den gelben Komponentenwert ab. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | Die Konvertierung von CMYK-Farbe in ARGB-Farbe. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | Die Konvertierung von CMYK-Farben in ARGB-Farben. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | Die Konvertierung von CMYK-Farben in ARGB-Farben. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | Die Konvertierung von CMYK-Farbe in ARGB-Farbe mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | Die Konvertierung von CMYK-Farben in ARGB-Farben mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | Die Konvertierung von CMYK-Farbe in ARGB-Farbe mithilfe der Icc-Konvertierung mit benutzerdefiniertem Profil. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | Die Konvertierung von CMYK-Farben in ARGB-Farben mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | Die Umwandlung von ARGB-Farbe in CMYK-Farbe. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | Die Konvertierung von ARGB-Farben in CMYK-Farben. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | Die Umwandlung von ARGB-Farbe in CMYK-Farbe. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | Die Konvertierung von ARGB-Farben in CMYK-Farben. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | Wandelt RGB in CMYK um. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | Die Konvertierung von ARGB-Farbe in CMYK-Farbe mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | Die Konvertierung von ARGB-Farben in CMYK-Farben mithilfe der Icc-Konvertierung mit Standardprofilen. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | Die Konvertierung von ARGB-Farbe in CMYK-Farbe mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | Die Konvertierung von ARGB-Farben in CMYK-Farben mithilfe der Icc-Konvertierung mit benutzerdefinierten Profilen. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | Konvertiert RGB in CMYK mit benutzerdefinierten ICC-Profilen. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)



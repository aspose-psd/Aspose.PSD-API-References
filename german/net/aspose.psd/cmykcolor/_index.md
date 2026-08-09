---
title: "Struktur CmykColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.CmykColor Struktur. Die CMYK-Farbe des Pixels"
type: docs
weight: 270
url: /de/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

Die CMYK-Farbe des Pixels.

```csharp
public struct CmykColor
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Gibt das Leere zurück. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Liefert den Cyan-Komponentenwert dieser [`Color`](../color/) Struktur. |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Liefert einen Wert, der angibt, ob diese [`Color`](../color/) Struktur nicht initialisiert ist. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Liefert den Schwarz-Komponentenwert dieser [`Color`](../color/) Struktur. |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Liefert den Magenta-Komponentenwert dieser [`Color`](../color/) Struktur. |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Liefert den Gelb-Komponentenwert dieser [`Color`](../color/) Struktur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Erstellt eine `CmykColor` Struktur aus 32-bit Cyan-, Magenta-, Gelb- und Schwarzwerten. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`FromComponents`](../cmykcolorhelper/fromcomponents/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | Die Konvertierung von 32-bit ARGB zu CMYKColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Der Hashcode wird abgerufen. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Der Rückgabewert. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | Die Konvertierung von CMYKColor zu 32-bit ARGB-Farbe unter Verwendung einer ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToArgb32`](../cmykcolorhelper/toargb32/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | Die Konvertierung von 32-bit ARGB-Farbe zu CMYKColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | Die Konvertierung von CMYKColor zu Color. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | Die Konvertierung von CMYKColor zu Color unter Verwendung einer ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



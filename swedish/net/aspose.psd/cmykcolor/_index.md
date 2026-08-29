---
title: "Struktur CmykColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.CmykColor‑struktur. CMYK‑färgen för pixeln"
type: docs
weight: 270
url: /sv/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

CMYK‑färgen för pixeln.

```csharp
public struct CmykColor
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | Hämtar den tomma. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | Hämtar cyan‑komponentens värde för denna [`Color`](../color/)‑struktur. |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | Hämtar ett värde som indikerar om denna [`Color`](../color/)‑struktur är oinitierad. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | Hämtar svart‑komponentens värde för denna [`Color`](../color/)‑struktur. |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | Hämtar magenta‑komponentens värde för denna [`Color`](../color/)‑struktur. |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | Hämtar gul‑komponentens värde för denna [`Color`](../color/)‑struktur. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | Skapar en `CmykColor`‑struktur från 32‑bitars cyan-, magenta-, gul- och svartvärden. Denna metod är föråldrad. Använd den mer effektiva [`FromComponents`](../cmykcolorhelper/fromcomponents/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | Konverteringen från 32‑bitars ARGB till CMYKColor. Denna metod är föråldrad. Använd den mer effektiva [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | Bestämmer om det angivna objektet är lika med den här instansen. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | Hämtar hash‑koden. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | Till‑värdet. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | Konverteringen från CMYKColor till 32‑bitars ARGB‑färg med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd den mer effektiva [`ToArgb32`](../cmykcolorhelper/toargb32/). |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | Konverteringen från 32‑bitars ARGB‑färg till CMYKColor. Denna metod är föråldrad. Använd den mer effektiva [`ToCmyk`](../cmykcolorhelper/tocmyk/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | Konverteringen från CMYKColor till Color. Denna metod är föråldrad. Använd den mer effektiva [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd den mer effektiva [`ToArgb`](../cmykcolorhelper/toargb/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd den mer effektiva [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd den mer effektiva [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | Konverteringen från CMYKColor till Color med icc‑konvertering. Denna metod är föråldrad. Använd den mer effektiva [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | Konverteringen från CMYKColor till Color med icc‑konvertering. Denna metod är föråldrad. Använd den mer effektiva [`ToArgbIcc`](../cmykcolorhelper/toargbicc/). |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



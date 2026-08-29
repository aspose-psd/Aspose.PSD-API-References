---
title: "Klass ColorPalette"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ColorPalette‑klass. Definierar en array av färger som utgör en färgpalett. Färgerna är 32‑bit ARGB‑färger. Inte ärvbar"
type: docs
weight: 370
url: /sv/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

Definierar en array av färger som utgör en färgpalett. Färgerna är 32‑bitars ARGB-färger. Klassen kan inte ärvas.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Initierar en ny instans av klassen `ColorPalette` och IsCompactPalette är falskt. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Initierar en ny instans av klassen `ColorPalette`. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Initierar en ny instans av klassen `ColorPalette`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Hämtar en array av 32‑bit ARGB‑strukturer. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Hämtar en array av [`Color`](../color/) strukturer. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Hämtar antalet poster. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Hämtar eller anger ett värde som indikerar om kompakt palett används. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Kopierar paletten. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Kopierar paletten. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Hämtar 32‑bit ARGB‑palettfärgen efter index. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Hämtar palettfärgen efter index. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Hämtar indexet för den närmaste färgen. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Hämtar indexet för den närmaste färgen. |

### Se även

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



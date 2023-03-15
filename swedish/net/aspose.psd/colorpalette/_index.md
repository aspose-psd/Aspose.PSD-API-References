---
title: Class ColorPalette
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ColorPalette klass. Definierar en uppsättning färger som utgör en färgpalett. Färgerna är 32bitars ARGBfärger. Inte ärftlig.
type: docs
weight: 370
url: /sv/net/aspose.psd/colorpalette/
---
## ColorPalette class

Definierar en uppsättning färger som utgör en färgpalett. Färgerna är 32-bitars ARGB-färger. Inte ärftlig.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Initierar en ny instans av`ColorPalette` klass och IsCompactPalette är falsk. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Initierar en ny instans av`ColorPalette` klass och IsCompactPalette är falsk. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Initierar en ny instans av`ColorPalette` class. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Initierar en ny instans av`ColorPalette` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Får en array med 32-bitars ARGB-strukturer. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Får en array av[`Color`](../color/) strukturer. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Hämtar antalet poster. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Hämtar eller ställer in ett värde som anger om kompakt palett används. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Kopierar paletten. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Kopierar paletten. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Får 32-bitars ARGB-palettens färg efter index. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Hämtar palettfärgen efter index. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Hämtar index för närmaste färg. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Hämtar index för närmaste färg. |

### Se även

* interface [IColorPalette](../icolorpalette/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)



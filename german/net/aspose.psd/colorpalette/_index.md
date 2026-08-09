---
title: "Klasse ColorPalette"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ColorPalette‑Klasse. Definiert ein Array von Farben, das eine Farbpalette bildet. Die Farben sind 32‑Bit‑ARGB‑Farben. Nicht vererbbar"
type: docs
weight: 370
url: /de/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

Definiert ein Array von Farben, das eine Farbpalette bildet. Die Farben sind 32‑Bit‑ARGB‑Farben. Nicht vererbbar.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Initialisiert eine neue Instanz der `ColorPalette`‑Klasse und IsCompactPalette ist false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Initialisiert eine neue Instanz der `ColorPalette`‑Klasse und IsCompactPalette ist false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Initialisiert eine neue Instanz der `ColorPalette`‑Klasse. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Initialisiert eine neue Instanz der `ColorPalette`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Liefert ein Array von 32‑Bit‑ARGB‑Strukturen. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Liefert ein Array von [`Color`](../color/)‑Strukturen. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Gibt die Anzahl der Einträge zurück. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Liest oder setzt einen Wert, der angibt, ob eine kompakte Palette verwendet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Kopiert die Palette. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Kopiert die Palette. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Liefert die 32‑Bit‑ARGB-Palettefarbe nach Index. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Liefert die Palettenfarbe nach Index. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Liefert den Index der nächstgelegenen Farbe. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Liefert den Index der nächstgelegenen Farbe. |

### Siehe auch

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



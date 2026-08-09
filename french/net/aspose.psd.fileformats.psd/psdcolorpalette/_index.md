---
title: "Classe PsdColorPalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.PsdColorPalette class. La palette de couleurs PSD"
type: docs
weight: 4040
url: /fr/net/aspose.psd.fileformats.psd/psdcolorpalette/
---
{{< psd/tize >}}
## PsdColorPalette class

La palette de couleurs PSD.

```csharp
public class PsdColorPalette : IPsdColorPalette
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PsdColorPalette](psdcolorpalette/#constructor_6)(byte[]) | Initialise une nouvelle instance de la classe `PsdColorPalette` et IsCompactPalette est false. |
| [PsdColorPalette](psdcolorpalette/#constructor)(Color[]) | Initialise une nouvelle instance de la classe `PsdColorPalette` et IsCompactPalette est false. |
| [PsdColorPalette](psdcolorpalette/#constructor_4)(IColorPalette) | Initialise une nouvelle instance de la classe `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_7)(byte[], bool) | Initialise une nouvelle instance de la classe `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_8)(byte[], short) | Initialise une nouvelle instance de la classe `PsdColorPalette` et IsCompactPalette est false. |
| [PsdColorPalette](psdcolorpalette/#constructor_1)(Color[], bool) | Initialise une nouvelle instance de la classe `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_2)(Color[], short) | Initialise une nouvelle instance de la classe `PsdColorPalette` et IsCompactPalette est false. |
| [PsdColorPalette](psdcolorpalette/#constructor_5)(IColorPalette, short) | Initialise une nouvelle instance de la classe `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_10)(int[], bool) | Initialise une nouvelle instance de la classe `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_9)(byte[], short, bool) | Initialise une nouvelle instance de la classe `PsdColorPalette`. |
| [PsdColorPalette](psdcolorpalette/#constructor_3)(Color[], short, bool) | Initialise une nouvelle instance de la classe `PsdColorPalette`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Argb32Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/argb32entries/) { get; } | Obtient un tableau de couleurs ARGB 32 bits. |
| [Entries](../../aspose.psd.fileformats.psd/psdcolorpalette/entries/) { get; } | Obtient un tableau de structures [`Color`](../../aspose.psd/color/). |
| [EntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/entriescount/) { get; } | Obtient le nombre d'entrées. |
| [HasTransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/hastransparentcolor/) { get; } | Obtient une valeur indiquant si une couleur transparente existe. |
| [IsCompactPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/) { get; } | Obtient une valeur indiquant si la palette est compacte. |
| [RawEntries](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentries/) { get; } | Obtient les données brutes des entrées de la palette de couleurs. |
| [RawEntriesCount](../../aspose.psd.fileformats.psd/psdcolorpalette/rawentriescount/) { get; } | Obtient le nombre brut d'entrées de la palette de couleurs. |
| [TransparentColor](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentcolor/) { get; } | Obtient la couleur transparente. |
| [TransparentIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/transparentindex/) { get; } | Obtient l'index de la couleur transparente. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette)(IColorPalette) | Copie la palette. |
| static [CopyPalette](../../aspose.psd.fileformats.psd/psdcolorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Copie la palette. |
| [GetArgb32Color](../../aspose.psd.fileformats.psd/psdcolorpalette/getargb32color/)(int) | Obtient la couleur de la palette ARGB 32 bits par indice. |
| [GetColor](../../aspose.psd.fileformats.psd/psdcolorpalette/getcolor/)(int) | Obtient la couleur de la palette par indice. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Obtient l'indice de la couleur la plus proche. |
| [GetNearestColorIndex](../../aspose.psd.fileformats.psd/psdcolorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Obtient l'indice de la couleur la plus proche. |

### Voir aussi

* interface [IPsdColorPalette](../../aspose.psd/ipsdcolorpalette/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)



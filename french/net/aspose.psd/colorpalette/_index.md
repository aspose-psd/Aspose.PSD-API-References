---
title: "Classe ColorPalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ColorPalette. Définit un tableau de couleurs qui composent une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable"
type: docs
weight: 370
url: /fr/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

Définit un tableau de couleurs constituant une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Initialise une nouvelle instance de la classe `ColorPalette` et IsCompactPalette est false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Initialise une nouvelle instance de la classe `ColorPalette`. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Initialise une nouvelle instance de la classe `ColorPalette`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Obtient un tableau de structures ARGB 32 bits. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Obtient un tableau de structures [`Color`](../color/). |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Obtient le nombre d'entrées. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Obtient ou définit une valeur indiquant si une palette compacte est utilisée. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Copie la palette. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Copie la palette. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Obtient la couleur de la palette ARGB 32 bits par indice. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Obtient la couleur de la palette par indice. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Obtient l'indice de la couleur la plus proche. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Obtient l'indice de la couleur la plus proche. |

### Voir aussi

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: Class ColorPalette
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ColorPalette class. Defines an array of colors that make up a color palette. The colors are 32bit ARGB colors. Not inheritable
type: docs
weight: 370
url: /net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Constructors

| Name | Description |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Initializes a new instance of the `ColorPalette` class and IsCompactPalette is false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Initializes a new instance of the `ColorPalette` class. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Initializes a new instance of the `ColorPalette` class. |

## Properties

| Name | Description |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Gets an array of 32-bit ARGB structures. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Gets an array of [`Color`](../color/) structures. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Gets the entries count. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Gets or sets a value indicating whether compact palette is used. |

## Methods

| Name | Description |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Copies the palette. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Copies the palette. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Gets the 32-bit ARGB palette color by index. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Gets the palette color by index. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Gets the index of the nearest color. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Gets the index of the nearest color. |

### See Also

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



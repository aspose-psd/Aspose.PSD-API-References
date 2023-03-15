---
title: Class ColorPalette
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.ColorPalette clase. Define una matriz de colores que componen una paleta de colores. Los colores son colores ARGB de 32 bits. No heredable.
type: docs
weight: 370
url: /es/net/aspose.psd/colorpalette/
---
## ColorPalette class

Define una matriz de colores que componen una paleta de colores. Los colores son colores ARGB de 32 bits. No heredable.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Inicializa una nueva instancia del`ColorPalette` class y IsCompactPalette es false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Inicializa una nueva instancia del`ColorPalette` class y IsCompactPalette es false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Inicializa una nueva instancia del`ColorPalette` clase. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Inicializa una nueva instancia del`ColorPalette` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Obtiene una matriz de estructuras ARGB de 32 bits. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Obtiene una matriz de[`Color`](../color/) estructuras. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Obtiene el recuento de entradas. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Obtiene o establece un valor que indica si se utiliza la paleta compacta. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Copia la paleta. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Copia la paleta. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Obtiene el color de la paleta ARGB de 32 bits por index. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Obtiene el color de la paleta por index. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Obtiene el índice del color más cercano. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Obtiene el índice del color más cercano. |

### Ver también

* interface [IColorPalette](../icolorpalette/)
* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)



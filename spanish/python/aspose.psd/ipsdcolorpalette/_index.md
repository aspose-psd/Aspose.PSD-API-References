---
title: "Clase IPsdColorPalette"
type: docs
weight: 1990
url: /es/python-net/aspose.psd/ipsdcolorpalette/
---

**Summary:** The pasd color palette

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPsdColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Obtiene una matriz de estructuras ARGB de 32 bits. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Obtiene una matriz de estructuras [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Obtiene el recuento de entradas. |
| has_transparent_color | bool | r | Obtiene un valor que indica si existe un color transparente. |
| is_compact_palette | bool | r | Obtiene un valor que indica si se usa una paleta compacta. |
| raw_entries | byte | r | Obtiene los datos sin procesar de las entradas de la paleta de colores. |
| raw_entries_count | int | r | Obtiene el recuento de entradas sin procesar de la paleta de colores. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Obtiene el color transparente. |
| transparent_index | short | r | Obtiene el índice del color transparente. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [get_color(index)](#get_color_index_2) | Obtiene el color de la paleta por índice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Obtiene el índice del color ARGB de 32 bits más cercano. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Obtiene el índice del color ARGB de 32 bits más cercano. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

Obtiene el color de la paleta ARGB de 32 bits por índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de color de la paleta ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La entrada de la paleta de colores especificada por el <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

Obtiene el color de la paleta por índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | int | El índice de color de la paleta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | La entrada de la paleta de colores especificada por el <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Obtiene el índice del color ARGB de 32 bits más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_color | int | El color ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Obtiene el índice del color ARGB de 32 bits más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |



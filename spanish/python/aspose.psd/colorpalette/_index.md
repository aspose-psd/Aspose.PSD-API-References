---
title: "Clase ColorPalette"
type: docs
weight: 800
url: /es/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) y IsCompactPalette es false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) y IsCompactPalette es false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Obtiene una matriz de estructuras ARGB de 32 bits. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Obtiene una matriz de estructuras [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Obtiene el recuento de entradas. |
| is_compact_palette | bool | r | Obtiene o establece un valor que indica si se utiliza una paleta compacta. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copia la paleta. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copia la paleta. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [get_color(index)](#get_color_index_4) | Obtiene el color de la paleta por índice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Obtiene el índice del color más cercano. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Obtiene el índice del color más cercano. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_entries | int | Las entradas de la paleta de colores ARGB de 32 bits. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_entries | int | Las entradas de la paleta de colores ARGB de 32 bits. |
| is_compact_palette | bool | Indica si la paleta está compacta. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Indica si la paleta está compacta. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copia la paleta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La paleta recién creada y copiada o null si se pasa una paleta null. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copia la paleta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores. |
| use_compact_palette | bool | Indica si la paleta es compacta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La paleta recién creada y copiada o null si se pasa una paleta null. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


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


### Method: get_color(index) {#get_color_index_4}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Obtiene el índice del color más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_32_color | int | El color ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Obtiene el índice del color más cercano.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice del color más cercano. |



---
title: "Clase PsdColorPalette"
type: docs
weight: 1750
url: /es/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Obtiene una matriz de colores ARGB de 32 bits. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Obtiene una matriz de estructuras [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Obtiene el recuento de entradas. |
| has_transparent_color | bool | r | Obtiene un valor que indica si existe un color transparente. |
| is_compact_palette | bool | r | Obtiene un valor que indica si la paleta es compacta. |
| raw_entries | byte | r | Obtiene los datos sin procesar de las entradas de la paleta de colores. |
| raw_entries_count | int | r | Obtiene el recuento de entradas sin procesar de la paleta de colores. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Obtiene el color transparente. |
| transparent_index | short | r | Obtiene el índice del color transparente. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copia la paleta. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copia la paleta. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [get_color(index)](#get_color_index_4) | Obtiene el color de la paleta por índice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Obtiene el índice del color más cercano. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Obtiene el índice del color más cercano. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta de colores. |
| transparent_index | short | El índice de color transparente. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Las entradas de la paleta de colores ARGB de 32 bits. |
| is_compact_palette | bool | Indica si la paleta está compacta. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Las entradas de la paleta de colores. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Las entradas de la paleta de colores. |
| is_compact_palette | bool | Indica si la paleta está compacta. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Las entradas de la paleta de colores. |
| transparent_index | short | El índice de color transparente. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Las entradas de la paleta de colores. |
| transparent_index | short | El índice de color transparente. |
| use_compact_palette | bool | Indica si la paleta está compacta. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raw_entries_data | byte | Los datos de las entradas crudas. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raw_entries_data | byte | Los datos de las entradas crudas. |
| is_compact_palette | bool | Indica si la paleta está compacta. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) y IsCompactPalette es false.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raw_entries_data | byte | Los datos de las entradas crudas. |
| transparent_index | short | El índice de color transparente. Nota: el índice no es el índice de las entradas crudas, sino que es para la matriz de colores convertidos. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Inicializa una nueva instancia de la clase [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| raw_entries_data | byte | Los datos de las entradas crudas. |
| transparent_index | short | El índice de color transparente. Nota: el índice no es el índice de las entradas crudas, sino que es para la matriz de colores convertidos. |
| use_compact_palette | bool | Indica si la paleta está compacta. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | La paleta recién creada y copiada o null si se pasa una paleta null. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | La paleta recién creada y copiada o null si se pasa una paleta null. |


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



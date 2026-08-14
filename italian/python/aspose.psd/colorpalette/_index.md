---
title: "Classe ColorPalette"
type: docs
weight: 800
url: /it/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) e IsCompactPalette è false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) e IsCompactPalette è false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Restituisce un array di strutture ARGB a 32 bit. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Restituisce un array di strutture [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Restituisce il conteggio delle voci. |
| is_compact_palette | bool | r | Ottiene o imposta un valore che indica se viene utilizzata una palette compatta. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copia la palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copia la palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Restituisce il colore della tavolozza ARGB a 32 bit per indice. |
| [get_color(index)](#get_color_index_4) | Restituisce il colore della tavolozza per indice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Restituisce l'indice del colore più vicino. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Restituisce l'indice del colore più vicino. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_entries | int | Le voci della tavolozza dei colori ARGB a 32 bit. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_entries | int | Le voci della tavolozza dei colori ARGB a 32 bit. |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [ColorPalette](/psd/python-net/aspose.psd/colorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copia la palette.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La tavolozza dei colori. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La tavolozza appena creata e copiata o null se è stata passata una tavolozza null. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copia la palette.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La tavolozza dei colori. |
| use_compact_palette | bool | Indica se la tavolozza è compatta. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | La tavolozza appena creata e copiata o null se è stata passata una tavolozza null. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


```
 get_argb_32_color(index) 
```

Restituisce il colore della tavolozza ARGB a 32 bit per indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del colore della tavolozza ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La voce della tavolozza dei colori specificata da <paramref name="index" />. |


### Method: get_color(index) {#get_color_index_4}


```
 get_color(index) 
```

Restituisce il colore della tavolozza per indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice del colore della tavolozza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | La voce della tavolozza dei colori specificata da <paramref name="index" />. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

Restituisce l'indice del colore più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_32_color | int | Il colore ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice del colore più vicino. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

Restituisce l'indice del colore più vicino.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice del colore più vicino. |



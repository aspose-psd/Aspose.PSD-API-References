---
title: "PsdColorPalette Classe"
type: docs
weight: 1750
url: /it/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false. |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false. |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false. |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false. |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | Restituisce un array di colori ARGB a 32 bit. |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | Restituisce un array di strutture [Color](/psd/python-net/aspose.psd/color/). |
| entries_count | int | r | Restituisce il conteggio delle voci. |
| ha_colore_trasparente | bool | r | Restituisce un valore che indica se esiste un colore trasparente. |
| is_compact_palette | bool | r | Restituisce un valore che indica se la palette è compatta. |
| raw_entries | byte | r | Restituisce i dati grezzi delle voci della tavolozza dei colori. |
| raw_entries_count | int | r | Restituisce il conteggio grezzo delle voci della tavolozza dei colori. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | Restituisce il colore trasparente. |
| transparent_index | short | r | Restituisce l'indice del colore trasparente. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copia la palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copia la palette. |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | Restituisce il colore della tavolozza ARGB a 32 bit per indice. |
| [get_color(index)](#get_color_index_4) | Restituisce il colore della tavolozza per indice. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | Restituisce l'indice del colore più vicino. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | Restituisce l'indice del colore più vicino. |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La tavolozza dei colori. |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La tavolozza dei colori. |
| transparent_index | short | L'indice del colore trasparente. |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette_argb_32_entries | int | Le voci della tavolozza dei colori a 32-bit ARGB. |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Le voci della tavolozza dei colori. |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Le voci della tavolozza dei colori. |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Le voci della tavolozza dei colori. |
| transparent_index | short | L'indice del colore trasparente. |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | Le voci della tavolozza dei colori. |
| transparent_index | short | L'indice del colore trasparente. |
| use_compact_palette | bool | Indica se la tavolozza è compatta. |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raw_entries_data | byte | I dati grezzi delle voci. |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raw_entries_data | byte | I dati grezzi delle voci. |
| is_compact_palette | bool | Indica se la tavolozza è compatta. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) e IsCompactPalette è false.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raw_entries_data | byte | I dati grezzi delle voci. |
| transparent_index | short | L'indice del colore trasparente. Nota che l'indice non è l'indice grezzo delle voci, ma è per l'array di colori convertito. |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

Inizializza una nuova istanza della classe [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raw_entries_data | byte | I dati grezzi delle voci. |
| transparent_index | short | L'indice del colore trasparente. Nota che l'indice non è l'indice grezzo delle voci, ma è per l'array di colori convertito. |
| use_compact_palette | bool | Indica se la tavolozza è compatta. |

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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | La tavolozza appena creata e copiata o null se è stata passata una tavolozza null. |


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
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | La tavolozza appena creata e copiata o null se è stata passata una tavolozza null. |


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



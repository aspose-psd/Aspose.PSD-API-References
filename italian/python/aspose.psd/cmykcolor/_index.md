---
title: "CmykColor Classe"
type: docs
weight: 630
url: /it/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Inizializza una nuova istanza della classe CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | byte | r | Ottiene il valore del componente ciano di questa struttura [Color](/psd/python-net/aspose.psd/color/). |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Ottiene il valore vuoto. |
| is_empty | bool | r | Restituisce un valore che indica se questa struttura [Color](/psd/python-net/aspose.psd/color/) è non inizializzata. |
| k | byte | r | Ottiene il valore del componente nero di questa struttura [Color](/psd/python-net/aspose.psd/color/). |
| m | byte | r | Ottiene il valore del componente magenta di questa struttura [Color](/psd/python-net/aspose.psd/color/). |
| y | byte | r | Ottiene il valore del componente giallo di questa struttura [Color](/psd/python-net/aspose.psd/color/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Crea una struttura [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) da valori a 32 bit di ciano, magenta, giallo e nero.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | La conversione da CMYKColor a Color ARGB a 32 bit usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | Il valore to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Inizializza una nuova istanza della classe CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Crea una struttura [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) da valori a 32 bit di ciano, magenta, giallo e nero.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| ciano | int | Il componente ciano. I valori validi sono da 0 a 255. |
| magenta | int | Il componente magenta. I valori validi sono da 0 a 255. |
| giallo | int | Il componente giallo. I valori validi sono da 0 a 255. |
| nero | int | Il componente nero. I valori validi sono da 0 a 255. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Il [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

La conversione da CMYKColor a Color ARGB a 32 bit usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'array del colore ARGB a 32 bit. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Il <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

La conversione da colore ARGB a 32 bit a CMYKColor.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int | I pixel del formato ARGB a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Il <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | L'array dei colori ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | L'array dei colori ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Il [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc rgb. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Il [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Il [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da CMYKColor a Color usando la conversione icc.<br/>            Questo metodo è deprecato. Si prega di utilizzare più efficace Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo icc rgb. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Il [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

Il valore to.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| long | L'intero. |



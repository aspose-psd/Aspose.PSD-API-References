---
title: "CmykColorHelper Classe"
type: docs
weight: 640
url: /it/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Crea CMYK da valori ciano, magenta, giallo e nero a 32 bit. |
| [get_c(cmyk)](#get_c_cmyk_2) | Ottiene il valore del componente ciano. |
| [get_k(cmyk)](#get_k_cmyk_3) | Ottiene il valore del componente nero. |
| [get_m(cmyk)](#get_m_cmyk_4) | Ottiene il valore del componente magenta. |
| [get_y(cmyk)](#get_y_cmyk_5) | Ottiene il valore del componente giallo. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | La conversione da colori CMYK a colori ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | La conversione da colori CMYK a colori ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | La conversione da colori CMYK a colori ARGB. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | La conversione da colori ARGB a colori CMYK. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Converte RGB in CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Converte RGB in CMYK usando profili ICC personalizzati. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Crea CMYK da valori ciano, magenta, giallo e nero a 32 bit.

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
| int | Il colore CMYK presentato come valore intero a 32 bit. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Ottiene il valore del componente ciano.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente ciano. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Ottiene il valore del componente nero.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente nero. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Ottiene il valore del componente magenta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente magenta. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Ottiene il valore del componente giallo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore del componente giallo. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | I colori ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int | I colori CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | I colori ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int | I colori CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori ARGB presentati come valori interi a 32 bit. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | I colori ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | I colori ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int | I pixel CMYK presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | I colori ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cmyk_pixels | int | I colori CMYK presentati come valori interi a 32 bit. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | I colori ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int | I colori ARGB presentati come valori interi a 32 bit. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

La conversione da colori ARGB a colori CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Converte RGB in CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb_pixels | int | I colori RGB presentati come valori interi a 32 bit. |
| start_index | int | L'indice di inizio del colore RGB. |
| lunghezza | int | Il numero di pixel RGB da convertire. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | I colori CMYK presentati come array di byte. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | I colori ARGB. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | I colori ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso contenente il profilo Icc CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | I colori CMYK presentati come valori interi a 32 bit. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converte RGB in CMYK usando profili ICC personalizzati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels | int | I colori RGB presentati come valori interi a 32 bit. |
| start_index | int | L'indice di inizio del colore RGB. |
| lunghezza | int | Il numero di pixel RGB da convertire. |
| rgb_icc_stream | _io.BufferedRandom | Il flusso del profilo RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Il flusso del profilo CMYK. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | I colori CMYK presentati come array di byte. |



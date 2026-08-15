---
title: "CmykColorHelper-klass"
type: docs
weight: 640
url: /sv/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden. |
| [get_c(cmyk)](#get_c_cmyk_2) | Hämtar cyan-komponentens värde. |
| [get_k(cmyk)](#get_k_cmyk_3) | Hämtar svartkomponentens värde. |
| [get_m(cmyk)](#get_m_cmyk_4) | Hämtar magentakomponentens värde. |
| [get_y(cmyk)](#get_y_cmyk_5) | Hämtar gulkomponentens värde. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | Konverteringen från CMYK-färger till ARGB-färger. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | Konverteringen från ARGB-färger till CMYK-färger. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Konverterar RGB till CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Konverterar RGB till CMYK med anpassade ICC-profiler. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cyan | int | Cyan-komponenten. Giltiga värden är 0 till 255. |
| magenta | int | Magentakomponenten. Giltiga värden är 0 till 255. |
| gul | int | Gulkomponenten. Giltiga värden är 0 till 255. |
| svart | int | Svartkomponenten. Giltiga värden är 0 till 255. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Hämtar cyan-komponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Cyan-komponentvärdet. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Hämtar svartkomponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det svarta komponentvärdet. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Hämtar magentakomponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det magenta komponentvärdet. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Hämtar gulkomponentens värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det gula komponentvärdet. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | ARGB-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int | CMYK-pixlarna presenterade som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int | ARGB-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Konverterar RGB till CMYK.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int | RGB-färgerna presenterade som 32-bitars heltalsvärden. |
| start_index | int | Startindexet för RGB-färgen. |
| längd | int | Antalet RGB-pixlar att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | CMYK-färgerna presenterade som en bytearray. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB-färgerna. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller RGB Icc-profilen. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller CMYK Icc-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Konverterar RGB till CMYK med anpassade ICC-profiler.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixlar | int | RGB-färgerna presenterade som 32-bitars heltalsvärden. |
| start_index | int | Startindexet för RGB-färgen. |
| längd | int | Antalet RGB-pixlar att konvertera. |
| rgb_icc_stream | _io.BufferedRandom | RGB-profilströmmen. |
| cmyk_icc_stream | _io.BufferedRandom | CMYK-profilströmmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | CMYK-färgerna presenterade som en bytearray. |



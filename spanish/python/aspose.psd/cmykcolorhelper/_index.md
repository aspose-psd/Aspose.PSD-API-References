---
title: "CmykColorHelper Clase"
type: docs
weight: 640
url: /es/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits. |
| [get_c(cmyk)](#get_c_cmyk_2) | Obtiene el valor del componente cian. |
| [get_k(cmyk)](#get_k_cmyk_3) | Obtiene el valor del componente negro. |
| [get_m(cmyk)](#get_m_cmyk_4) | Obtiene el valor del componente magenta. |
| [get_y(cmyk)](#get_y_cmyk_5) | Obtiene el valor del componente amarillo. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | La conversión de colores CMYK a colores ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | La conversión de colores CMYK a colores ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | La conversión de colores CMYK a colores ARGB. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | La conversión de colores ARGB a colores CMYK. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Convierte RGB a CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Convierte RGB a CMYK usando perfiles ICC personalizados. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Crea CMYK a partir de valores de cian, magenta, amarillo y negro de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cian | int | El componente cian. Los valores válidos son de 0 a 255. |
| magenta | int | El componente magenta. Los valores válidos son de 0 a 255. |
| amarillo | int | El componente amarillo. Los valores válidos son de 0 a 255. |
| negro | int | El componente negro. Los valores válidos son de 0 a 255. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El color CMYK presentado como un valor entero de 32 bits. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Obtiene el valor del componente cian.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente cian. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Obtiene el valor del componente negro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente negro. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Obtiene el valor del componente magenta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente magenta. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Obtiene el valor del componente amarillo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk | int | El color CMYK presentado como un valor entero de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor del componente amarillo. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Los colores ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Los colores ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int | Los colores CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores ARGB presentados como valores enteros de 32 bits. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Los colores ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Los colores ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int | Los píxeles CMYK presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Los colores ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de colores CMYK a colores ARGB usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | int | Los colores CMYK presentados como valores enteros de 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Los colores ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int | Los colores ARGB presentados como valores enteros de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

La conversión de colores ARGB a colores CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Convierte RGB a CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int | Los colores RGB presentados como valores enteros de 32 bits. |
| start_index | int | El índice de inicio del color RGB. |
| longitud | int | El número de píxeles RGB a convertir. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Los colores CMYK presentados como una matriz de bytes. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles predeterminados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Los colores ARGB. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversión de colores ARGB a colores CMYK usando conversión Icc con perfiles personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Los colores ARGB. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil Icc CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los colores CMYK presentados como valores enteros de 32 bits. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Convierte RGB a CMYK usando perfiles ICC personalizados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | int | Los colores RGB presentados como valores enteros de 32 bits. |
| start_index | int | El índice de inicio del color RGB. |
| longitud | int | El número de píxeles RGB a convertir. |
| rgb_icc_stream | _io.BufferedRandom | El flujo del perfil RGB. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo del perfil CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Los colores CMYK presentados como una matriz de bytes. |



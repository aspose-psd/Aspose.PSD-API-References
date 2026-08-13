---
title: "CmykColorHelper Classe"
type: docs
weight: 640
url: /fr/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Crée le CMYK à partir de valeurs cyan, magenta, jaune et noir 32 bits. |
| [get_c(cmyk)](#get_c_cmyk_2) | Obtient la valeur du composant cyan. |
| [get_k(cmyk)](#get_k_cmyk_3) | Obtient la valeur du composant noir. |
| [get_m(cmyk)](#get_m_cmyk_4) | Obtient la valeur du composant magenta. |
| [get_y(cmyk)](#get_y_cmyk_5) | Obtient la valeur du composant jaune. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | La conversion des couleurs CMYK en couleurs ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | La conversion des couleurs CMYK en couleurs ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | La conversion des couleurs CMYK en couleurs ARGB. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | La conversion des couleurs CMYK en couleurs ARGB utilisant la conversion Icc avec des profils personnalisés. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | La conversion des couleurs CMYK en couleurs ARGB utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | La conversion des couleurs ARGB en couleurs CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | La conversion des couleurs ARGB en couleurs CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | La conversion des couleurs ARGB en couleurs CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | La conversion des couleurs ARGB en couleurs CMYK. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Convertit RGB en CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils par défaut. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils par défaut. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils personnalisés. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Convertit RGB en CMYK en utilisant des profils ICC personnalisés. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Crée le CMYK à partir de valeurs cyan, magenta, jaune et noir 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cyan | int | Le composant cyan. Les valeurs valides sont de 0 à 255. |
| magenta | int | Le composant magenta. Les valeurs valides sont de 0 à 255. |
| jaune | int | Le composant jaune. Les valeurs valides sont de 0 à 255. |
| noir | int | Le composant noir. Les valeurs valides sont de 0 à 255. |

**Returns**

| Type | Description |
| :- | :- |
| int | La couleur CMYK présentée comme une valeur entière de 32 bits. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Obtient la valeur du composant cyan.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant cyan. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Obtient la valeur du composant noir.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant noir. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Obtient la valeur du composant magenta.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant magenta. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Obtient la valeur du composant jaune.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk | int | La couleur CMYK présentée comme une valeur entière de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur du composant jaune. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

La conversion des couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

La conversion des couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

La conversion des couleurs CMYK en couleurs ARGB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs ARGB présentées comme des valeurs entières de 32 bits. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion des couleurs CMYK en couleurs ARGB utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc RGB. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

La conversion des couleurs CMYK en couleurs ARGB en utilisant la conversion Icc avec les profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | Les pixels CMYK présentés comme des valeurs entières de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion des couleurs CMYK en couleurs ARGB utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc CMYK. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc RGB. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int | Les couleurs ARGB présentées comme des valeurs entières de 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

La conversion des couleurs ARGB en couleurs CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Convertit RGB en CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| start_index | int | L'index de départ de la couleur RGB. |
| longueur | int | Le nombre de pixels RGB à convertir. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Les couleurs CMYK présentées sous forme de tableau d'octets. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

La conversion des couleurs ARGB en couleurs CMYK utilisant la conversion Icc avec des profils personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Les couleurs ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil Icc CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les couleurs CMYK présentées comme des valeurs entières de 32 bits. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Convertit RGB en CMYK en utilisant des profils ICC personnalisés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int | Les couleurs RGB présentées sous forme de valeurs entières 32 bits. |
| start_index | int | L'index de départ de la couleur RGB. |
| longueur | int | Le nombre de pixels RGB à convertir. |
| rgb_icc_stream | _io.BufferedRandom | Le flux du profil RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux du profil CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Les couleurs CMYK présentées sous forme de tableau d'octets. |



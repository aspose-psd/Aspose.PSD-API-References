---
title: "CmykColorHelper Class"
type: docs
weight: 640
url: /nl/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Maakt CMYK aan op basis van 32-bit cyaan-, magenta-, geel- en zwartwaarden. |
| [get_c(cmyk)](#get_c_cmyk_2) | Haalt de cyaancomponentwaarde op. |
| [get_k(cmyk)](#get_k_cmyk_3) | Haalt de zwartcomponentwaarde op. |
| [get_m(cmyk)](#get_m_cmyk_4) | Haalt de magentacomponentwaarde op. |
| [get_y(cmyk)](#get_y_cmyk_5) | Haalt de geelcomponentwaarde op. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | De conversie van CMYK-kleuren naar ARGB-kleuren. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | De conversie van CMYK-kleuren naar ARGB-kleuren. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | De conversie van CMYK-kleuren naar ARGB-kleuren. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en standaardprofielen. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en aangepaste profielen. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en standaardprofielen. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en aangepaste profielen. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | De conversie van ARGB-kleuren naar CMYK-kleuren. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | De conversie van ARGB-kleuren naar CMYK-kleuren. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | De conversie van ARGB-kleuren naar CMYK-kleuren. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | De conversie van ARGB-kleuren naar CMYK-kleuren. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Converteert RGB naar CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en standaardprofielen. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en aangepaste profielen. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en standaardprofielen. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en aangepaste profielen. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Converteert RGB naar CMYK met aangepaste ICC-profielen. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Maakt CMYK aan op basis van 32-bit cyaan-, magenta-, geel- en zwartwaarden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cyaan | int | Het cyaancomponent. Geldige waarden zijn 0 tot en met 255. |
| magenta | int | Het magentacomponent. Geldige waarden zijn 0 tot en met 255. |
| geel | int | Het geelcomponent. Geldige waarden zijn 0 tot en met 255. |
| zwart | int | Het zwartcomponent. Geldige waarden zijn 0 tot en met 255. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleur gepresenteerd als een 32-bits geheel getal. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Haalt de cyaancomponentwaarde op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De cyaancomponentwaarde. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Haalt de zwartcomponentwaarde op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De zwarte componentwaarde. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Haalt de magentacomponentwaarde op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De magenta componentwaarde. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Haalt de geelcomponentwaarde op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De gele componentwaarde. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

De conversie van CMYK-kleuren naar ARGB-kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

De conversie van CMYK-kleuren naar ARGB-kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

De conversie van CMYK-kleuren naar ARGB-kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De ARGB-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en standaardprofielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en aangepaste profielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | De stroom die het CMYK Icc-profiel bevat. |
| rgb_icc_stream | _io.BufferedRandom | De stroom die het RGB Icc-profiel bevat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en standaardprofielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | int | De CMYK-pixels gepresenteerd als 32-bits geheel getallen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en aangepaste profielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |
| cmyk_icc_stream | _io.BufferedRandom | De stroom die het CMYK Icc-profiel bevat. |
| rgb_icc_stream | _io.BufferedRandom | De stroom die het RGB Icc-profiel bevat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_pixels | int | De ARGB-kleuren gepresenteerd als 32-bits geheel getallen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Converteert RGB naar CMYK.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_pixels | int | De RGB-kleuren weergegeven als 32-bits gehele getallen. |
| start_index | int | De startindex van de RGB-kleur. |
| lengte | int | Het aantal RGB-pixels om te converteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | De CMYK-kleuren weergegeven als een byte-array. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en standaardprofielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en aangepaste profielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | De stroom die het RGB Icc-profiel bevat. |
| cmyk_icc_stream | _io.BufferedRandom | De stroom die het CMYK Icc-profiel bevat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en standaardprofielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en aangepaste profielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | De ARGB-kleuren. |
| rgb_icc_stream | _io.BufferedRandom | De stroom die het RGB Icc-profiel bevat. |
| cmyk_icc_stream | _io.BufferedRandom | De stroom die het CMYK Icc-profiel bevat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De CMYK-kleuren gepresenteerd als 32-bits geheel getallen. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Converteert RGB naar CMYK met aangepaste ICC-profielen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pixels | int | De RGB-kleuren weergegeven als 32-bits gehele getallen. |
| start_index | int | De startindex van de RGB-kleur. |
| lengte | int | Het aantal RGB-pixels om te converteren. |
| rgb_icc_stream | _io.BufferedRandom | De RGB-profielstroom. |
| cmyk_icc_stream | _io.BufferedRandom | De CMYK-profielstroom. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | De CMYK-kleuren weergegeven als een byte-array. |



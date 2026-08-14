---
title: "CmykColorHelper Klasse"
type: docs
weight: 640
url: /de/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Erstellt CMYK aus 32-Bit-Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| [get_c(cmyk)](#get_c_cmyk_2) | Liest den Cyan-Komponentenwert. |
| [get_k(cmyk)](#get_k_cmyk_3) | Liest den Schwarz-Komponentenwert. |
| [get_m(cmyk)](#get_m_cmyk_4) | Gibt den Magenta-Komponentenwert zurück. |
| [get_y(cmyk)](#get_y_cmyk_5) | Gibt den Gelb-Komponentenwert zurück. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | Die Umwandlung von CMYK-Farben zu ARGB-Farben. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Konvertiert RGB zu CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Erstellt CMYK aus 32-Bit-Cyan-, Magenta-, Gelb- und Schwarzwerten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cyan | int | Die Cyan-Komponente. Gültige Werte liegen zwischen 0 und 255. |
| magenta | int | Die Magenta-Komponente. Gültige Werte liegen zwischen 0 und 255. |
| gelb | int | Die Gelb-Komponente. Gültige Werte liegen zwischen 0 und 255. |
| schwarz | int | Die Schwarz-Komponente. Gültige Werte liegen zwischen 0 und 255. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Liest den Cyan-Komponentenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Cyan-Komponentenwert. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Liest den Schwarz-Komponentenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Schwarz-Komponentenwert. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Gibt den Magenta-Komponentenwert zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Magenta-Komponentenwert. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Gibt den Gelb-Komponentenwert zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der Gelb-Komponentenwert. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die ARGB-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc-Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB-Icc-Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int | Die CMYK-Pixel, dargestellt als 32-Bit-Ganzzahlwerte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc-Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB-Icc-Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int | Die ARGB-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Konvertiert RGB zu CMYK.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int | Die RGB-Farben, dargestellt als 32-Bit-Ganzzahlwerte. |
| start_index | int | Der Startindex der RGB-Farbe. |
| Länge | int | Die Anzahl der zu konvertierenden RGB-Pixel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Die CMYK-Farben, dargestellt als Byte-Array. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB-Icc-Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc-Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Die ARGB-Farben. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das RGB-Icc-Profil enthält. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das CMYK Icc-Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die CMYK-Farben dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels | int | Die RGB-Farben, dargestellt als 32-Bit-Ganzzahlwerte. |
| start_index | int | Der Startindex der RGB-Farbe. |
| Länge | int | Die Anzahl der zu konvertierenden RGB-Pixel. |
| rgb_icc_stream | _io.BufferedRandom | Der RGB-Profil-Stream. |
| cmyk_icc_stream | _io.BufferedRandom | Der CMYK-Profil-Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Die CMYK-Farben, dargestellt als Byte-Array. |



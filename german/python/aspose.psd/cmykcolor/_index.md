---
title: "CmykColor Klasse"
type: docs
weight: 630
url: /de/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initialisiert eine neue Instanz der CmykColor Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| c | byte | r | Gibt den Cyan-Komponentenwert dieser [Color](/psd/python-net/aspose.psd/color/) Struktur zurück. |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Gibt den leeren Wert zurück. |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob diese [Color](/psd/python-net/aspose.psd/color/) Struktur nicht initialisiert ist. |
| k | byte | r | Gibt den Schwarz-Komponentenwert dieser [Color](/psd/python-net/aspose.psd/color/) Struktur zurück. |
| m | byte | r | Gibt den Magenta-Komponentenwert dieser [Color](/psd/python-net/aspose.psd/color/) Struktur zurück. |
| y | byte | r | Gibt den Gelb-Komponentenwert dieser [Color](/psd/python-net/aspose.psd/color/) Struktur zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Erstellt eine [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) Struktur aus 32‑Bit Cyan-, Magenta-, Gelb- und Schwarzwerten.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Die Konvertierung von CMYKColor zu 32‑Bit ARGB Color mittels ICC-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | Der to-Wert. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initialisiert eine neue Instanz der CmykColor Klasse

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Erstellt eine [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) Struktur aus 32‑Bit Cyan-, Magenta-, Gelb- und Schwarzwerten.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Das [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu 32‑Bit ARGB Color mittels ICC-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das Array der 32‑Bit‑ARGB‑Farbe. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Das <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Die Konvertierung von 32‑Bit ARGB Color zu CMYKColor.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| argb_pixels | int | Die Pixel des 32‑Bit‑ARGB‑Formats. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Das <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Das Array der ARGB‑Farben. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Das Array der ARGB‑Farben. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Das [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das icc cmyk-Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das icc rgb-Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Das [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung mit Standardprofilen.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK-Format. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Das [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Die Konvertierung von CMYKColor zu Color mittels icc-Konvertierung.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK-Format. |
| cmyk_icc_stream | _io.BufferedRandom | Der Stream, der das icc cmyk-Profil enthält. |
| rgb_icc_stream | _io.BufferedRandom | Der Stream, der das icc rgb-Profil enthält. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Das [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

Der to-Wert.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long | Der int. |



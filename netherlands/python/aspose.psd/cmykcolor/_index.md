---
title: "CmykColor Klasse"
type: docs
weight: 630
url: /nl/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initialiseert een nieuw exemplaar van de CmykColor klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| c | byte | r | Haalt de cyaancomponentwaarde op van deze [Color](/psd/python-net/aspose.psd/color/) structuur. |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Haalt het lege op. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of deze [Color](/psd/python-net/aspose.psd/color/) structuur niet is geïnitialiseerd. |
| k | byte | r | Haalt de zwartcomponentwaarde op van deze [Color](/psd/python-net/aspose.psd/color/) structuur. |
| m | byte | r | Haalt de magentacomponentwaarde op van deze [Color](/psd/python-net/aspose.psd/color/) structuur. |
| y | byte | r | Haalt de geelcomponentwaarde op van deze [Color](/psd/python-net/aspose.psd/color/) structuur. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Maakt een [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) structuur aan vanuit 32-bit cyaan-, magenta-, geel- en zwartwaarden.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | De conversie van CMYKColor naar 32-bit ARGB Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | De conversie van 32-bit ARGB-kleur naar CMYKColor.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | De conversie van 32-bit ARGB-kleur naar CMYKColor.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | De conversie van CMYKColor naar Color met icc-conversie.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | De conversie van CMYKColor naar Color met icc-conversie.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | De to-waarde. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initialiseert een nieuw exemplaar van de CmykColor klasse

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Maakt een [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) structuur aan vanuit 32-bit cyaan-, magenta-, geel- en zwartwaarden.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | De [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

De conversie van CMYKColor naar 32-bit ARGB Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | De pixels van het type CMYKColor in CMYK-indeling. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De array van de 32-bit ARGB-kleur. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

De conversie van 32-bit ARGB-kleur naar CMYKColor.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | De <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

De conversie van 32-bit ARGB-kleur naar CMYKColor.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| argb_pixels | int | De pixels van 32-bit ARGB-indeling. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | De <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De array van de ARGB-kleuren. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | De pixels van het type CMYKColor in CMYK-indeling. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De array van de ARGB-kleuren. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

De conversie van CMYKColor naar Color met icc-conversie.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | De stream die het icc cmyk-profiel bevat. |
| rgb_icc_stream | _io.BufferedRandom | De stream die het icc rgb-profiel bevat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | De pixels van het type CMYKColor in CMYK-indeling. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

De conversie van CMYKColor naar Color met icc-conversie.<br/>            Deze methode is verouderd. Gebruik a.u.b. effectievere Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | De pixels van het type CMYKColor in CMYK-indeling. |
| cmyk_icc_stream | _io.BufferedRandom | De stream die het icc cmyk-profiel bevat. |
| rgb_icc_stream | _io.BufferedRandom | De stream die het icc rgb-profiel bevat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

De to-waarde.

**Returns**

| Type | Beschrijving |
| :- | :- |
| long | De int. |



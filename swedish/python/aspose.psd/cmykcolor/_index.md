---
title: "CmykColor-klass"
type: docs
weight: 630
url: /sv/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initierar en ny instans av CmykColor-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| c | byte | r | Hämtar cyan-komponentens värde för denna [Color](/psd/python-net/aspose.psd/color/) struktur. |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Hämtar den tomma. |
| is_empty | bool | r | Hämtar ett värde som indikerar om denna [Color](/psd/python-net/aspose.psd/color/) struktur är oinitierad. |
| k | byte | r | Hämtar svart-komponentens värde för denna [Color](/psd/python-net/aspose.psd/color/) struktur. |
| m | byte | r | Hämtar magenta-komponentens värde för denna [Color](/psd/python-net/aspose.psd/color/) struktur. |
| y | byte | r | Hämtar gul-komponentens värde för denna [Color](/psd/python-net/aspose.psd/color/) struktur. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Skapar en [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struktur från 32-bitars cyan-, magenta-, gul- och svartvärden.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Konverteringen från CMYKColor till 32-bitars ARGB Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Konverteringen från 32-bitars ARGB-färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Konverteringen från 32-bitars ARGB-färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | Tillvärdet. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initierar en ny instans av CmykColor-klassen

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Skapar en [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struktur från 32-bitars cyan-, magenta-, gul- och svartvärden.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Den [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Konverteringen från CMYKColor till 32-bitars ARGB Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Arrayen av 32-bitars ARGB-färg. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Konverteringen från 32-bitars ARGB-färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Den <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Konverteringen från 32-bitars ARGB-färg till CMYKColor.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_pixels | int | Pixlarna i 32-bitars ARGB-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Den <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Arrayen av ARGB-färger. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Arrayen av ARGB-färger. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Den [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc cmyk-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc rgb-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Den [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler.<br/>            Denna metod är föråldrad. Använd en mer effektiv [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK-format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Den [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Konverteringen från CMYKColor till Color med icc-konvertering.<br/>            Denna metod är föråldrad. Använd en mer effektiv Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK-format. |
| cmyk_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc cmyk-profilen. |
| rgb_icc_stream | _io.BufferedRandom | Strömmen som innehåller icc rgb-profilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Den [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

Tillvärdet.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long | Int-typen. |



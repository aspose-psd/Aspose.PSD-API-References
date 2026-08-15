---
title: "Clase CmykColor"
type: docs
weight: 630
url: /es/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Inicializa una nueva instancia de la clase CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| c | byte | r | Obtiene el valor del componente cian de esta estructura [Color](/psd/python-net/aspose.psd/color/). |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Obtiene el vacío. |
| is_empty | bool | r | Obtiene un valor que indica si esta estructura [Color](/psd/python-net/aspose.psd/color/) no está inicializada. |
| k | byte | r | Obtiene el valor del componente negro de esta estructura [Color](/psd/python-net/aspose.psd/color/). |
| m | byte | r | Obtiene el valor del componente magenta de esta estructura [Color](/psd/python-net/aspose.psd/color/). |
| y | byte | r | Obtiene el valor del componente amarillo de esta estructura [Color](/psd/python-net/aspose.psd/color/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Crea una estructura [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) a partir de valores de cian, magenta, amarillo y negro de 32 bits.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | El valor to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Inicializa una nueva instancia de la clase CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Crea una estructura [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) a partir de valores de cian, magenta, amarillo y negro de 32 bits.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | El [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

La conversión de CMYKColor a Color ARGB de 32 bits usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La matriz del color ARGB de 32 bits. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | El <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

La conversión de color ARGB de 32 bits a CMYKColor.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| argb_pixels | int | Los píxeles del formato ARGB de 32 bits. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | El <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | La matriz de los colores ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | La matriz de los colores ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | El [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc rgb. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | El [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

La conversión de CMYKColor a Color usando conversión icc con perfiles predeterminados.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | El [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversión de CMYKColor a Color usando conversión icc.<br/>            Este método está obsoleto. Por favor, use una versión más eficaz Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Los píxeles del tipo CMYKColor en formato CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | El flujo que contiene el perfil icc rgb. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | El [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

El valor to.

**Returns**

| Tipo | Descripción |
| :- | :- |
| long | El int. |



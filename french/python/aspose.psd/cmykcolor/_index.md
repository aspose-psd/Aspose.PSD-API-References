---
title: "Classe CmykColor"
type: docs
weight: 630
url: /fr/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Initialise une nouvelle instance de la classe CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| c | byte | r | Obtient la valeur du composant cyan de cette structure [Color](/psd/python-net/aspose.psd/color/). |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Obtient le vide. |
| is_empty | bool | r | Obtient une valeur indiquant si cette structure [Color](/psd/python-net/aspose.psd/color/) est non initialisée. |
| k | byte | r | Obtient la valeur du composant noir de cette structure [Color](/psd/python-net/aspose.psd/color/). |
| m | byte | r | Obtient la valeur du composant magenta de cette structure [Color](/psd/python-net/aspose.psd/color/). |
| y | byte | r | Obtient la valeur du composant jaune de cette structure [Color](/psd/python-net/aspose.psd/color/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Crée une structure [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) à partir de valeurs cyan, magenta, jaune et noir sur 32 bits.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | La conversion de CMYKColor vers une couleur ARGB 32 bits en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | La valeur to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Initialise une nouvelle instance de la classe CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Crée une structure [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) à partir de valeurs cyan, magenta, jaune et noir sur 32 bits.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

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
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Le [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

La conversion de CMYKColor vers une couleur ARGB 32 bits en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le tableau de la couleur ARGB 32 bits. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Le <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

La conversion d'une couleur ARGB 32 bits vers CMYKColor.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| argb_pixels | int | Les pixels du format ARGB 32 bits. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Le <see cref=\"T:Aspose:PSD:CmykColor[]\" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Le tableau des couleurs ARGB. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Le tableau des couleurs ARGB. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Le [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc rgb. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Le [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc avec les profils par défaut.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Le [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

La conversion de CMYKColor vers Color en utilisant la conversion icc.<br/>            Cette méthode est obsolète. Veuillez utiliser une version plus efficace de Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Les pixels de type CMYKColor au format CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Le flux contenant le profil icc rgb. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Le [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

La valeur to.

**Returns**

| Type | Description |
| :- | :- |
| long | L'entier. |



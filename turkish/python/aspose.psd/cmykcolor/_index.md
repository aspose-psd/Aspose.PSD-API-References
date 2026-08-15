---
title: "CmykColor Sınıfı"
type: docs
weight: 630
url: /tr/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | CmykColor sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| c | byte | r | Bu [Color](/psd/python-net/aspose.psd/color/) yapısının camgöbeği bileşen değerini alır. |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Boş değeri alır. |
| is_empty | bool | r | Bu [Color](/psd/python-net/aspose.psd/color/) yapısının başlatılmamış olup olmadığını gösteren bir değeri alır. |
| k | byte | r | Bu [Color](/psd/python-net/aspose.psd/color/) yapısının siyah bileşen değerini alır. |
| m | byte | r | Bu [Color](/psd/python-net/aspose.psd/color/) yapısının macenta bileşen değerini alır. |
| y | byte | r | Bu [Color](/psd/python-net/aspose.psd/color/) yapısının sarı bileşen değerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | 32 bit camgöbeği, macenta, sarı ve siyah değerlerinden bir [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) yapısı oluşturur.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan 32 bit ARGB Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | 32 bit ARGB renginden CMYKColor'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | 32 bit ARGB renginden CMYKColor'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | ICC dönüşümü kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) yöntemini kullanın. |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın. |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | ICC dönüşümü kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) yöntemini kullanın. |
| [to_value()](#to_value__11) | Bu to değeri. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

CmykColor sınıfının yeni bir örneğini başlatır

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

32 bit camgöbeği, macenta, sarı ve siyah değerlerinden bir [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) yapısı oluşturur.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| camgöbeği | int | Camgöbeği bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| macenta | int | Macenta bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| sarı | int | Sarı bileşeni. Geçerli değerler 0 ile 255 arasındadır. |
| siyah | int | Siyah bileşeni. Geçerli değerler 0 ile 255 arasındadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Bu [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan 32 bit ARGB Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | 32 bit ARGB renginin dizisi. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

32 bit ARGB renginden CMYKColor'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Bu <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

32 bit ARGB renginden CMYKColor'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argb_pixels | int | 32 bit ARGB formatındaki pikseller. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Bu <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB renklerinin dizisi. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB renklerinin dizisi. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Bu [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

ICC dönüşümü kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | ICC CMYK profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | ICC RGB profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Bu [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

ICC dönüşümü ve varsayılan profiller kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Bu [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

ICC dönüşümü kullanılarak CMYKColor'dan Color'a dönüşüm.<br/> Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) yöntemini kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK formatındaki CMYKColor tipinin pikselleri. |
| cmyk_icc_stream | _io.BufferedRandom | ICC CMYK profilini içeren akış. |
| rgb_icc_stream | _io.BufferedRandom | ICC RGB profilini içeren akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Bu [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

Bu to değeri.

**Returns**

| Tür | Açıklama |
| :- | :- |
| long | Bu int. |



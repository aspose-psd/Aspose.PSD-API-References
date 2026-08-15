---
title: "CmykColor Класс"
type: docs
weight: 630
url: /ru/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | Инициализирует новый экземпляр класса CmykColor |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| c | byte | r | Получает значение компонента циана этой структуры [Color](/psd/python-net/aspose.psd/color/). |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | Получает пустое. |
| is_empty | bool | r | Возвращает значение, указывающее, что эта структура [Color](/psd/python-net/aspose.psd/color/) не инициализирована. |
| k | byte | r | Получает значение компонента черного этой структуры [Color](/psd/python-net/aspose.psd/color/). |
| m | byte | r | Получает значение компонента пурпурного этой структуры [Color](/psd/python-net/aspose.psd/color/). |
| y | byte | r | Получает значение компонента желтого этой структуры [Color](/psd/python-net/aspose.psd/color/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | Создает структуру [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) из 32‑битных значений циана, пурпурного, желтого и черного.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | Преобразование из CMYKColor в 32‑битный ARGB Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/). |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | Преобразование из CMYKColor в Color с использованием ICC‑преобразования.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom). |
| [to_value()](#to_value__11) | Значение to. |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

Инициализирует новый экземпляр класса CmykColor

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

Создает структуру [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) из 32‑битных значений циана, пурпурного, желтого и черного.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| циан | int | Компонент циана. Допустимые значения от 0 до 255. |
| пурпурный | int | Компонент мадженты. Допустимые значения от 0 до 255. |
| жёлтый | int | Компонент желтого. Допустимые значения от 0 до 255. |
| чёрный | int | Компонент черного. Допустимые значения от 0 до 255. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Элемент [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

Преобразование из CMYKColor в 32‑битный ARGB Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив 32‑битного ARGB цвета. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | Элемент <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

Преобразование из 32‑битного ARGB color в CMYKColor.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int | Пиксели в формате 32‑битного ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Элемент <see cref="T:Aspose:PSD:CmykColor[]" />. |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Массив ARGB цветов. |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Массив ARGB цветов. |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Массив [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из CMYKColor в Color с использованием ICC‑преобразования.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль icc rgb. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Массив [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

Преобразование из CMYKColor в Color с использованием ICC‑преобразования с профилями по умолчанию.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Массив [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование из CMYKColor в Color с использованием ICC‑преобразования.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Пиксели типа CMYKColor в формате CMYK. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль icc cmyk. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль icc rgb. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Массив [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

Значение to.

**Returns**

| Тип | Описание |
| :- | :- |
| long | Тип int. |



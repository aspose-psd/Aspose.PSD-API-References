---
title: "CmykColorHelper Класс"
type: docs
weight: 640
url: /ru/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | Создает CMYK из 32-битных значений циана, магенты, желтого и черного. |
| [get_c(cmyk)](#get_c_cmyk_2) | Получает значение компоненты циана. |
| [get_k(cmyk)](#get_k_cmyk_3) | Получает значение компоненты черного. |
| [get_m(cmyk)](#get_m_cmyk_4) | Получает значение компоненты магенты. |
| [get_y(cmyk)](#get_y_cmyk_5) | Получает значение компоненты желтого. |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | Преобразование цветов CMYK в цвета ARGB. |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | Преобразование цветов CMYK в цвета ARGB. |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | Преобразование цветов CMYK в цвета ARGB. |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования с профилями по умолчанию. |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | Преобразование цветов CMYK в цвета ARGB с использованием Icc‑конверсии с пользовательскими профилями. |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования с профилями по умолчанию. |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | Преобразование цветов CMYK в цвета ARGB с использованием Icc‑конверсии с пользовательскими профилями. |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | Преобразование цветов ARGB в цвета CMYK. |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | Преобразование цветов ARGB в цвета CMYK. |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | Преобразование цветов ARGB в цвета CMYK. |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | Преобразование цветов ARGB в цвета CMYK. |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | Преобразует RGB в CMYK. |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с профилями по умолчанию. |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с пользовательскими профилями. |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с профилями по умолчанию. |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с пользовательскими профилями. |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | Преобразует RGB в CMYK с использованием пользовательских ICC‑профилей. |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

Создает CMYK из 32-битных значений циана, магенты, желтого и черного.

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
| int | Цвет CMYK, представленный как 32‑битное целое значение. |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

Получает значение компоненты циана.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целое значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение компонента циана. |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

Получает значение компоненты черного.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целое значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение чёрного компонента. |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

Получает значение компоненты магенты.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целое значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение пурпурного компонента. |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

Получает значение компоненты желтого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk | int | Цвет CMYK, представленный как 32‑битное целое значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение жёлтого компонента. |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

Преобразование цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвета ARGB. |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

Преобразование цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Цвета ARGB. |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

Преобразование цветов CMYK в цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета ARGB, представленные как 32‑битные целочисленные значения. |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования с профилями по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвета ARGB. |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование цветов CMYK в цвета ARGB с использованием Icc‑конверсии с пользовательскими профилями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль CMYK Icc. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль RGB Icc. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвета ARGB. |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

Преобразование цветов CMYK в цвета ARGB с использованием ICC‑преобразования с профилями по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int | Пиксели CMYK, представленные как 32‑битные целочисленные значения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Цвета ARGB. |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

Преобразование цветов CMYK в цвета ARGB с использованием Icc‑конверсии с пользовательскими профилями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cmyk_pixels | int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль CMYK Icc. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль RGB Icc. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Цвета ARGB. |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

Преобразование цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

Преобразование цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int | Цвета ARGB, представленные как 32‑битные целочисленные значения. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

Преобразование цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

Преобразование цветов ARGB в цвета CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

Преобразует RGB в CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_pixels | int | RGB‑цвета, представленные в виде 32‑битных целочисленных значений. |
| start_index | int | Начальный индекс RGB‑цвета. |
| длина | int | Количество RGB‑пикселей для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | CMYK‑цвета, представленные в виде массива байтов. |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с профилями по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с пользовательскими профилями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль RGB Icc. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль CMYK Icc. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с профилями по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Цвета ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразование цветов ARGB в цвета CMYK с использованием Icc‑конверсии с пользовательскими профилями.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Цвета ARGB. |
| rgb_icc_stream | _io.BufferedRandom | Поток, содержащий профиль RGB Icc. |
| cmyk_icc_stream | _io.BufferedRandom | Поток, содержащий профиль CMYK Icc. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Цвета CMYK, представленные как 32‑битные целочисленные значения. |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

Преобразует RGB в CMYK с использованием пользовательских ICC‑профилей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels | int | RGB‑цвета, представленные в виде 32‑битных целочисленных значений. |
| start_index | int | Начальный индекс RGB‑цвета. |
| длина | int | Количество RGB‑пикселей для преобразования. |
| rgb_icc_stream | _io.BufferedRandom | Поток профиля RGB. |
| cmyk_icc_stream | _io.BufferedRandom | Поток профиля CMYK. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | CMYK‑цвета, представленные в виде массива байтов. |



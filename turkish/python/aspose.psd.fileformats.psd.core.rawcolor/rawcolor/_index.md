---
title: "RawColor Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | Yeni bir [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) sınıfı örneği başlatır. |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | Önceden tanımlı renk modlarını kullanarak piksel veri formatından yeni bir [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| color_mode | short | r/w | Rengin takip edeceği mod. |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | Rengin bileşenlerini alır. Her bileşen ayrı bir kanaldır ve popüler olmayan<br/>            renk şemasını kullanıyorsanız, her kanalla ayrı ayrı çalışmak daha iyidir. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | Rengi mümkünse int olarak alır. |
| [get_as_long()](#get_as_long__2) | Rengi mümkünse long olarak alır. |
| [get_bit_depth()](#get_bit_depth__3) | Raw Color'ın bit derinliğini alır. <br/>            Örneğin, kanal/bileşen başına 8 bit olan ARGB renk için 32'dir<br/>            Kanal/bileşen başına 16 bit olan tam ARGB renk için 64'tür.<br/>            Bit derinliği, kanalların bit derinliklerinin toplamından elde edilir. <br/>            Farklı kanalların farklı bit derinliklerine sahip olması durumunda mümkündür. |
| [get_color_mode_name()](#get_color_mode_name__4) | Renk modunun adını alır. Renk modu adı, kanallar/bileşen adlarından oluşur. |
| [set_as_int(value)](#set_as_int_value_5) | Mümkünse int argümanından tüm kanallara veri ayarlar. |
| [set_as_long(value)](#set_as_long_value_6) | Mümkünse int argümanından tüm kanallara veri ayarlar. |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

Yeni bir [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | Özel renk bileşenleri. |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

Önceden tanımlı renk modlarını kullanarak piksel veri formatından yeni bir [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Piksel veri formatı. |
| color_mode | short | Rengin takip edeceği mod. |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

Rengi mümkünse int olarak alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Kanalların verisi Int içinde depolanır. |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

Rengi mümkünse long olarak alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| long | Kanalların verisi Int içinde depolanır. |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Raw Color'ın bit derinliğini alır. <br/>            Örneğin, kanal/bileşen başına 8 bit olan ARGB renk için 32'dir<br/>            Kanal/bileşen başına 16 bit olan tam ARGB renk için 64'tür.<br/>            Bit derinliği, kanalların bit derinliklerinin toplamından elde edilir. <br/>            Farklı kanalların farklı bit derinliklerine sahip olması durumunda mümkündür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Tüm kanalların bit derinliklerinin toplamı. |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

Renk modunun adını alır. Renk modu adı, kanallar/bileşen adlarından oluşur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Renk modu adı içeren dize. |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

Mümkünse int argümanından tüm kanallara veri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | int | Bileşen verisini içeren int değeri. |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

Mümkünse int argümanından tüm kanallara veri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | long | Bileşen verisini içeren int değeri. |


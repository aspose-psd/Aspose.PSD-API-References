---
title: "ColorRangeHsl Sınıfı"
type: docs
weight: 180
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Yeni bir [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) sınıfının yeni bir örneğini başlatır. |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Yeni bir [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| hue | short | r/w | hue değerini alır veya ayarlar. |
| left_border | short | r/w | Sol kenarı alır veya ayarlar. |
| lightness | short | r/w | lightness değerini alır veya ayarlar. |
| most_left_border | short | r/w | En sol kenarı alır veya ayarlar. |
| most_right_border | short | r/w | En sağ kenarı alır veya ayarlar. |
| right_border | short | r/w | Sağ kenarı alır veya ayarlar. |
| doygunluk | short | r/w | Doygunluğu alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Aralık katsayısını alır. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Tonun büyük aralıkta olup olmadığını belirler. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Tonun küçük aralıkta olup olmadığını belirler. |
| [save(stream_container)](#save_stream_container_4) | Verileri belirtilen akış konteynerine kaydeder. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Yeni bir [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) sınıfının yeni bir örneğini başlatır.

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Yeni bir [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Renk aralığı verisi. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Aralık katsayısını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| hue | double | Ton değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Doygunluk aralık katsayısı. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Tonun büyük aralıkta olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| hue | double | Ton değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer ton büyük aralıkta ise; aksi takdirde, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Tonun küçük aralıkta olup olmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| hue | double | Ton değeri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer ton küçük aralıkta ise; aksi takdirde, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Verileri belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |


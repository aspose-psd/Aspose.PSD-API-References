---
title: "PhflResourceVersion3 Sınıfı"
type: docs
weight: 810
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion3

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PhflResourceVersion3()](#PhflResourceVersion3__1) | [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) sınıfının yeni bir örneğini başlatır. |
| [PhflResourceVersion3(data)](#PhflResourceVersion3_data_2) | [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB'ye özgü kaynak imzası. |
| RESOURCE_SIGNATURE [static] | int | r | Ortak kaynak imzası. |
| TYPE_TOOL_KEY [static] | int | r | Tür aracı bilgi anahtarı. |
| color_space | short | r | Renk uzayını alır. |
| color_x | float | r/w | X rengini alır veya ayarlar. |
| color_y | float | r/w | Y rengini alır veya ayarlar. |
| color_z | float | r/w | Z rengini alır veya ayarlar. |
| density | int | r/w | Yoğunluğu alır veya ayarlar. |
| key | int | r | Katman kaynağı anahtarını alır. |
| uzunluk | int | r | Katman kaynağı uzunluğunu bayt olarak alır. |
| preserve_luminosity | bool | r/w | Bir değeri alır veya ayarlar ve [preserve luminosity] olup olmadığını gösterir. |
| psd_version | int | r | Katman kaynağı için gereken minimum psd sürümünü alır. 0, kısıtlama olmadığını gösterir. |
| signature | int | r | İmzayı alır. |
| version | short | r | Sürümü alır. Varsayılan 2 veya 3'tür. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Rengi al. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | RGB rengini ayarlar. |


### Constructor: PhflResourceVersion3() {#PhflResourceVersion3__1}


```
 PhflResourceVersion3() 
```

[PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) sınıfının yeni bir örneğini başlatır.

### Constructor: PhflResourceVersion3(data) {#PhflResourceVersion3_data_2}


```
 PhflResourceVersion3(data) 
```

[PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Kaynağın verisi. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Rengi al.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB rengi |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psd_version | int | PSD sürümü. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

RGB rengini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Renk. |


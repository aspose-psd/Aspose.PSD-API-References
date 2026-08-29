---
title: "PattResourceData Sınıfı"
type: docs
weight: 780
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | PattResourceData sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| yükseklik | short | r | Yüksekliği alır. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Görüntü modunu alır. |
| uzunluk | int | r | Desenin uzunluğunu alır. |
| name | string | r/w | Adı alır veya ayarlar. |
| pattern_data | int | r | Desen verisini alır. |
| pattern_id | string | r/w | Desen tanımlayıcısını alır veya ayarlar. |
| version | int | r | Sürümü alır. |
| width | short | r | Genişliği alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Desen verisini kaydeder. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Deseni ayarlar. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

PattResourceData sınıfının yeni bir örneğini başlatır

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Desen verisini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Deseni ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| piksel | int | Pikseller. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sınırlar. |


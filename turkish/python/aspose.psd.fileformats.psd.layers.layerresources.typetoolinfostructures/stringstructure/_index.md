---
title: "StringStructure Sınıfı"
type: docs
weight: 160
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Summary:** The string structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.StringStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [StringStructure(key_name)](#StringStructure_key_name_1) | Yeni bir [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) sınıfı örneği oluşturur. |
| [StringStructure(key_name, value)](#StringStructure_key_name_value_2) | Değer ile yeni bir [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) sınıfı örneği oluşturur. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Yapı anahtarını tanımlar. |
| key | int | r | Anahtarı alır. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Anahtar adını alır veya ayarlar. |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır. |
| değer | string | r/w | Değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Başlık uzunluğunu alır. |
| [save(stream_container)](#save_stream_container_2) | Yapıyı belirtilen akış konteynerine kaydeder. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Yapıyı belirtilen akış konteynerine kaydeder. |


### Constructor: StringStructure(key_name) {#StringStructure_key_name_1}


```
 StringStructure(key_name) 
```

Yeni bir [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) sınıfı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Anahtar adı. |

### Constructor: StringStructure(key_name, value) {#StringStructure_key_name_value_2}


```
 StringStructure(key_name, value) 
```

Değer ile yeni bir [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) sınıfı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Anahtar adı. |
| değer | string | Değer. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Başlık uzunluğunu alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Başlık uzunluğu |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Yapıyı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Yapıyı belirtilen akış konteynerine kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Akış konteyneri. |


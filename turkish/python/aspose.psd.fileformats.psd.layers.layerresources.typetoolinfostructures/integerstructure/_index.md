---
title: "IntegerStructure Sınıfı"
type: docs
weight: 80
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/
---

**Summary:** The integer structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.IntegerStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [IntegerStructure(key_name)](#IntegerStructure_key_name_1) | Yeni bir [IntegerStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/) sınıfı örneği oluşturur. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Tam sayı yapı anahtarı. |
| key | int | r | Anahtarı alır. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Anahtar adını alır veya ayarlar. |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır. |
| değer | int | r/w | Tam sayı değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Başlık uzunluğunu alır. |
| [save(stream_container)](#save_stream_container_2) | Yapıyı belirtilen akış konteynerine kaydeder. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Yapıyı belirtilen akış konteynerine kaydeder. |


### Constructor: IntegerStructure(key_name) {#IntegerStructure_key_name_1}


```
 IntegerStructure(key_name) 
```

Yeni bir [IntegerStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/integerstructure/) sınıfı örneği oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Anahtar adı. |

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


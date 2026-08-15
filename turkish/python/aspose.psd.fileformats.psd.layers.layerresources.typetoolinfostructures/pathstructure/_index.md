---
title: "PathStructure Sınıfı"
type: docs
weight: 120
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---

**Summary:** The path structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.PathStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PathStructure(key_name)](#PathStructure_key_name_1) | Yeni bir [PathStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Yapı anahtarını tanımlar. |
| key | int | r | Yapı anahtarını alır. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Anahtar adını alır veya ayarlar. |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır. |
| yol | string | r/w | Yolu alır veya ayarlar. |
| önek | string | r/w | Yol önekini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Başlık uzunluğunu alır. |
| [save(stream_container)](#save_stream_container_2) | Yapıyı belirtilen akış konteynerine kaydeder. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Yapıyı belirtilen akış konteynerine kaydeder. |


### Constructor: PathStructure(key_name) {#PathStructure_key_name_1}


```
 PathStructure(key_name) 
```

Yeni bir [PathStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/) sınıfının örneğini başlatır.

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


---
title: "EnumeratedDescriptorStructure Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/
---

**Summary:** The enumerated descriptor structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedDescriptorStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EnumeratedDescriptorStructure(key_name, type_id, enum_name)](#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1) | Yeni bir [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Numaralandırılmış tanımlayıcı anahtarı. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Enum adını alır veya ayarlar. |
| key | int | r | Anahtarı alır. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Anahtar adını alır veya ayarlar. |
| length | int | r | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Tür kimliğini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Başlık uzunluğunu alır. |
| [save(stream_container)](#save_stream_container_2) | Verileri kaydeder. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Yapıyı belirtilen akış konteynerine kaydeder. |


### Constructor: EnumeratedDescriptorStructure(key_name, type_id, enum_name) {#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1}


```
 EnumeratedDescriptorStructure(key_name, type_id, enum_name) 
```

Yeni bir [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Anahtar adı. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Tür kimliği. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Enum adı. |

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

Verileri kaydeder.

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


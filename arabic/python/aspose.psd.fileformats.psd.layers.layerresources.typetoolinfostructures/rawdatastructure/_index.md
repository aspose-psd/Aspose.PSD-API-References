---
title: "فئة RawDataStructure"
type: docs
weight: 140
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure/
---

**Summary:** The raw data structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.RawDataStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [RawDataStructure(key_name)](#RawDataStructure_key_name_1) | يقوم بإنشاء نسخة جديدة من الفئة [RawDataStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | يحدد مفتاح البنية. |
| البيانات | byte | r/w | يحصل أو يعيّن البيانات. |
| key | int | r | يحصل على المفتاح. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن اسم المفتاح. |
| length | int | r | يحصل على طول [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) بالبايت. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | يحصل على طول الترويسة. |
| [save(stream_container)](#save_stream_container_2) | يحفظ البنية في حاوية الدفق المحددة. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | يحفظ البنية في حاوية الدفق المحددة. |


### Constructor: RawDataStructure(key_name) {#RawDataStructure_key_name_1}


```
 RawDataStructure(key_name) 
```

يقوم بإنشاء نسخة جديدة من الفئة [RawDataStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | اسم المفتاح. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

يحصل على طول الترويسة.

**Returns**

| النوع | الوصف |
| :- | :- |
| int | طول الرأس |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

يحفظ البنية في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

يحفظ البنية في حاوية الدفق المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | حاوية الدفق. |


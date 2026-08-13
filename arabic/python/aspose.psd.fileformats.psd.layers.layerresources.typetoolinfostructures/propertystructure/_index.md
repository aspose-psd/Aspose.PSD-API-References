---
title: "فئة PropertyStructure"
type: docs
weight: 130
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/
---

**Summary:** The property structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.PropertyStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PropertyStructure(key_name, class_id, key_id)](#PropertyStructure_key_name_class_id_key_id_1) | ينشئ مثلاً جديداً من الفئة [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | يحدد مفتاح البنية. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن معرف الفئة. |
| class_name | string | r/w | يحصل أو يعيّن اسم الفئة. |
| key | int | r | يحصل على مفتاح البنية. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن معرف المفتاح. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن اسم المفتاح. |
| length | int | r | يحصل على طول [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) بالبايت. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | يحصل على طول الترويسة. |
| [save(stream_container)](#save_stream_container_2) | يحفظ البنية في حاوية الدفق المحددة. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | يحفظ البنية في حاوية الدفق المحددة. |


### Constructor: PropertyStructure(key_name, class_id, key_id) {#PropertyStructure_key_name_class_id_key_id_1}


```
 PropertyStructure(key_name, class_id, key_id) 
```

ينشئ مثلاً جديداً من الفئة [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | اسم المفتاح. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | معرّف الفئة. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | معرّف المفتاح. |

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


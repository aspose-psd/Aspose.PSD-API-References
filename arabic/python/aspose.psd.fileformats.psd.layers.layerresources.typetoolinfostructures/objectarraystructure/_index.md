---
title: "ObjectArrayStructure فئة"
type: docs
weight: 100
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | ينشئ مثيلاً جديداً من الفئة [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | ينشئ مثيلاً جديداً من الفئة [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | يحدد مفتاح بنية 'ObAr'. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يضبط معرف فئة مصفوفة الكائن. |
| class_name | string | r/w | يحصل أو يضبط اسم فئة مصفوفة الكائن. |
| key | int | r | يحصل على مفتاح بنية مصفوفة الكائن. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن اسم المفتاح. |
| length | int | r | يحصل على طول [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) بالبايت. |
| structure_count | int | r | يحصل على عدد البنى الفرعية لمصفوفة الكائن. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | يحصل أو يعيّن نسخة من مصفوفة البنى. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | يحصل على طول الترويسة. |
| [save(stream_container)](#save_stream_container_2) | يحفظ البنية في حاوية الدفق المحددة. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | يحفظ البنية في حاوية الدفق المحددة. |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

ينشئ مثيلاً جديداً من الفئة [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key | int | المفتاح الصحيح. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | اسم المفتاح. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | معرّف الفئة. |
| class_name | string | اسم الفئة. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | البنى. |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

ينشئ مثيلاً جديداً من الفئة [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key_name | string | اسم المفتاح. |
| class_id_name | string | اسم معرّف الفئة. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | البنى. |

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


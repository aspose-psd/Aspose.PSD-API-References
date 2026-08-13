---
title: "فئة StringStructure"
type: docs
weight: 160
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/
---

**Summary:** The string structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.StringStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [StringStructure(key_name)](#StringStructure_key_name_1) | ينشئ مثيلاً جديدًا من الفئة [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) . |
| [StringStructure(key_name, value)](#StringStructure_key_name_value_2) | ينشئ مثيلاً جديدًا من الفئة [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) مع القيمة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | يحدد مفتاح البنية. |
| key | int | r | يحصل على المفتاح. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | يحصل أو يعيّن اسم المفتاح. |
| length | int | r | يحصل على طول [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) بالبايت. |
| قيمة | string | r/w | يحصل أو يعيّن القيمة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | يحصل على طول الترويسة. |
| [save(stream_container)](#save_stream_container_2) | يحفظ البنية في حاوية الدفق المحددة. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | يحفظ البنية في حاوية الدفق المحددة. |


### Constructor: StringStructure(key_name) {#StringStructure_key_name_1}


```
 StringStructure(key_name) 
```

ينشئ مثيلاً جديدًا من الفئة [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) .

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | اسم المفتاح. |

### Constructor: StringStructure(key_name, value) {#StringStructure_key_name_value_2}


```
 StringStructure(key_name, value) 
```

ينشئ مثيلاً جديدًا من الفئة [StringStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/) مع القيمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | اسم المفتاح. |
| قيمة | string | القيمة. |

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


---
title: "فئة SmartObjectProvider"
type: docs
weight: 1940
url: /ar/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | يقوم بتحويل الطبقات إلى كائن ذكي مدمج. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | يقوم بتحويل الطبقات إلى كائن ذكي مدمج. |
| embed_all_linked() | يدمج جميع الكائنات الذكية المرتبطة في الصورة. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | ينشئ طبقة كائن ذكي جديدة عن طريق نسخ الطبقة المصدر. |
| update_all_modified_content() | يقوم بتحديث محتوى جميع الكائنات الذكية المعدلة في الصورة. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

يقوم بتحويل الطبقات إلى كائن ذكي مدمج.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer_numbers | int | أرقام الطبقة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | مثيل [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) تم إنشاؤه. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

يقوم بتحويل الطبقات إلى كائن ذكي مدمج.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | الطبقات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | مثيل [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) تم إنشاؤه. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

ينشئ طبقة كائن ذكي جديدة عن طريق نسخ الطبقة المصدر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | طبقة المصدر. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | مثيل [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) المستنسخ. |



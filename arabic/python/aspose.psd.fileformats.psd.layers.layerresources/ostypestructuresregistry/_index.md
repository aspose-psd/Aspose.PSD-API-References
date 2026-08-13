---
title: "فئة OSTypeStructuresRegistry"
type: docs
weight: 720
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | يحصل على الوصفيات المسجلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | يحصل على أول وصف فاتح مدعوم. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | يحصل على أول وصيف مدعوم بناءً على اسم النوع الخاص به. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | يقوم بتحميل [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) باستخدام أول مُفتاح تم العثور عليه مناسب للمحدد <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | يسجل الفاتح. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | يلغي تسجيل الفاتح. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

يحصل على أول وصف فاتح مدعوم.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | وصف محمل موارد الطبقة أو null إذا لم يكن هناك وصف محمل مدعوم لهذا التدفق. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

يحصل على أول وصيف مدعوم بناءً على اسم النوع الخاص به.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| descriptor_type_name | string | اسم نوع الوصف. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | الوصف الأول للفاتح الموجود أو null إذا لم يتم العثور على مثل هذا الوصف. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

يقوم بتحميل [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) باستخدام أول مُفتاح تم العثور عليه مناسب للمحدد <paramref name="stream" />.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | المورد المحمَّل [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) أو null إذا لم يتم العثور على فاتح. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

يسجل الفاتح.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | وصف الفاتح لتسجيله. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

يلغي تسجيل الفاتح.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | وصف الفاتح لإلغاء تسجيله. |


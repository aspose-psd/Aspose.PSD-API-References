---
title: "فئة LayerResourcesRegistry"
type: docs
weight: 1010
url: /ar/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | يحصل على الوصفيات المسجلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | يحصل على أول وصف فاتح مدعوم. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | يحصل على أول وصيف مدعوم بناءً على اسم النوع الخاص به. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | يقوم بتحميل [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) باستخدام أول فاتح تم العثور عليه مناسب للمحدد <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | يسجل الفاتح. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | يلغي تسجيل الفاتح. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

يحصل على أول وصف فاتح مدعوم.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |
| psd_version | int | إصدار PSD. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | وصف محمل موارد الطبقة أو null إذا لم يكن هناك وصف محمل مدعوم لهذا التدفق. |


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | الوصف الأول للفاتح الموجود أو null إذا لم يتم العثور على مثل هذا الوصف. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

يقوم بتحميل [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) باستخدام أول فاتح تم العثور عليه مناسب للمحدد <paramref name="stream" />.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |
| psd_version | int | إصدار PSD. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | المورد المحمَّل [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) أو null إذا لم يتم العثور على فاتح. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

يسجل الفاتح.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | وصف الفاتح لتسجيله. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

يلغي تسجيل الفاتح.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | وصف الفاتح لإلغاء تسجيله. |


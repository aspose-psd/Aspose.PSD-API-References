---
title: "فئة ImageLoadersRegistry"
type: docs
weight: 2260
url: /ar/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | يحصل على الوصفيات المسجلة. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على صيغ تحميل الصور المسجلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | ينشئ أول محمل تم العثور عليه مناسب للـ <paramref name="stream" /> المحدد وبشكل اختياري الـ <paramref name="loadOptions" />. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | يحصل على أول وصف مدعوم تم العثور عليه مناسب للـ <paramref name="stream" /> المحدد وبشكل اختياري الـ <paramref name="loadOptions" />. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | يحصل على أول صيغة ملف مدعومة حسب اسم النوع الخاص بها. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | يحصل على أول وصيف مدعوم بناءً على اسم النوع الخاص به. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | يسجل وصف محمل الصورة المحدد. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | يسجل المحمل. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | يلغي تسجيل المحمل. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

ينشئ أول محمل تم العثور عليه مناسب للـ <paramref name="stream" /> المحدد وبشكل اختياري الـ <paramref name="loadOptions" />.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | المحمل الذي يدعم الـ <paramref name="stream" /> و <paramref name="loadOptions" /> المحددين أو null إذا لم يتم العثور على مثل هذا المحمل. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

يحصل على أول وصف مدعوم تم العثور عليه مناسب للـ <paramref name="stream" /> المحدد وبشكل اختياري الـ <paramref name="loadOptions" />.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | وصف المحمل الذي يدعم الـ <paramref name="stream" /> و <paramref name="loadOptions" /> المحددين أو null إذا لم يتم العثور على مثل هذا الوصف. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

يحصل على أول صيغة ملف مدعومة حسب اسم النوع الخاص بها.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | صيغة ملف الوصف المدعومة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | وصف المحمل الأول الذي تم العثور عليه أو null إذا لم يتم العثور على مثل هذا الوصف. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


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
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | وصف المحمل الأول الذي تم العثور عليه أو null إذا لم يتم العثور على مثل هذا الوصف. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

يسجل وصف محمل الصورة المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | وصف محمل الصورة. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

يسجل المحمل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | وصف المحمل للتسجيل. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

يلغي تسجيل المحمل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | وصف المحمل لإلغاء التسجيل. |


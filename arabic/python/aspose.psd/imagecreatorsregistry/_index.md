---
title: "فئة ImageCreatorsRegistry"
type: docs
weight: 2210
url: /ar/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | يحصل على الوصفيات المسجلة. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على صيغ إنشاء الصور المسجلة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | ينشئ أول مُنشئ تم العثور عليه مناسب للمحدد. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | يحصل على أول موصّف مدعوم مناسب للمحدد. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | يسجّل موصّف منشئ الصورة المحدد. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | يسجّل المنشئ. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | يلغي تسجيل المنشئ. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

ينشئ أول مُنشئ تم العثور عليه مناسب للمحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الصورة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | المنشئ الذي يدعم المحدد أو null إذا لم يُعثر على مثل هذا المنشئ. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

يحصل على أول موصّف مدعوم مناسب للمحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الصورة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | موصّف المنشئ الذي يدعم المحدد أو null إذا لم يُعثر على مثل هذا الموصّف. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

يسجّل موصّف منشئ الصورة المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | موصّف منشئ الصورة. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

يسجّل المنشئ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | موصّف المنشئ لتسجيله. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

يلغي تسجيل المنشئ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | موصّف المنشئ. |


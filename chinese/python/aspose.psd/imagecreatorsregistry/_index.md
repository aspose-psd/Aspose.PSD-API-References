---
title: "ImageCreatorsRegistry 类"
type: docs
weight: 2210
url: /zh/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | 获取已注册的描述符。 |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取已注册的图像创建格式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | 创建第一个找到的适用于指定条件的创建器。 |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | 获取第一个找到的适用于指定条件的受支持描述符。 |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | 注册指定的图像创建器描述符。 |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | 注册该创建器。 |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | 注销该创建器。 |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

创建第一个找到的适用于指定条件的创建器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 图像选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | 支持指定条件的创建器，如果未找到则为 null。 |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

获取第一个找到的适用于指定条件的受支持描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 图像选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 支持指定条件的创建器描述符，如果未找到则为 null。 |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

注册指定的图像创建器描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 图像创建器描述符。 |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

注册该创建器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 用于注册的创建者描述符。 |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

注销该创建器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | 创建者描述符。 |


---
title: "ImageLoadersRegistry 类"
type: docs
weight: 2260
url: /zh/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | 获取已注册的描述符。 |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取已注册的图像加载格式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | 创建第一个适用于指定 <paramref name="stream" /> 且可选的 <paramref name="loadOptions" /> 的加载器。 |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | 获取第一个适用于指定 <paramref name="stream" /> 且可选的 <paramref name="loadOptions" /> 的受支持描述符。 |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | 通过类型名称获取第一个受支持的文件格式。 |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | 根据类型名称获取第一个受支持的描述符。 |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | 注册指定的图像加载器描述符。 |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | 注册加载器。 |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | 注销加载器。 |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

创建第一个适用于指定 <paramref name="stream" /> 且可选的 <paramref name="loadOptions" /> 的加载器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 流。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | 支持指定 <paramref name="stream" /> 和 <paramref name="loadOptions" /> 的加载器，如果未找到则为 null。 |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

获取第一个适用于指定 <paramref name="stream" /> 且可选的 <paramref name="loadOptions" /> 的受支持描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 流。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 支持指定 <paramref name="stream" /> 和 <paramref name="loadOptions" /> 的加载器描述符，如果未找到则为 null。 |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

通过类型名称获取第一个受支持的文件格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | 受支持的描述符文件格式。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 第一个找到的加载器描述符，如果未找到则为 null。 |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

根据类型名称获取第一个受支持的描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| descriptor_type_name | 字符串 | 描述符类型名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 第一个找到的加载器描述符，如果未找到则为 null。 |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

注册指定的图像加载器描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 图像加载器描述符。 |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

注册加载器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 要注册的加载器描述符。 |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

注销加载器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | 要注销的加载器描述符。 |


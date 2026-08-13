---
title: "ImageExportersRegistry 类"
type: docs
weight: 2230
url: /zh/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | 获取已注册的导出器描述符。 |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取已注册的导出格式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | 创建第一个找到的、适用于指定保存选项和图像的导出器。 |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | 获取第一个找到的、适用于指定保存选项和图像的受支持描述符。 |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | 注册指定的图像导出器描述符。 |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | 注册导出器。 |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | 注销导出器。 |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

创建第一个找到的、适用于指定保存选项和图像的导出器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要导出的图像。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 用于导出的保存选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | 支持指定图像和保存选项的导出器，如果未找到此类导出器则为 null。 |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

获取第一个找到的、适用于指定保存选项和图像的受支持描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要导出的图像。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 支持指定图像和保存选项的导出器描述符，如果未找到此类描述符则为 null。 |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

注册指定的图像导出器描述符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 图像导出器描述符。 |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

注册导出器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 要注册的导出器描述符。 |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

注销导出器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | 要注销的导出器描述符。 |


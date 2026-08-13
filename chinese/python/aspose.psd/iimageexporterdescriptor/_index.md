---
title: "IImageExporterDescriptor 类"
type: docs
weight: 1800
url: /zh/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取受支持的格式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | 确定图像导出器是否可以将指定的图像导出为保存选项指定的图像格式。 |
| [create_instance()](#create_instance__2) | 创建一个新的导出器实例。 |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

确定图像导出器是否可以将指定的图像导出为保存选项指定的图像格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 要导出的图像。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项基类。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>True</c> 如果此描述符创建的导出器可以将指定的图像导出为指定的文件格式；否则为 <c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

创建一个新的导出器实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | 一个新的导出器实例。 |



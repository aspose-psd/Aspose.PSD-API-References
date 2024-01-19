---
title: IImageExporterDescriptor Class
type: docs
weight: 1740
url: /python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 23.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Gets the supported format. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Determines whether image exporter can export the specified image to the specified image format specified by save options. |
| [create_instance()](#create_instance__2) | Creates a new exporter instance. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Determines whether image exporter can export the specified image to the specified image format specified by save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to export. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The options base. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> if exporter created by this descriptor can export the specified image to the specified file format; otherwise, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Creates a new exporter instance.

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | A new exporter instance. |



---
title: ImageExportersRegistry Class
type: docs
weight: 2180
url: /python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.6.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Gets the registered exporter descriptors. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Gets the registered export formats. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Creates the first found exporter suitable for the specified save options and image. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Gets the fist found supported descriptor suitable for the specified save options and image. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registers the specified image exporter descriptor. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registers the exporter. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Unregisters the exporter. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Creates the first found exporter suitable for the specified save options and image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to export. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The save options to use for export. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | The exporter which supports the specified image and save options or null if no such exporter is found. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Gets the fist found supported descriptor suitable for the specified save options and image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The image to export. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | The exporter descriptor which supports the specified image and save options or null if no such descriptor is found. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registers the specified image exporter descriptor.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | The image exporter descriptor. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registers the exporter.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | The exporter descriptor to register. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Unregisters the exporter.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | The exporter descriptor to unregister. |


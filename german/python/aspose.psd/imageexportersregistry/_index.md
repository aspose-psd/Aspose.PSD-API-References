---
title: "ImageExportersRegistry Klasse"
type: docs
weight: 2230
url: /de/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Ruft die registrierten Exporter-Deskriptoren ab. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ruft die registrierten Exportformate ab. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Erstellt den zuerst gefundenen Exporter, der für die angegebenen Speicheroptionen und das Bild geeignet ist. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für die angegebenen Speicheroptionen und das Bild geeignet ist. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registriert den angegebenen Bildexporter-Deskriptor. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registriert den Exporter. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Deregistriert den Exporter. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Erstellt den zuerst gefundenen Exporter, der für die angegebenen Speicheroptionen und das Bild geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das Bild zum Exportieren. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Speicheroptionen, die für den Export verwendet werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Der Exporter, der das angegebene Bild und die Speicheroptionen unterstützt, oder null, wenn kein solcher Exporter gefunden wird. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für die angegebenen Speicheroptionen und das Bild geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das Bild zum Exportieren. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Der Exporter-Deskriptor, der das angegebene Bild und die Speicheroptionen unterstützt, oder null, wenn kein solcher Deskriptor gefunden wird. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registriert den angegebenen Bildexporter-Deskriptor.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Der Bildexporter-Deskriptor. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registriert den Exporter.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Der zu registrierende Exporter-Deskriptor. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Deregistriert den Exporter.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Der zu deregistrierende Exporter-Deskriptor. |


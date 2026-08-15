---
title: "Clase ImageExportersRegistry"
type: docs
weight: 2230
url: /es/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Obtiene los descriptores de exportador registrados. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtiene los formatos de exportación registrados. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Crea el primer exportador encontrado que sea adecuado para las opciones de guardado y la imagen especificadas. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Obtiene el primer descriptor compatible encontrado que sea adecuado para las opciones de guardado y la imagen especificadas. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registra el descriptor de exportador de imagen especificado. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registra el exportador. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Anula el registro del exportador. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Crea el primer exportador encontrado que sea adecuado para las opciones de guardado y la imagen especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a exportar. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de guardado a usar para la exportación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | El exportador que soporta la imagen y las opciones de guardado especificadas o null si no se encuentra tal exportador. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Obtiene el primer descriptor compatible encontrado que sea adecuado para las opciones de guardado y la imagen especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a exportar. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | El descriptor del exportador que soporta la imagen y las opciones de guardado especificadas o null si no se encuentra tal descriptor. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registra el descriptor de exportador de imagen especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | El descriptor del exportador de imágenes. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registra el exportador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | El descriptor del exportador a registrar. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Anula el registro del exportador.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | El descriptor del exportador a anular el registro. |


---
title: "Classe ImageExportersRegistry"
type: docs
weight: 2230
url: /fr/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Obtient les descripteurs d'exportateur enregistrés. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtient les formats d'exportation enregistrés. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Crée le premier exportateur trouvé adapté aux options d'enregistrement et à l'image spécifiées. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement et à l'image spécifiées. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Enregistre le descripteur d'exportateur d'image spécifié. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Enregistre l'exportateur. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Désenregistre l'exportateur. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Crée le premier exportateur trouvé adapté aux options d'enregistrement et à l'image spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à exporter. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'enregistrement à utiliser pour l'exportation. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | L'exportateur qui prend en charge l'image spécifiée et les options d'enregistrement ou null si aucun exportateur de ce type n'est trouvé. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Obtient le premier descripteur pris en charge trouvé adapté aux options d'enregistrement et à l'image spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à exporter. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options. |

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Le descripteur d'exportateur qui prend en charge l'image spécifiée et les options d'enregistrement ou null si aucun descripteur de ce type n'est trouvé. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Enregistre le descripteur d'exportateur d'image spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Le descripteur d'exportateur d'image. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Enregistre l'exportateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Le descripteur d'exportateur à enregistrer. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Désenregistre l'exportateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Le descripteur d'exportateur à désenregistrer. |


---
title: "ImageExportersRegistry Klasse"
type: docs
weight: 2230
url: /nl/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Haalt de geregistreerde exporter‑descriptors op. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt de geregistreerde exportformaten op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Maakt de eerst gevonden exporter aan die geschikt is voor de opgegeven opslaanopties en afbeelding. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven opslaanopties en afbeelding. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registreert de opgegeven image exporter descriptor. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registreert de exporteur. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Deregistreert de exporteur. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Maakt de eerst gevonden exporter aan die geschikt is voor de opgegeven opslaanopties en afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te exporteren. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opslagopties die gebruikt moeten worden voor export. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | De exporteur die de opgegeven afbeelding en opslagopties ondersteunt, of null als zo'n exporteur niet wordt gevonden. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Haalt de eerst gevonden ondersteunde descriptor op die geschikt is voor de opgegeven opslaanopties en afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te exporteren. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | De exporteurdescriptor die de opgegeven afbeelding en opslagopties ondersteunt, of null als zo'n descriptor niet wordt gevonden. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registreert de opgegeven image exporter descriptor.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | De afbeeldingsexporteurdescriptor. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registreert de exporteur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | De te registreren exporteurdescriptor. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Deregistreert de exporteur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | De te deregistreren exporteurdescriptor. |


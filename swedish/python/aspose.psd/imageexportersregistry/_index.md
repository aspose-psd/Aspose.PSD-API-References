---
title: "ImageExportersRegistry‑klass"
type: docs
weight: 2230
url: /sv/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Hämtar de registrerade exportörbeskrivningarna. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar de registrerade exportformaten. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Skapar den först hittade exportören som är lämplig för de angivna sparalternativen och bilden. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Hämtar den först hittade stödjade beskrivaren som är lämplig för de angivna sparalternativen och bilden. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Registrerar den angivna bildexportörsbeskrivaren. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Registrerar exportören. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Avregistrerar exportören. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Skapar den först hittade exportören som är lämplig för de angivna sparalternativen och bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska exporteras. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparalternativen att använda för export. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Exportören som stöder den angivna bilden och sparalternativen eller null om ingen sådan exportör hittas. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Hämtar den först hittade stödjade beskrivaren som är lämplig för de angivna sparalternativen och bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska exporteras. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Exportörsbeskrivaren som stöder den angivna bilden och sparalternativen eller null om ingen sådan beskrivare hittas. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Registrerar den angivna bildexportörsbeskrivaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Bildexportörsbeskrivaren. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Registrerar exportören.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Exportörsbeskrivaren att registrera. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Avregistrerar exportören.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Exportörsbeskrivaren att avregistrera. |


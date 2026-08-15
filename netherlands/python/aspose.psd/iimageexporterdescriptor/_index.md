---
title: "IImageExporterDescriptor Klasse"
type: docs
weight: 1800
url: /nl/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt het ondersteunde formaat op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Bepaalt of de afbeeldingsexporter de opgegeven afbeelding kan exporteren naar het opgegeven afbeeldingformaat zoals gespecificeerd door de opslagopties. |
| [create_instance()](#create_instance__2) | Maakt een nieuwe exporter‑instantie aan. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Bepaalt of de afbeeldingsexporter de opgegeven afbeelding kan exporteren naar het opgegeven afbeeldingformaat zoals gespecificeerd door de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | De afbeelding om te exporteren. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De basis van de opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>True</c> als de door deze descriptor gemaakte exporter de opgegeven afbeelding kan exporteren naar het opgegeven bestandsformaat; anders <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Maakt een nieuwe exporter‑instantie aan.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Een nieuw exporteerder‑object. |



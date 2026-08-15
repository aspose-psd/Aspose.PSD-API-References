---
title: "IImageExporterDescriptor-klass"
type: docs
weight: 1800
url: /sv/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar det stödjade formatet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen. |
| [create_instance()](#create_instance__2) | Skapar en ny exportörsinstans. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Bestämmer om bildexportören kan exportera den angivna bilden till det angivna bildformatet som specificeras av sparalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Bilden som ska exporteras. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativbasen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>True</c> om exportören som skapats av denna beskrivare kan exportera den angivna bilden till det angivna filformatet; annars <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Skapar en ny exportörsinstans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | En ny exportörsinstans. |



---
title: "IImageExporterDescriptor Klasse"
type: docs
weight: 1800
url: /de/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ermittelt das unterstützte Format. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Bestimmt, ob der Bildexporteur das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann. |
| [create_instance()](#create_instance__2) | Erstellt eine neue Exporter-Instanz. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Bestimmt, ob der Bildexporteur das angegebene Bild in das durch die Speicheroptionen angegebene Bildformat exportieren kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das Bild zum Exportieren. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionsbasis. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>True</c> wenn der durch diesen Deskriptor erstellte Exporter das angegebene Bild in das angegebene Dateiformat exportieren kann; andernfalls <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Erstellt eine neue Exporter-Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Eine neue Exporter-Instanz. |



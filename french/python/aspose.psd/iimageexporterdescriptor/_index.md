---
title: "Classe IImageExporterDescriptor"
type: docs
weight: 1800
url: /fr/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtient le format pris en charge. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Détermine si l'exportateur d'image peut exporter l'image spécifiée au format d'image spécifié par les options d'enregistrement. |
| [create_instance()](#create_instance__2) | Crée une nouvelle instance d'exportateur. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Détermine si l'exportateur d'image peut exporter l'image spécifiée au format d'image spécifié par les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'image à exporter. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | La base des options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> si l'exportateur créé par ce descripteur peut exporter l'image spécifiée au format de fichier spécifié ; sinon, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crée une nouvelle instance d'exportateur.

**Returns**

| Type | Description |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Une nouvelle instance d'exportateur. |



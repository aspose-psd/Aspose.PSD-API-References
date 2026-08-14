---
title: "Classe IImageExporterDescriptor"
type: docs
weight: 1800
url: /it/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ottiene il formato supportato. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio. |
| [create_instance()](#create_instance__2) | Crea una nuova istanza dell'esportatore. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Determina se l'esportatore di immagini può esportare l'immagine specificata nel formato immagine specificato dalle opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | L'immagine da esportare. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | La base delle opzioni. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>True</c> se l'esportatore creato da questo descrittore può esportare l'immagine specificata nel formato file specificato; altrimenti, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nuova istanza dell'esportatore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Una nuova istanza dell'esportatore. |



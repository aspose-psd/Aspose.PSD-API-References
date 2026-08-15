---
title: "Clase IImageExporterDescriptor"
type: docs
weight: 1800
url: /es/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtiene el formato compatible. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado. |
| [create_instance()](#create_instance__2) | Crea una nueva instancia del exportador. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Determina si el exportador de imágenes puede exportar la imagen especificada al formato de imagen especificado por las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen a exportar. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | La base de opciones. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>True</c> si el exportador creado por este descriptor puede exportar la imagen especificada al formato de archivo especificado; de lo contrario, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nueva instancia del exportador.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Una nueva instancia del exportador. |



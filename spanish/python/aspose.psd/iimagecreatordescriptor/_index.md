---
title: "Clase IImageCreatorDescriptor"
type: docs
weight: 1770
url: /es/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtiene el formato compatible. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Determina si el creador de imágenes puede crear una nueva imagen usando el <paramref name=\"imageOptions\" />. |
| [create_instance()](#create_instance__2) | Crea una nueva instancia del creador. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Determina si el creador de imágenes puede crear una nueva imagen usando el <paramref name=\"imageOptions\" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>True</c> si el creador de imágenes creado por este descriptor puede crear datos de imagen usando el <paramref name=\"imageOptions\" /> especificado; de lo contrario, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nueva instancia del creador.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Una nueva instancia del creador. |



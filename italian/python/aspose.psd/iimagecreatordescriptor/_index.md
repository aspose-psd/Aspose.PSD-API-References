---
title: "Classe IImageCreatorDescriptor"
type: docs
weight: 1770
url: /it/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ottiene il formato supportato. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Determina se il creatore di immagini può creare una nuova immagine utilizzando <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | Crea una nuova istanza del creatore. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Determina se il creatore di immagini può creare una nuova immagine utilizzando <paramref name="imageOptions" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Le opzioni dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>True</c> se il creatore di immagini creato da questo descrittore può creare dati immagine utilizzando il <paramref name="imageOptions" /> specificato; altrimenti, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nuova istanza del creatore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Una nuova istanza del creatore. |



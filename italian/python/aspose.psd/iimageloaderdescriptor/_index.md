---
title: "Classe IImageLoaderDescriptor"
type: docs
weight: 1820
url: /it/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ottiene il formato supportato. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente utilizzando il <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Crea una nuova istanza del caricatore. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Determina se il caricatore di immagini può leggere una nuova immagine dallo stream specificato e opzionalmente utilizzando il <paramref name="loadOptions" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Il contenitore di stream. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | I dettagli del formato file specificati da <paramref name="loadOptions" />. Il <paramref name="loadOptions" /> può essere null. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se il caricatore di immagini creato da questo descrittore può leggere l'immagine dallo stream; altrimenti, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crea una nuova istanza del caricatore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Una nuova istanza del caricatore. |



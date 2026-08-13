---
title: "Classe IImageLoaderDescriptor"
type: docs
weight: 1820
url: /fr/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtient le format pris en charge. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant le <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Crée une nouvelle instance du chargeur. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Détermine si le chargeur d'image peut lire une nouvelle image depuis le flux spécifié et éventuellement en utilisant le <paramref name="loadOptions" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Les détails du format de fichier spécifiés par <paramref name="loadOptions" />. Le <paramref name="loadOptions" /> peut être nul. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si le chargeur d'image créé par ce descripteur peut lire l'image depuis le flux ; sinon, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crée une nouvelle instance du chargeur.

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Une nouvelle instance du chargeur. |



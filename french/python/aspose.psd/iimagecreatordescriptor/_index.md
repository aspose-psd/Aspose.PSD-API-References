---
title: "IImageCreatorDescriptor Classe"
type: docs
weight: 1770
url: /fr/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtient le format pris en charge. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Détermine si le créateur d'image peut créer une nouvelle image en utilisant le <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | Crée une nouvelle instance du créateur. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Détermine si le créateur d'image peut créer une nouvelle image en utilisant le <paramref name="imageOptions" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'image. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> si le créateur d'image créé par ce descripteur peut créer des données d'image en utilisant le <paramref name="imageOptions" /> spécifié ; sinon, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Crée une nouvelle instance du créateur.

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Une nouvelle instance du créateur. |



---
title: "Klasse IImageCreatorDescriptor"
type: docs
weight: 1770
url: /de/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Ermittelt das unterstützte Format. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Bestimmt, ob der Bild-Ersteller ein neues Bild mit dem <paramref name=\"imageOptions\" /> erstellen kann. |
| [create_instance()](#create_instance__2) | Erstellt eine neue Ersteller-Instanz. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Bestimmt, ob der Bild-Ersteller ein neues Bild mit dem <paramref name=\"imageOptions\" /> erstellen kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Bildoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>True</c> wenn der von diesem Deskriptor erstellte Bild-Ersteller Bilddaten mit dem angegebenen <paramref name=\"imageOptions\" /> erzeugen kann; andernfalls <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Erstellt eine neue Ersteller-Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Eine neue Ersteller-Instanz. |



---
title: "IImageCreatorDescriptor-klass"
type: docs
weight: 1770
url: /sv/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar det stödjade formatet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Bestämmer om bildskaparen kan skapa en ny bild med hjälp av <paramref name=\"imageOptions\" />. |
| [create_instance()](#create_instance__2) | Skapar en ny skapareinstans. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Bestämmer om bildskaparen kan skapa en ny bild med hjälp av <paramref name=\"imageOptions\" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bildalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>True</c> om bildskaparen som skapats av detta beskrivningsobjekt kan skapa bilddata med den angivna <paramref name=\"imageOptions\" />; annars <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Skapar en ny skapareinstans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | En ny skapareinstans. |



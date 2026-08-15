---
title: "IImageCreatorDescriptor Klasse"
type: docs
weight: 1770
url: /nl/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt het ondersteunde formaat op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Bepaalt of de afbeeldingmaker een nieuwe afbeelding kan maken met behulp van <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | Maakt een nieuw maker‑object aan. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Bepaalt of de afbeeldingmaker een nieuwe afbeelding kan maken met behulp van <paramref name="imageOptions" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De afbeeldingopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>True</c> als de door deze descriptor gemaakte afbeeldingmaker afbeeldingsgegevens kan maken met de opgegeven <paramref name="imageOptions" />; anders <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Maakt een nieuw maker‑object aan.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Een nieuw maker‑object. |



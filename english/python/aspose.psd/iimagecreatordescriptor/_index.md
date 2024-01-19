---
title: IImageCreatorDescriptor Class
type: docs
weight: 1710
url: /python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 23.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Gets the supported format. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | Determines whether image creator can create a new image using the <paramref name="imageOptions" />. |
| [create_instance()](#create_instance__2) | Creates a new creator instance. |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

Determines whether image creator can create a new image using the <paramref name="imageOptions" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The image options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>True</c> if image creator created by this descriptor can create image data using the specified <paramref name="imageOptions" />; otherwise, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Creates a new creator instance.

**Returns**

| Type | Description |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | A new creator instance. |



---
title: IImageLoaderDescriptor Class
type: docs
weight: 1770
url: /python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.6.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Gets the supported format. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | Determines whether image loader can read a new image from the specified stream and optionally using the <paramref name="loadOptions" />. |
| [create_instance()](#create_instance__2) | Creates a new loader instance. |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

Determines whether image loader can read a new image from the specified stream and optionally using the <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | The file format details specified by <paramref name="loadOptions" />. The <paramref name="loadOptions" /> may be null. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image loader created by this descriptor can read image from stream; otherwise, <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Creates a new loader instance.

**Returns**

| Type | Description |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | A new loader instance. |



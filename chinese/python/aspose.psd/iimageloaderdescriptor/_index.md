---
title: "IImageLoaderDescriptor 类"
type: docs
weight: 1820
url: /zh/python-net/aspose.psd/iimageloaderdescriptor/
---

**Summary:** The image loader descriptor specifying the loader properties. The loader descriptor is used to overcome<br/>            the necessity to contain each image loader instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageLoaderDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取受支持的格式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_load(stream_container, load_options)](#can_load_stream_container_load_options_1) | 确定图像加载器是否可以从指定的流读取新图像，并可选地使用 <paramref name="loadOptions" />。 |
| [create_instance()](#create_instance__2) | 创建一个新的加载器实例。 |


### Method: can_load(stream_container, load_options) {#can_load_stream_container_load_options_1}


```
 can_load(stream_container, load_options) 
```

确定图像加载器是否可以从指定的流读取新图像，并可选地使用 <paramref name="loadOptions" />。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 由 <paramref name="loadOptions" /> 指定的文件格式详细信息。<paramref name="loadOptions" /> 可能为 null。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果由此描述符创建的图像加载器可以从流读取图像，则为 <c>true</c>；否则为 <c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

创建一个新的加载器实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | 一个新的加载器实例。 |



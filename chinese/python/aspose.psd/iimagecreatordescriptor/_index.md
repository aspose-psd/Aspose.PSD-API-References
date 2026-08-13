---
title: "IImageCreatorDescriptor 类"
type: docs
weight: 1770
url: /zh/python-net/aspose.psd/iimagecreatordescriptor/
---

**Summary:** The image creator descriptor specifying the creator properties. The creator descriptor is used to overcome<br/>            the necessity to contain each image creator instance in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageCreatorDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取受支持的格式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [can_create(image_options)](#can_create_image_options_1) | 确定图像创建器是否可以使用 <paramref name=\"imageOptions\" /> 创建新图像。 |
| [create_instance()](#create_instance__2) | 创建一个新的创建器实例。 |


### Method: can_create(image_options) {#can_create_image_options_1}


```
 can_create(image_options) 
```

确定图像创建器是否可以使用 <paramref name=\"imageOptions\" /> 创建新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 图像选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>True</c> 如果由此描述符创建的图像创建器能够使用指定的 <paramref name=\"imageOptions\" /> 创建图像数据；否则为 <c>false</c>。 |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

创建一个新的创建器实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | 一个新的创建器实例。 |



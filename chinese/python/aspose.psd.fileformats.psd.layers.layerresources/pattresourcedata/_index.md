---
title: "PattResourceData 类"
type: docs
weight: 780
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | 初始化 PattResourceData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| height | short | r | 获取高度。 |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | 获取图像模式。 |
| 长度 | int | r | 获取图案的长度。 |
| name | 字符串 | 读/写 | 获取或设置名称。 |
| pattern_data | int | r | 获取图案数据。 |
| pattern_id | 字符串 | 读/写 | 获取或设置图案标识符。 |
| version | int | r | 获取版本。 |
| width | short | r | 获取宽度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | 保存图案数据。 |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | 设置图案。 |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

初始化 PattResourceData 类的新实例

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

保存图案数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

设置图案。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pixels | int | 像素。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 边界。 |


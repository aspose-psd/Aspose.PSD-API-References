---
title: "AiLayerSection 类"
type: docs
weight: 50
url: /zh/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 蓝色 | int | 读/写 | 获取或设置蓝色分量。 |
| color_index | int | 读/写 | 获取或设置颜色的索引。<br/>            此参数的取值范围为 –1 到 26。每个整数<br/>            表示可分配给图层用于用户<br/>            标识目的的颜色。 |
| color_number | int | 读/写 | 获取或设置颜色编号。-1 是来自红、绿、蓝属性的自定义颜色值。<br/>            指定图层的颜色设置。 |
| dim_value | int | 读/写 | 获取或设置暗度值（百分比）。<br/>            将图层中包含的链接图像和位图图像的强度降低到指定的百分比。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| 绿色 | int | 读/写 | 获取或设置绿色颜色分量。 |
| has_multi_layer_masks | bool | 读/写 | 获取或设置一个值，指示此实例是否具有多层掩码。 |
| is_images_dimmed | bool | 读/写 | 获取或设置一个值，指示此图层是否已调暗。<br/>            降低图层中链接图像和位图图像的强度。 |
| is_locked | bool | 读/写 | 获取或设置一个值，指示此图层是否被锁定。<br/>            防止对该项目的更改。 |
| is_preview | bool | 读/写 | 获取或设置一个值，指示此图层是否为预览。<br/>            以彩色而非轮廓显示图层中包含的艺术作品。 |
| is_printed | bool | 读/写 | 获取或设置一个值，指示此图层是否已打印。<br/>            如果为 true，则使图层中包含的艺术作品可打印。 |
| is_shown | bool | 读/写 | 获取或设置一个值，指示此图层是否显示。<br/>            如果为 true，则在画板上显示图层中包含的所有艺术作品。 |
| is_template | bool | 读/写 | 获取或设置一个值，指示此图层是否为模板图层。 |
| name | 字符串 | 读/写 | 获取或设置图层名称。<br/>            指定项目在“图层”面板中显示的名称。 |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | 获取光栅图像。 |
| 红色 | int | 读/写 | 获取或设置红色颜色分量。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | 添加光栅图像。 |
| [get_data()](#get_data__2) | 获取字符串数据。 |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

添加光栅图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | 光栅图像。 |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

获取字符串数据。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 该节的字符串数据 |



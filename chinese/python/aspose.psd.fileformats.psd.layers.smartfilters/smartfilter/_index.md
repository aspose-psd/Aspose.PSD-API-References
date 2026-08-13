---
title: "SmartFilter 类"
type: docs
weight: 50
url: /zh/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---

**Summary:** The class to process a base logic of smart filters.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | 获取或设置混合模式。 |
| filter_id | int | r | 获取智能过滤器类型标识符。 |
| is_enabled | bool | 读/写 | 获取或设置智能过滤器的启用状态。 |
| name | 字符串 | r | 获取智能过滤器名称。 |
| opacity | double | 读/写 | 获取或设置智能滤镜的不透明度值。 |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | 带有智能滤镜数据的源描述符结构。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | 将当前滤镜应用于输入的 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 图像。 |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | 将当前滤镜应用于输入的 [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 掩码数据。 |
| [clone()](#clone__3) | 创建当前实例的成员级克隆。 |


### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

将当前滤镜应用于输入的 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 光栅图像。 |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

将当前滤镜应用于输入的 [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 掩码数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 带有掩码数据的图层。 |

### Method: clone() {#clone__3}


```
 clone() 
```

创建当前实例的成员级克隆。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | 返回当前实例的成员级克隆。 |



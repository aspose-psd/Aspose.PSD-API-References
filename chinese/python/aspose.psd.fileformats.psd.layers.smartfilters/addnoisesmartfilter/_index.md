---
title: "AddNoiseSmartFilter 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---

**Summary:** The AddNoise smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.AddNoiseSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter__1) | 初始化 [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | 当前智能过滤器的标识符。 |
| amount_noise | double | 读/写 | 获取或设置噪声值的数量。 |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | 获取或设置混合模式。 |
| distribution | [NoiseDistribution](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/noisedistribution) | r/w | 获取或设置噪声滤镜的分布。 |
| filter_id | int | r | 获取智能过滤器类型标识符。 |
| is_enabled | bool | 读/写 | 获取或设置智能过滤器的启用状态。 |
| is_monochromatic | bool | 读/写 | 获取或设置单色的值。 |
| name | 字符串 | r | 获取智能过滤器名称。 |
| opacity | double | 读/写 | 获取或设置智能滤镜的不透明度值。 |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | 带有智能滤镜数据的源描述符结构。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | 将当前滤镜应用于输入的 [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 图像。 |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | 将当前滤镜应用于输入的 [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) 掩码数据。 |
| [clone()](#clone__3) | 创建当前实例的成员级克隆。 |


### Constructor: AddNoiseSmartFilter() {#AddNoiseSmartFilter__1}


```
 AddNoiseSmartFilter() 
```

初始化 [AddNoiseSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/) 类的新实例。

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



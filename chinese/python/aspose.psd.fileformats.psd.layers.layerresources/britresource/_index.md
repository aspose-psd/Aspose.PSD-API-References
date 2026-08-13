---
title: "BritResource 类"
type: docs
weight: 120
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BritResource()](#BritResource__1) | 初始化 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 类的新实例。 |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | 初始化 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 类的新实例。 |
| [BritResource(bytes)](#BritResource_bytes_3) | 初始化 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 类的新实例。<br/>            PSD 格式规范包含以下描述：<br/>            2 亮度<br/>            2 对比度<br/>            2 亮度和对比度的平均值<br/>            1 仅 Lab 颜色<br/>            在现代 PSD（CS5 及以上）中不再使用，其中使用 CgEd。CgEd 存储信息属性 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| 亮度 | short | 读/写 | 获取或设置亮度。 |
| 对比度 | short | 读/写 | 获取或设置对比度。 |
| key | int | r | 获取图层资源键。 |
| lab_color | bool | 读/写 | 获取或设置指示是否为 [lab color] 的值。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| mean_value_for_brightness_and_contrast | short | 读/写 | 获取或设置亮度和对比度的平均值。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

初始化 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 类的新实例。

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

初始化 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 亮度 | short | 亮度。 |
| 对比度 | short | 对比度。 |
| mean_value_for_brightness_and_contrast | short | 亮度和对比度的平均值。 |
| lab_color | bool | 如果设置为 <c>true</c> [lab color]。 |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

初始化 [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) 类的新实例。<br/>            PSD 格式规范包含以下描述：<br/>            2 亮度<br/>            2 对比度<br/>            2 亮度和对比度的平均值<br/>            1 仅 Lab 颜色<br/>            在现代 PSD（CS5 及以上）中不再使用，其中使用 CgEd。CgEd 存储信息属性

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 字节 | byte | 这些字节。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |


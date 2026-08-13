---
title: "PhflResource 类"
type: docs
weight: 790
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| density | int | 读/写 | 获取或设置密度。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| preserve_luminosity | bool | 读/写 | 获取或设置指示是否 [preserve luminosity] 的值。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
| version | short | r | 获取版本。默认是 2 或 3 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | 获取 RGB 的颜色。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | 将资源保存到指定的流容器。 |
| [set_rgb_color(color)](#set_rgb_color_color_3) | 设置 RGB 颜色。 |


### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

获取 RGB 的颜色。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB 颜色 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

设置 RGB 颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | RGB 颜色。 |


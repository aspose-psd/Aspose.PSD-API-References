---
title: "BlncResource 类"
type: docs
weight: 80
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | 初始化一个新的 [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| highlights_cyan_red_balance | short | 读/写 | 获取或设置 Highlights Cyan Red Balance。 |
| highlights_magenta_green_balance | short | 读/写 | 获取或设置 Highlights Magenta Green Balance。 |
| highlights_yellow_blue_balance | short | 读/写 | 获取或设置 Highlights Yellow Blue Balance。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| midtones_cyan_red_balance | short | 读/写 | 获取或设置 Midtones Cyan Red Balance。 |
| midtones_magenta_green_balance | short | 读/写 | 获取或设置 Midtones Magenta Green Balance。 |
| midtones_yellow_blue_balance | short | 读/写 | 获取或设置 Midtones Yellow Blue Balance。 |
| preserve_luminosity | bool | r/w | 获取或设置一个值，指示此 [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) 是否保留亮度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| shadows_cyan_red_balance | short | 读/写 | 获取或设置 Shadows Cyan Red Balance。 |
| shadows_magenta_green_balance | short | 读/写 | 获取或设置 Shadows Magenta Green Balance。 |
| shadows_yellow_blue_balance | short | 读/写 | 获取或设置 Shadows Yellow Blue Balance。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

初始化一个新的 [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) 类实例。

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


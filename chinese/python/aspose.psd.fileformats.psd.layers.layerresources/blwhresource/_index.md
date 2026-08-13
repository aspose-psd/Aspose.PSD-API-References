---
title: "BlwhResource 类"
type: docs
weight: 90
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | 初始化 BlwhResource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| black_and_white_preset_file_name | 字符串 | 读/写 | 获取或设置黑白预设文件名。 |
| 蓝色 | int | 读/写 | 获取或设置蓝色值。 |
| bw_preset_kind | int | 读/写 | 获取或设置黑白预设类型值。 |
| 青色 | int | 读/写 | 获取或设置青色值。 |
| 绿色 | int | 读/写 | 获取或设置绿色值。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| 洋红色 | int | 读/写 | 获取或设置洋红色值。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| 红色 | int | 读/写 | 获取或设置 reds 值。 |
| signature | int | r | 获取签名。 |
| tint_color | int | 读/写 | 获取或设置 Tint Color ARGB 值。 |
| use_tint | bool | 读/写 | 获取或设置一个值，指示是否使用 [tint color]。 |
| yellows | int | 读/写 | 获取或设置 yellows 值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

初始化 BlwhResource 类的新实例

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


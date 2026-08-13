---
title: "CgEdResource 类"
type: docs
weight: 130
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | 初始化 CgEdResource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| auto | bool | r/w | 获取或设置一个值，指示此 [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) 是否为自动。 |
| 亮度 | int | 读/写 | 获取或设置亮度。 |
| 对比度 | int | 读/写 | 获取或设置对比度。 |
| key | int | r | 获取图层资源键。 |
| lab_color | bool | 读/写 | 获取或设置一个值，指示是否使用 [lab color]。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| mean_value_for_brightness_and_contrast | int | 读/写 | 获取或设置亮度和对比度的平均值。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
| use_legacy | bool | 读/写 | 获取或设置一个值，指示是否 [use legacy]。 |
| version | int | 读/写 | 获取或设置版本。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

初始化 CgEdResource 类的新实例

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


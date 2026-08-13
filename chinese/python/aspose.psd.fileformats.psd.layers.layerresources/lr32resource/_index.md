---
title: "Lr32Resource 类"
type: docs
weight: 620
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/
---

**Summary:** The lr32 resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lr32Resource

**Inheritance:** LrXxResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Lr32Resource()](#Lr32Resource__1) | 初始化 Lr32Resource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| key | int | r | 获取图层资源键。 |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | r/w | 获取或设置图层。 |
| 长度 | int | r | 获取图像的 PSD 标头版本的资源长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 保存图层记录。 |


### Constructor: Lr32Resource() {#Lr32Resource__1}


```
 Lr32Resource() 
```

初始化 Lr32Resource 类的新实例

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

保存图层记录。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| psd_version | int | PSD 版本。 |


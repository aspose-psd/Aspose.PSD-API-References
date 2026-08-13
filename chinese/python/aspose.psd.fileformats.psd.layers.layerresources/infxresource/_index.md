---
title: "InfxResource 类"
type: docs
weight: 420
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | 初始化 [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 类的新实例。 |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | 初始化 [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 类的新实例。 |
| [InfxResource(data)](#InfxResource_data_3) | 初始化 [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 类的新实例。<br/>            使用自定义或未知值 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 该类型工具信息键。 |
| blend_interior_elements | bool | 读/写 | 获取或设置一个值，指示 [blend interior elements]。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 保存指定的流容器。 |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

初始化 [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 类的新实例。

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

初始化 [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| blend_interior_elements | bool | 如果设置为 <c>true</c> [blend interior elements]。 |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

初始化 [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) 类的新实例。<br/>            使用自定义或未知值

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 资源数据。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

保存指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |
| psd_version | int | PSD 版本。 |


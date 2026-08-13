---
title: "LspfResource 类"
type: docs
weight: 640
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | 初始化 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 类的新实例。 |
| [LspfResource(data)](#LspfResource_data_2) | 初始化 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 类的新实例。<br/>            使用自定义或未知值 |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | 初始化 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| TYPE_TOOL_KEY [static] | int | r | 类型工具信息键 1819504742 |
| is_composite_protected | bool | 读/写 | 获取或设置一个值，指示此实例是否受复合保护。 |
| is_position_protected | bool | 读/写 | 获取或设置一个值，指示此实例是否受位置保护。 |
| is_transparency_protected | bool | 读/写 | 获取或设置一个值，指示此实例是否受透明度保护。 |
| key | int | r | 获取图层资源键。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | 获取或设置锁的类型。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| signature | int | r | 获取签名。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

初始化 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 类的新实例。

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

初始化 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 类的新实例。<br/>            使用自定义或未知值

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 资源数据。 |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

初始化 [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| is_transparency_protected | bool | 如果设置为 <c>true</c> [是透明度受保护的]。 |
| is_composite_protected | bool | 如果设置为 <c>true</c> [是复合受保护的]。 |
| is_position_protected | bool | 如果设置为 <c>true</c> [是位置受保护的]。 |

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


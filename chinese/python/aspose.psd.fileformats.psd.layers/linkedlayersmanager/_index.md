---
title: "LinkedLayersManager 类"
type: docs
weight: 1140
url: /zh/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | 根据链接组 ID 获取图层。 |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | 获取与图层关联的链接组 ID。 |
| [link_layers(layers)](#link_layers_layers_3) | 链接输入图层并返回 LingGroupId。 |
| [unlink_layer(layer)](#unlink_layer_layer_4) | 取消链接该图层。 |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

根据链接组 ID 获取图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| link_group_id | short | 链接组 ID。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 图层数组。 |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

获取与图层关联的链接组 ID。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 该图层。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| short | 链接组 ID。 |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

链接输入图层并返回 LingGroupId。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 图层。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| short | 链接组 ID。 |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

取消链接该图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 该图层。 |


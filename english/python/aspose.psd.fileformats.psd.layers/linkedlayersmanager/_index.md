---
title: LinkedLayersManager Class
type: docs
weight: 1080
url: /python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.1.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Gets layers by link group id. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Gets the link group ID associated with the layer. |
| [link_layers(layers)](#link_layers_layers_3) | Links the input layers and return LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Unlinks the layer.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Gets layers by link group id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| link_group_id | short | The link group id. |

**Returns**

| Type | Description |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | The layers array. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Gets the link group ID associated with the layer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | The layer. |

**Returns**

| Type | Description |
| :- | :- |
| short | The link group id. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Links the input layers and return LingGroupId.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | The layers. |

**Returns**

| Type | Description |
| :- | :- |
| short | The link group id. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Unlinks the layer..

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | The layer. |


---
title: "LinkedLayersManager Klasse"
type: docs
weight: 1140
url: /nl/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Haalt lagen op op basis van linkgroeps-id. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Haalt de linkgroeps-ID op die aan de laag is gekoppeld. |
| [link_layers(layers)](#link_layers_layers_3) | Koppelt de invoerlagen en retourneert LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Ontkoppelt de laag.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Haalt lagen op op basis van linkgroeps-id.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| link_group_id | short | De linkgroeps-id. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | De lagenarray. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Haalt de linkgroeps-ID op die aan de laag is gekoppeld.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | De laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| short | De linkgroeps-id. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Koppelt de invoerlagen en retourneert LingGroupId.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | De lagen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| short | De linkgroeps-id. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Ontkoppelt de laag..

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | De laag. |


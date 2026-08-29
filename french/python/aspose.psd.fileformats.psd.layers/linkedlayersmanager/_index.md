---
title: "Classe LinkedLayersManager"
type: docs
weight: 1140
url: /fr/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Obtient les calques par identifiant du groupe de liens. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Obtient l'identifiant du groupe de liens associé au calque. |
| [link_layers(layers)](#link_layers_layers_3) | Lie les calques d'entrée et renvoie LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Délie le calque.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Obtient les calques par identifiant du groupe de liens.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| link_group_id | short | L'identifiant du groupe de liens. |

**Returns**

| Type | Description |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Le tableau de calques. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Obtient l'identifiant du groupe de liens associé au calque.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Le calque. |

**Returns**

| Type | Description |
| :- | :- |
| short | L'identifiant du groupe de liens. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Lie les calques d'entrée et renvoie LingGroupId.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Les calques. |

**Returns**

| Type | Description |
| :- | :- |
| short | L'identifiant du groupe de liens. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Délie le calque..

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Le calque. |


---
title: "Classe LinkedLayersManager"
type: docs
weight: 1140
url: /it/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Ottiene i livelli per ID gruppo di collegamento. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Ottiene l'ID del gruppo di collegamento associato al livello. |
| [link_layers(layers)](#link_layers_layers_3) | Collega i livelli di input e restituisce LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Scollega il livello.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Ottiene i livelli per ID gruppo di collegamento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| link_group_id | short | L'ID del gruppo di collegamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | L'array dei livelli. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Ottiene l'ID del gruppo di collegamento associato al livello.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Il livello. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| short | L'ID del gruppo di collegamento. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Collega i livelli di input e restituisce LingGroupId.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | I livelli. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| short | L'ID del gruppo di collegamento. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Scollega il livello..

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Il livello. |


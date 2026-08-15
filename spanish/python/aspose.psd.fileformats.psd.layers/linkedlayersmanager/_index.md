---
title: "Clase LinkedLayersManager"
type: docs
weight: 1140
url: /es/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Obtiene capas por ID de grupo de enlace. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Obtiene el ID del grupo de enlace asociado a la capa. |
| [link_layers(layers)](#link_layers_layers_3) | Enlaza las capas de entrada y devuelve LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Desenlaza la capa.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Obtiene capas por ID de grupo de enlace.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| link_group_id | short | El ID del grupo de enlace. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | La matriz de capas. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Obtiene el ID del grupo de enlace asociado a la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | La capa. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| short | El ID del grupo de enlace. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Enlaza las capas de entrada y devuelve LingGroupId.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Las capas. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| short | El ID del grupo de enlace. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Desenlaza la capa..

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | La capa. |


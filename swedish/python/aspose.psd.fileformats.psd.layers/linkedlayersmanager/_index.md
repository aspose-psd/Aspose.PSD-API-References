---
title: "LinkedLayersManager-klass"
type: docs
weight: 1140
url: /sv/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Hämtar lager efter länkgrupps-id. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Hämtar länkgrupps-ID som är associerat med lagret. |
| [link_layers(layers)](#link_layers_layers_3) | Länkar inmatningslagren och returnerar LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Kopplar bort lagret.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Hämtar lager efter länkgrupps-id.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| link_group_id | short | Länkgruppens id. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagerarrayen. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Hämtar länkgrupps-ID som är associerat med lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| short | Länkgruppens id. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Länkar inmatningslagren och returnerar LingGroupId.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| short | Länkgruppens id. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Kopplar bort lagret..

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagret. |


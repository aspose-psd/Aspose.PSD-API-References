---
title: "LinkedLayersManager Klasse"
type: docs
weight: 1140
url: /de/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Liest Ebenen nach Linkgruppen-ID. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Liest die mit der Ebene verknüpfte Linkgruppen-ID. |
| [link_layers(layers)](#link_layers_layers_3) | Verknüpft die Eingabeebenen und gibt LingGroupId zurück. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Löst die Verknüpfung der Ebene. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Liest Ebenen nach Linkgruppen-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| link_group_id | short | Die Linkgruppen-ID. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Das Ebenen-Array. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Liest die mit der Ebene verknüpfte Linkgruppen-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Die Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| short | Die Linkgruppen-ID. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Verknüpft die Eingabeebenen und gibt LingGroupId zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Die Ebenen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| short | Die Linkgruppen-ID. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Löst die Verknüpfung der Ebene.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Die Ebene. |


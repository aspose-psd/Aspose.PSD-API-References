---
title: "Κλάση LinkedLayersManager"
type: docs
weight: 1140
url: /el/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Λαμβάνει τα στρώματα με βάση το αναγνωριστικό ομάδας συνδέσμου. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Λαμβάνει το αναγνωριστικό ομάδας συνδέσμου που σχετίζεται με το στρώμα. |
| [link_layers(layers)](#link_layers_layers_3) | Συνδέει τα εισερχόμενα στρώματα και επιστρέφει το LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Αποσυνδέει το στρώμα.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Λαμβάνει τα στρώματα με βάση το αναγνωριστικό ομάδας συνδέσμου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| link_group_id | short | Το αναγνωριστικό ομάδας συνδέσμου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Ο πίνακας στρωμάτων. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Λαμβάνει το αναγνωριστικό ομάδας συνδέσμου που σχετίζεται με το στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Το στρώμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| short | Το αναγνωριστικό ομάδας συνδέσμου. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Συνδέει τα εισερχόμενα στρώματα και επιστρέφει το LingGroupId.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Τα στρώματα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| short | Το αναγνωριστικό ομάδας συνδέσμου. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Αποσυνδέει το στρώμα..

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Το στρώμα. |


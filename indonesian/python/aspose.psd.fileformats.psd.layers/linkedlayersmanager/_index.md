---
title: "Kelas LinkedLayersManager"
type: docs
weight: 1140
url: /id/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Mendapatkan lapisan berdasarkan ID grup tautan. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Mendapatkan ID grup tautan yang terkait dengan lapisan. |
| [link_layers(layers)](#link_layers_layers_3) | Menautkan lapisan input dan mengembalikan LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Melepaskan tautan lapisan.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Mendapatkan lapisan berdasarkan ID grup tautan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| link_group_id | short | ID grup tautan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Array lapisan. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Mendapatkan ID grup tautan yang terkait dengan lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lapisan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| short | ID grup tautan. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Menautkan lapisan input dan mengembalikan LingGroupId.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lapisan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| short | ID grup tautan. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Melepaskan tautan lapisan..

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lapisan. |


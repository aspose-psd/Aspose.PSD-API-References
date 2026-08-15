---
title: "LinkedLayersManager Sınıfı"
type: docs
weight: 1140
url: /tr/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | Katmanları link grup kimliğine göre alır. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | Katmanla ilişkili link grup kimliğini alır. |
| [link_layers(layers)](#link_layers_layers_3) | Girdi katmanlarını bağlar ve LingGroupId'yi döndürür. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | Katmanın bağlantısını kaldırır.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

Katmanları link grup kimliğine göre alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| link_group_id | short | Link grup kimliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Katmanlar dizisi. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

Katmanla ilişkili link grup kimliğini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Katman. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| short | Link grup kimliği. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

Girdi katmanlarını bağlar ve LingGroupId'yi döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Katmanlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| short | Link grup kimliği. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

Katmanın bağlantısını kaldırır..

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Katman. |


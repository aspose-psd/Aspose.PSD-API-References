---
title: "فئة LinkedLayersManager"
type: docs
weight: 1140
url: /ar/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | يحصل على الطبقات حسب معرف مجموعة الارتباط. |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | يحصل على معرف مجموعة الارتباط المرتبط بالطبقة. |
| [link_layers(layers)](#link_layers_layers_3) | يربط الطبقات المدخلة ويعيد LingGroupId. |
| [unlink_layer(layer)](#unlink_layer_layer_4) | يفك ربط الطبقة.. |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

يحصل على الطبقات حسب معرف مجموعة الارتباط.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| link_group_id | short | معرف مجموعة الارتباط. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | مصفوفة الطبقات. |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

يحصل على معرف مجموعة الارتباط المرتبط بالطبقة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | الطبقة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| short | معرف مجموعة الارتباط. |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

يربط الطبقات المدخلة ويعيد LingGroupId.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | الطبقات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| short | معرف مجموعة الارتباط. |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

يفك ربط الطبقة..

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | الطبقة. |


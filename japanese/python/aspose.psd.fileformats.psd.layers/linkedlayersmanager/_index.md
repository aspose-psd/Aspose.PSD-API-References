---
title: "LinkedLayersManager クラス"
type: docs
weight: 1140
url: /ja/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---

**Summary:** Linked layers manager class.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LinkedLayersManager

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_layers_by_link_group_id(link_group_id)](#get_layers_by_link_group_id_link_group_id_1) | リンクグループIDでレイヤーを取得します。 |
| [get_link_group_id(layer)](#get_link_group_id_layer_2) | レイヤーに関連付けられたリンクグループIDを取得します。 |
| [link_layers(layers)](#link_layers_layers_3) | 入力レイヤーをリンクし、LingGroupId を返します。 |
| [unlink_layer(layer)](#unlink_layer_layer_4) | レイヤーのリンクを解除します。 |


### Method: get_layers_by_link_group_id(link_group_id) {#get_layers_by_link_group_id_link_group_id_1}


```
 get_layers_by_link_group_id(link_group_id) 
```

リンクグループIDでレイヤーを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| link_group_id | short | リンクグループIDです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | レイヤー配列です。 |


### Method: get_link_group_id(layer) {#get_link_group_id_layer_2}


```
 get_link_group_id(layer) 
```

レイヤーに関連付けられたリンクグループIDを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | レイヤー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| short | リンクグループIDです。 |


### Method: link_layers(layers) {#link_layers_layers_3}


```
 link_layers(layers) 
```

入力レイヤーをリンクし、LingGroupId を返します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | レイヤーです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| short | リンクグループIDです。 |


### Method: unlink_layer(layer) {#unlink_layer_layer_4}


```
 unlink_layer(layer) 
```

レイヤーのリンクを解除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | レイヤー。 |


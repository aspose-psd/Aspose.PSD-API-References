---
title: "SmartObjectProvider クラス"
type: docs
weight: 1940
url: /ja/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | レイヤーを埋め込みスマートオブジェクトに変換します。 |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | レイヤーを埋め込みスマートオブジェクトに変換します。 |
| embed_all_linked() | 画像内のすべてのリンクされたスマートオブジェクトを埋め込みます。 |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | ソースレイヤーをコピーして新しいスマートオブジェクトレイヤーを作成します。 |
| update_all_modified_content() | 画像内のすべての変更されたスマートオブジェクトの内容を更新します。 |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

レイヤーを埋め込みスマートオブジェクトに変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer_numbers | int | レイヤー番号。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 作成された [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) インスタンスです。 |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

レイヤーを埋め込みスマートオブジェクトに変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | レイヤーです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | 作成された [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) インスタンスです。 |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

ソースレイヤーをコピーして新しいスマートオブジェクトレイヤーを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | ソースレイヤーです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | クローンされた [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) インスタンス。 |



---
title: "LayerHashCalculator クラス"
type: docs
weight: 960
url: /ja/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | 新しいインスタンスを初期化します。 [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) クラスです。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | ブレンドハッシュを取得します。 |
| [get_channels_hash()](#get_channels_hash__2) | チャンネルハッシュを取得します。 |
| [get_content_hash()](#get_content_hash__3) | コンテンツハッシュを取得します。 |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

新しいインスタンスを初期化します。 [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) クラスです。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | レイヤー。 |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

ブレンドハッシュを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | レイヤーブレンドオプションのユニークハッシュ |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

チャンネルハッシュを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | すべてのレイヤーチャンネルのハッシュ |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

コンテンツハッシュを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | レイヤーの重要なパラメータのハッシュです。このハッシュはすべてのレイヤータイプで異なります。 |



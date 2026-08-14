---
title: "Txt2Resource クラス"
type: docs
weight: 970
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | 新しい Txt2Resource クラスのインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| data | byte | r/w | データを取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | テキストレコードを Resource に追加し、テキストレコードの ID を返します。 |
| [get_text_data()](#get_text_data__2) | リソースデータからテキストレコードを取得します。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | 指定されたストリームコンテナを保存します。 |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

新しい Txt2Resource クラスのインスタンスを初期化します

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

テキストレコードを Resource に追加し、テキストレコードの ID を返します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| text | string | レコードのテキストです。 |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 境界。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | リソースのテキストレコードの ID を返します |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

リソースデータからテキストレコードを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | テキストレコードの配列 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

指定されたストリームコンテナを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |


---
title: "OffsetStructure クラス"
type: docs
weight: 110
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/offsetstructure/
---

**Summary:** The offset structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.OffsetStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [OffsetStructure(key_name, class_id)](#OffsetStructure_key_name_class_id_1) | 新しいインスタンスを初期化します [OffsetStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/offsetstructure/) クラス。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | 構造キーを識別します。 |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | クラス ID を取得または設定します。 |
| class_name | string | r/w | クラス名を取得または設定します。 |
| key | int | r | 構造キーを取得します。 |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | キー名を取得または設定します。 |
| length | int | r | バイト単位で [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) の長さを取得します。 |
| 値 | int | r/w | 整数値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | ヘッダーの長さを取得します。 |
| [save(stream_container)](#save_stream_container_2) | 指定されたストリームコンテナに構造を保存します。 |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 指定されたストリームコンテナに構造を保存します。 |


### Constructor: OffsetStructure(key_name, class_id) {#OffsetStructure_key_name_class_id_1}


```
 OffsetStructure(key_name, class_id) 
```

新しいインスタンスを初期化します [OffsetStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/offsetstructure/) クラス。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | キー名。 |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | クラス ID。 |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

ヘッダーの長さを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | ヘッダーの長さ |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

指定されたストリームコンテナに構造を保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

指定されたストリームコンテナに構造を保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |


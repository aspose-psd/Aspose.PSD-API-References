---
title: "UnitArrayStructure クラス"
type: docs
weight: 170
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---

**Summary:** Defines the UnitArrayStructure class that holds float values array and their measure unit.<br/>            It is used in the PSD file resources, usually by [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnitArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [UnitArrayStructure(key_name, unit_type, values)](#UnitArrayStructure_key_name_unit_type_values_1) | 新しい [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | 「UnFl」 [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) キーを定義します。 |
| key | int | r | このユニット配列構造キーを取得します。 |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | キー名を取得または設定します。 |
| length | int | r | バイト単位で [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) の長さを取得します。 |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | r/w | [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) の値の測定単位タイプを取得または設定します。 |
| value_count | int | r | 値のカウントを取得します。 |
| values | double | r/w | 単位配列構造の値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | ヘッダーの長さを取得します。 |
| [save(stream_container)](#save_stream_container_2) | 指定されたストリームコンテナに構造を保存します。 |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 指定されたストリームコンテナに構造を保存します。 |


### Constructor: UnitArrayStructure(key_name, unit_type, values) {#UnitArrayStructure_key_name_unit_type_values_1}


```
 UnitArrayStructure(key_name, unit_type, values) 
```

新しい [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | キーの名前。 |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | 単位の型。 |
| values | double | 値。 |

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


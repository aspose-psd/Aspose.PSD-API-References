---
title: "EnumeratedReferenceStructure クラス"
type: docs
weight: 70
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/
---

**Summary:** Enumerated reference structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedReferenceStructure

**Inheritance:** EnumeratedDescriptorStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name)](#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1) | 新しいインスタンスを初期化します [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) クラス。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| ENUMERATED_STRUCTURE_KEY [static] | int | r | 構造キーを識別します。 |
| STRUCTURE_KEY [static] | int | r | 列挙された記述子キー。 |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | クラス ID を取得または設定します。 |
| class_name | string | r/w | クラス名を取得または設定します。 |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 列挙型名を取得または設定します。 |
| key | int | r | キーを取得します。 |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | キー名を取得または設定します。 |
| length | int | r | バイト単位で [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) の長さを取得します。 |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | 型IDを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | ヘッダーの長さを取得します。 |
| [save(stream_container)](#save_stream_container_2) | データを保存します。 |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | 指定されたストリームコンテナに構造を保存します。 |


### Constructor: EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) {#EnumeratedReferenceStructure_key_name_class_id_type_id_enum_name_1}


```
 EnumeratedReferenceStructure(key_name, class_id, type_id, enum_name) 
```

新しいインスタンスを初期化します [EnumeratedReferenceStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumeratedreferencestructure/) クラス。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | キー名。 |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | クラス ID。 |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 型IDです。 |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | 列挙型名です。 |

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

データを保存します。

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


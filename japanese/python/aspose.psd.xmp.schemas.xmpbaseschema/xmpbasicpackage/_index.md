---
title: "XmpBasicPackage クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | 新しい [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) クラスのインスタンスを初期化します。 |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | 新しい [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | 評価の最大値。 |
| RATING_MIN [static] | int | r | 評価の最小値。 |
| RATING_REJECTED [static] | int | r | 評価の拒否値。 |
| namespace_uri | string | r | 名前空間 URI を取得します。 |
| プレフィックス | string | r | プレフィックスを取得します。 |
| xml_namespace | string | r | XML 名前空間を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 文字列プロパティを追加します。 |
| clear() | このインスタンスをクリアします。 |
| [contains_key(key)](#contains_key_key_2) | 指定されたキーがキーを含むかどうかを判定します。 |
| [get_xml_value()](#get_xml_value__3) | XMP 値を XML 表現に変換します。 |
| [remove(key)](#remove_key_4) | 指定されたキーの値を削除します。 |
| [set_created_date(created_date)](#set_created_date_created_date_5) | リソースの作成日を追加します。 |
| [set_created_date(created_date)](#set_created_date_created_date_6) | リソースの作成日を追加します。 |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | 作成ツールを設定します。 |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | 識別子を設定します。 |
| [set_label(label)](#set_label_label_9) | ラベルを設定します。 |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | メタデータの最終変更日を追加します。 |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | メタデータの最終変更日を追加します。 |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | リソースの最終更新日を追加します。 |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | リソースの最終更新日を追加します。 |
| [set_rating(choise)](#set_rating_choise_14) | 評価を設定します。 |
| [set_value(key, value)](#set_value_key_value_15) | 値を設定します。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | XMP タイプ値を設定します。 |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

新しい [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) クラスのインスタンスを初期化します。

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

新しい [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| プレフィックス | string | プレフィックスです。 |
| namespace_uri | string | 名前空間URIです。 |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

文字列プロパティを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 追加された値で識別されるキーの文字列表現です。 |
| 値 | string | 文字列値です。 |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

指定されたキーがキーを含むかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | チェックするキーです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたキーがキーを含む場合は true を返します。 |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP 値を XML 表現に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XML 表現に変換された XMP 値を返します。 |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

指定されたキーの値を削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 削除された値で識別されるキーの文字列表現です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたキーの値が削除された場合は true を返します。 |


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

リソースの作成日を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| created_date | datetime | 作成日。 |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

リソースの作成日を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| created_date | string | 作成日。 |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

作成ツールを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| creator_tool | string | ツールの名前。 |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

識別子を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| idenfifier | string | その idenfifier。 |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

ラベルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| label | string | そのラベル。 |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

メタデータの最終変更日を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| metadata_date | datetime | メタデータ日付。 |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

メタデータの最終変更日を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| metadata_date | string | メタデータ日付。 |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

リソースの最終更新日を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| modified_date | datetime | 最終更新日。 |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

リソースの最終更新日を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| modified_date | string | 最終更新日。 |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

評価を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| choise | int | -1 から 5 まで |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 追加された値で識別されるキーの文字列表現です。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 追加する値。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

XMP タイプ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 設定された値で識別されるキーの文字列表現。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 設定する値。 |


---
title: "XmpMediaManagementPackage クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | XmpMediaManagementPackage クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | 派生元を設定します。 |
| [set_document_id(guid)](#set_document_id_guid_6) | ドキュメント識別子を設定します。 |
| [set_document_id(guid)](#set_document_id_guid_7) | ドキュメント識別子を設定します。 |
| [set_instance_id(guid)](#set_instance_id_guid_8) | インスタンス ID を設定します。 |
| [set_instance_id(guid)](#set_instance_id_guid_9) | インスタンス ID を設定します。 |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | 元のドキュメント ID を設定します。 |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | 元のドキュメント ID を設定します。 |
| [set_value(key, value)](#set_value_key_value_12) | 値を設定します。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | XMP タイプ値を設定します。 |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

XmpMediaManagementPackage クラスの新しいインスタンスを初期化します。

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

派生元を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | リソース参照。 |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

ドキュメント識別子を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| guid | Guid | 一意識別子。 |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

ドキュメント識別子を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| guid | string | 一意識別子。 |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

インスタンス ID を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| guid | Guid | 一意識別子。 |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

インスタンス ID を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| guid | string | 一意識別子。 |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

元のドキュメント ID を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| guid | Guid | 一意識別子。 |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

元のドキュメント ID を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| guid | string | 一意識別子。 |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 追加された値で識別されるキーの文字列表現です。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 追加する値。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

XMP タイプ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 設定された値で識別されるキーの文字列表現。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 設定する値。 |


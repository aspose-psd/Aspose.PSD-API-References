---
title: "XmpRightsManagementPackage クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | XmpRightsManagementPackage クラスの新しいインスタンスを初期化します |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | 証明書を設定します。 |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | 権利管理コンテンツとしてマークします |
| [set_owners(owners)](#set_owners_owners_7) | 所有者を設定します。 |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | 使用条件を設定します。 |
| [set_value(key, value)](#set_value_key_value_9) | 値を設定します。 |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Web ステートメントを設定します。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | XMP タイプ値を設定します。 |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

XmpRightsManagementPackage クラスの新しいインスタンスを初期化します

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

証明書を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 証明書 | string | 証明書です。 |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

権利管理コンテンツとしてマークします

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 値 | bool | <c>true</c> に設定すると、これは権利管理リソースです。 |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

所有者を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 所有者 | string | 所有者。 |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

使用条件を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | 使用条件。 |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 追加された値で識別されるキーの文字列表現です。 |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | 追加する値。 |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Web ステートメントを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| web_statement_url | string | WebステートメントのURL。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

XMP タイプ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 設定された値で識別されるキーの文字列表現。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 設定する値。 |


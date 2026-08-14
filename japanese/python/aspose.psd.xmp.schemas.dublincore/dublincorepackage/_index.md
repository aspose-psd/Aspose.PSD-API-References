---
title: "DublinCorePackage クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Summary:** Represents Dublic Core schema.

**Module:** [aspose.psd.xmp.schemas.dublincore](/psd/python-net/aspose.psd.xmp.schemas.dublincore/)

**Full Name:** aspose.psd.xmp.schemas.dublincore.DublinCorePackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [DublinCorePackage()](#DublinCorePackage__1) | DublinCorePackage クラスの新しいインスタンスを初期化します |
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
| [set_author(author)](#set_author_author_5) | 著者を追加します。 |
| [set_author(author)](#set_author_author_6) | 著者を追加します。 |
| [set_description(desc)](#set_description_desc_7) | 説明を追加します。 |
| [set_description(desc)](#set_description_desc_8) | 説明を追加します。 |
| [set_publisher(publisher)](#set_publisher_publisher_9) | 出版社を追加します。 |
| [set_publisher(publisher)](#set_publisher_publisher_10) | 出版社を追加します。 |
| [set_subject(subject)](#set_subject_subject_11) | 主題を追加します。 |
| [set_subject(subject)](#set_subject_subject_12) | 主題を追加します。 |
| [set_title(title)](#set_title_title_13) | Dublin Core のタイトルを追加します。 |
| [set_title(title)](#set_title_title_14) | Dublin Core のタイトルを追加します。 |
| [set_value(key, value)](#set_value_key_value_15) | 値を設定します。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | XMP タイプ値を設定します。 |


### Constructor: DublinCorePackage() {#DublinCorePackage__1}


```
 DublinCorePackage() 
```

DublinCorePackage クラスの新しいインスタンスを初期化します

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


### Method: set_author(author) {#set_author_author_5}


```
 set_author(author) 
```

著者を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 著者 | string | 著者です。 |

### Method: set_author(author) {#set_author_author_6}


```
 set_author(author) 
```

著者を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 著者 | string | 著者です。 |

### Method: set_description(desc) {#set_description_desc_7}


```
 set_description(desc) 
```

説明を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 説明 | string | 説明です。 |

### Method: set_description(desc) {#set_description_desc_8}


```
 set_description(desc) 
```

説明を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| desc | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | 説明です。 |

### Method: set_publisher(publisher) {#set_publisher_publisher_9}


```
 set_publisher(publisher) 
```

出版社を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 出版社 | string | 出版社です。 |

### Method: set_publisher(publisher) {#set_publisher_publisher_10}


```
 set_publisher(publisher) 
```

出版社を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 出版社 | string | 出版社です。 |

### Method: set_subject(subject) {#set_subject_subject_11}


```
 set_subject(subject) 
```

主題を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 主題 | string | 主題です。 |

### Method: set_subject(subject) {#set_subject_subject_12}


```
 set_subject(subject) 
```

主題を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 主題 | string | 主題です。 |

### Method: set_title(title) {#set_title_title_13}


```
 set_title(title) 
```

Dublin Core のタイトルを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| title | string | タイトルです。 |

### Method: set_title(title) {#set_title_title_14}


```
 set_title(title) 
```

Dublin Core のタイトルを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| title | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | タイトルです。 |

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


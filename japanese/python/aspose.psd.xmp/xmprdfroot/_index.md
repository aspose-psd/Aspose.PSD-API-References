---
title: "XmpRdfRoot クラス"
type: docs
weight: 460
url: /ja/python-net/aspose.psd.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | XmpRdfRoot クラスの新しいインスタンスを初期化します |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | 属性を追加します。 |
| clear_attributes() | すべての属性を削除します。 |
| [get_attribute(attribute)](#get_attribute_attribute_2) | 属性を取得します。 |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | 特定のプレフィックスで名前空間 URI を取得します。プレフィックスは xmlns なしで開始できる場合があります。 |
| [get_xml_value()](#get_xml_value__4) | xmp の値を XML 表現に変換します。 |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | プレフィックスで名前空間 URI を追加します。プレフィックスは xmlns なしで開始できる場合があります。 |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

XmpRdfRoot クラスの新しいインスタンスを初期化します

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

属性を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| attribute | string | 属性です。 |
| 値 | string | 値です。 |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

属性を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| attribute | string | 属性です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | 指定された属性名の属性を返します。 |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

特定のプレフィックスで名前空間 URI を取得します。プレフィックスは xmlns なしで開始できる場合があります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| プレフィックス | string | プレフィックスです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | パッケージスキーマの URI を返します。 |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

xmp の値を XML 表現に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XMP 値を XML 文字列に変換して返します。 |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

プレフィックスで名前空間 URI を追加します。プレフィックスは xmlns なしで開始できる場合があります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| プレフィックス | string | プレフィックスです。 |
| namespace_uri | string | パッケージ スキーマ URI。 |


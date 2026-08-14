---
title: "XmpMeta クラス"
type: docs
weight: 410
url: /ja/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | 新しい [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) クラスのインスタンスを初期化します。 |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | 新しい [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Adobe Xmp ツールキットのバージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | 属性を追加します。 |
| clear_attributes() | すべての属性を削除します。 |
| [get_attribute(attribute)](#get_attribute_attribute_2) | 属性を取得します。 |
| [get_xml_value()](#get_xml_value__3) | XMP 値を XML 表現に変換します。 |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

新しい [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) クラスのインスタンスを初期化します。

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

新しい [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP ツールキットのバージョンです。 |

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


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP 値を XML 表現に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XML 表現に変換された XMP 値を返します。 |



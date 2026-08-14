---
title: "XmpArray クラス"
type: docs
weight: 290
url: /ja/python-net/aspose.psd.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/). TODO: Array may contain complex data.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpArray

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpArray(type)](#XmpArray_type_1) | 新しい [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) クラスのインスタンスを初期化します。 |
| [XmpArray(type, items)](#XmpArray_type_items_2) | 新しい [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| values | string | r | [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) 内の値の配列を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_item(item)](#add_item_item_1) | 新しい項目を追加します。 |
| [get_xml_value()](#get_xml_value__2) | XMP 値を XML 表現に変換します。 |


### Constructor: XmpArray(type) {#XmpArray_type_1}


```
 XmpArray(type) 
```

新しい [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | 配列の型です。 |

### Constructor: XmpArray(type, items) {#XmpArray_type_items_2}


```
 XmpArray(type, items) 
```

新しい [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | 配列の型です。 |
| 項目 | string | 項目のリストです。 |

### Method: add_item(item) {#add_item_item_1}


```
 add_item(item) 
```

新しい項目を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 項目 | string | 項目リストに追加される項目です。 |

### Method: get_xml_value() {#get_xml_value__2}


```
 get_xml_value() 
```

XMP 値を XML 表現に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XML 表現に変換された XMP 値を返します。 |



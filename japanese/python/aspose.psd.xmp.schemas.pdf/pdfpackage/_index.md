---
title: "PdfPackage クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | PdfPackage クラスの新しいインスタンスを初期化します。 |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | キーワードを設定します。 |
| [set_pdf_version(version)](#set_pdf_version_version_6) | PDFバージョンを設定します。 |
| [set_producer(producer)](#set_producer_producer_7) | Pdfを作成したツールの名前を設定します。 |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | トラップ状態を設定します。 |
| [set_value(key, value)](#set_value_key_value_9) | 値を設定します。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | XMP タイプ値を設定します。 |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

PdfPackage クラスの新しいインスタンスを初期化します。

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

キーワードを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| キーワード | string | キーワードです。 |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

PDFバージョンを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| version | string | Pdfバージョン（例: 1.0、1.3 など）。 |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Pdfを作成したツールの名前を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| プロデューサー | string | プロデューサー名です。 |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

トラップ状態を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| is_trapped | bool | <c>true</c> に設定されている場合、ドキュメントはトラップされています。 |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

XMP タイプ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | string | 設定された値で識別されるキーの文字列表現。 |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | 設定する値。 |


---
title: "XmpDate クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.psd.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.psd.xmp.types.basic](/psd/python-net/aspose.psd.xmp.types.basic/)

**Full Name:** aspose.psd.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) クラスの新しいインスタンスを初期化します。 |
| [XmpDate(date_time)](#XmpDate_date_time_2) | [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | ISO 8601（往復）形式の文字列です。 |
| フォーマット | string | r | 現在の値の書式文字列を取得します。 |
| 値 | datetime | r/w | 日付の値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP 形式で含まれる文字列の値を返します。 |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

[XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| date_string | string | 日付の文字列表現です。 |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

[XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| date_time | datetime | ISO RFC 8601 フォーマットのサブセットを使用して表現される日付時刻値です。 |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP 形式で含まれる文字列の値を返します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | XMP 形式で含まれる文字列の値を返します。 |



---
title: "StringFormat クラス"
type: docs
weight: 4260
url: /ja/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | 新しい[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトを初期化します。 |
| [StringFormat(format)](#StringFormat_format_2) | 指定された既存の[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトから新しい[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトを初期化します。 |
| [StringFormat(options)](#StringFormat_options_3) | 指定された[StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/)列挙体と言語を使用して新しい[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | 垂直平面上のテキスト配置情報を取得または設定します。 |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | カスタム文字識別子を取得または設定します。 |
| digit_substitution_language | int | r/w | ローカル数字が西洋数字に置き換えられる際に使用される言語を取得または設定します。 |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | 数字置換に使用される方法を取得または設定します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| first_tab_offset | float | r | テキスト行の先頭と最初のタブ位置との間のスペース数を取得します。 |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | フォーマット情報を含む [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 列挙体を取得または設定します。 |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | 汎用のデフォルト [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトを取得します。 |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | 汎用の組版用 [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトを取得します。 |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | この [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトの [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) オブジェクトを取得または設定します。 |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | 水平平面上の行揃えを取得または設定します。 |
| tab_stops | float | r | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) プロパティで指定された単位で、タブ位置間の距離の配列を取得します。 |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | この [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトの [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) 列挙体を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | この [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトのディープクローンを作成します。 |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | この [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトのタブ位置を設定します。 |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

新しい[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトを初期化します。

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

指定された既存の[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトから新しい[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 新しい [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトを初期化するための元となる [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトです。 |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

指定された[StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/)列挙体と言語を使用して新しい[StringFormat](/psd/python-net/aspose.psd/stringformat/)オブジェクトを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | 新しい [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクト用の [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) 列挙体です。 |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

この [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトのディープクローンを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | 現在の [StringFormat](/psd/python-net/aspose.psd/stringformat/) のディープクローンです。 |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

この [StringFormat](/psd/python-net/aspose.psd/stringformat/) オブジェクトのタブ位置を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| first_tab_offset | float | テキスト行の先頭と最初のタブ位置との間のスペース数です。 |
| tab_stops | float | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) プロパティで指定された単位で、タブ位置間の距離の配列です。 |


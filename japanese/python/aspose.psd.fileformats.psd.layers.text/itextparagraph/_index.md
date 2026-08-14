---
title: "ITextParagraph クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---

**Summary:** The interface to work with paragraph

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextParagraph

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| auto_hyphenate | bool | r/w | 取得または設定します。この値が[automatic hyphenate]かどうかを示します。 |
| auto_leading | double | r/w | 取得または設定します。自動リーディング。 |
| burasagari | bool | r/w | 取得または設定します。この[ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) がburasagiriかどうかを示す値。 |
| consecutive_hyphens | int | r/w | 取得または設定します。連続ハイフン。 |
| end_indent | double | r/w | 取得または設定します。終了インデント。 |
| every_line_composer | bool | r/w | 取得または設定します。この値が[every line composer]かどうかを示します。 |
| first_line_indent | double | r/w | 取得または設定します。最初の行インデント。 |
| glyph_spacing | double | r/w | 取得または設定します。グリフ間隔。 |
| hanging | bool | r/w | 取得または設定します。この[ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph/) がハンギングかどうかを示す値。 |
| hyphenated_word_size | int | r/w | 取得または設定します。ハイフン付き単語のサイズ。 |
| justification | [JustificationMode](/psd/python-net/aspose.psd.fileformats.psd/justificationmode) | r/w | 取得または設定します。配置。 |
| kinsoku_order | int | r/w | 取得または設定します。禁則順序。 |
| leading_type | [LeadingType](/psd/python-net/aspose.psd.fileformats.psd/leadingtype) | r/w | 取得または設定します。リーディングのタイプ。 |
| letter_spacing | double | r/w | 取得または設定します。文字間隔。 |
| post_hyphen | int | r/w | 後置ハイフンを取得または設定します。 |
| pre_hyphen | int | r/w | 前置ハイフンを取得または設定します。 |
| space_after | double | r/w | 後のスペースを取得または設定します。 |
| space_before | double | r/w | 前のスペースを取得または設定します。 |
| start_indent | double | r/w | 開始インデントを取得または設定します。 |
| word_spacing | double | r/w | 単語間隔を取得または設定します。 |
| zone | double | r/w | ゾーンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [apply(paragraph)](#apply_paragraph_1) | 指定された段落を適用します。 |
| [is_equal(paragraph)](#is_equal_paragraph_2) | 指定された段落が等しいかどうかを判断します。 |


### Method: apply(paragraph) {#apply_paragraph_1}


```
 apply(paragraph) 
```

指定された段落を適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

### Method: is_equal(paragraph) {#is_equal_paragraph_2}


```
 is_equal(paragraph) 
```

指定された段落が等しいかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| paragraph | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された段落が等しい場合は<c>true</c>、それ以外の場合は<c>false</c>です。 |



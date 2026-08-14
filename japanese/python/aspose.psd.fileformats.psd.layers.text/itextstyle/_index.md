---
title: "ITextStyle クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | 自動カーニングを取得または設定します。 |
| auto_leading | bool | r/w | 自動リーディングかどうかを示す値を取得または設定します。 |
| baseline_shift | double | r/w | ベースラインシフトです。 |
| contextual_alternates | bool | r/w | 文字を結合するために使用される文脈依存代替文字です。 |
| discretionary_ligatures | bool | r/w | 文字を結合するために使用される任意の合字は、特にスクリプトフォントで使用されます。 |
| faux_bold | bool | r/w | 偽ボールドが有効かどうかを取得または設定します。 |
| faux_italic | bool | r/w | 偽ボールドが有効かどうかを取得または設定します。 |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 塗りつぶしの色を取得または設定します。 |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | フォントのベースラインです。 |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | フォントの大文字です。 |
| font_index | int | r | フォントインデックスを取得します。 |
| font_name | string | r/w | フォント名を取得または設定します。 |
| font_size | double | r/w | フォントのサイズを取得または設定します。 |
| fractions | bool | r/w | 分数記号は特別なグリフに置き換えることができます。 |
| hindi_numbers | bool | r/w | 値を取得または設定し、[hindi numbers]かどうかを示します。 |
| horizontal_scale | double | r/w | 水平スケールです。 |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | 標準の垂直ローマン配置を取得または設定します。<br/>            これは BaselineDirection リソース値に基づき、テキストの向きが [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/) の場合にのみ適用されます。 |
| kerning | int | r/w | カーニングを取得または設定します。 |
| language_index | int | r | 言語インデックスを取得します。 |
| leading | double | r/w | リーディングを取得または設定します。 |
| no_break | bool | r/w | 改行なしの値を取得または設定します。 |
| standard_ligatures | bool | r/w | 文字を結合するために使用される標準的な文脈依存リガチャです。 |
| strikethrough | bool | r/w | [strikethrough] が有効かどうかを示す値を取得または設定します。 |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | ストロークの色を取得または設定します。 |
| tracking | int | r/w | トラッキングを取得または設定します。 |
| underline | bool | r/w | [underline] が有効かどうかを示す値を取得または設定します。 |
| vertical_scale | double | r/w | 垂直スケールです。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [apply(style)](#apply_style_1) | 指定されたスタイルを適用します。 |
| [is_equal(style)](#is_equal_style_2) | 指定されたスタイルが等しいかどうかを判定します。 |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

指定されたスタイルを適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | スタイルです。 |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

指定されたスタイルが等しいかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | スタイルです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <c>true</c> は指定されたスタイルが等しい場合、そうでなければ <c>false</c> です。 |



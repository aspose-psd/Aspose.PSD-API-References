---
title: "IText クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | 項目を取得します。 |
| text | string | r | テキストを取得します。 |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | テキストの向きを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | テキストの部分を末尾に追加します |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | 指定した位置に[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)を挿入します |
| [produce_portion()](#produce_portion__3) | デフォルトパラメータで新しい部分を生成します |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | 入力またはデフォルトパラメータで新しい部分を生成します。 |
| [remove_portion(index)](#remove_portion_index_5) | 指定されたインデックスの部分を削除します |
| update_layer_data() | レイヤーデータを更新します。 |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

テキストの部分を末尾に追加します

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | その部分。 |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

指定した位置に[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)を挿入します

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | その部分。 |
| index | int | インデックスです。 |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

デフォルトパラメータで新しい部分を生成します

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 新しく作成された[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)への参照です。 |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

入力またはデフォルトパラメータで新しい部分を生成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| portions_of_text | string | 新しい[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)を作成するテキストの部分です。 |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | nullでない場合、新しい[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)に適用され、nullの場合はデフォルトになります。 |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | nullでない場合、新しい[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)に適用され、nullの場合はデフォルトになります。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | 入力パラメータに基づいて新しい[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/)の部分を返します。 |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

指定されたインデックスの部分を削除します

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| index | int | インデックスです。 |


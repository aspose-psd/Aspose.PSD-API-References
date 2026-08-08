---
title: "IText"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "テキスト レイヤーのテキスト編集用インターフェイス"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

テキスト レイヤーのテキスト編集用インターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | テキストの部分を末尾に追加します |
| [getItems()](#getItems--) | 項目を取得します。 |
| [getText()](#getText--) | テキストを取得します。 |
| [getTextOrientation()](#getTextOrientation--) | テキストの向きを取得または設定します。 |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | 指定された位置に [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) を挿入します |
| [producePortion()](#producePortion--) | デフォルトパラメーターで新しい部分を生成します |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 入力またはデフォルトのパラメータで新しい部分を生成します。 |
| [removePortion(int index)](#removePortion-int-) | 指定されたインデックスの部分を削除します |
| [setTextOrientation(int value)](#setTextOrientation-int-) | テキストの向きを取得または設定します。 |
| [updateLayerData()](#updateLayerData--) | レイヤー データを更新します。 |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


テキストの部分を末尾に追加します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | その部分。 |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


項目を取得します。

値: アイテム。

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


テキストを取得します。

値: テキスト。

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


テキストの向きを取得または設定します。

値: テキストの向き。

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


指定された位置に [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) を挿入します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | その部分。 |
| index | int | インデックス。 |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


デフォルトパラメーターで新しい部分を生成します

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


入力またはデフォルトのパラメータで新しい部分を生成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | 新しい ITextPortion を作成するテキストの部分。 |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | null でない場合は新しい   に適用され、そうでない場合はデフォルトになります。 |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | null でない場合は新しい   に適用され、そうでない場合はデフォルトになります。 |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - 入力パラメータに基づいて新しい ITextPortion 部分を返します。
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


指定されたインデックスの部分を削除します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | インデックス。 |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


テキストの向きを取得または設定します。

値: テキストの向き。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


レイヤー データを更新します。


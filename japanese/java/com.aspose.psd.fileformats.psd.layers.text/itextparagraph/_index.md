---
title: "ITextParagraph"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "段落を操作するためのインターフェイス"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

段落を操作するためのインターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 指定された段落を適用します。 |
| [getAutoHyphenate()](#getAutoHyphenate--) | 自動ハイフネーションかどうかを示す値を取得または設定します。[automatic hyphenate] |
| [getAutoLeading()](#getAutoLeading--) | 自動リーディングを取得または設定します。 |
| [getBurasagari()](#getBurasagari--) | この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がburasagiriかどうかを示す値を取得または設定します。 |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | 連続ハイフンを取得または設定します。 |
| [getEndIndent()](#getEndIndent--) | 行末インデントを取得または設定します。 |
| [getEveryLineComposer()](#getEveryLineComposer--) | 毎行コンポーザーかどうかを示す値を取得または設定します。[every line composer] |
| [getFirstLineIndent()](#getFirstLineIndent--) | 最初の行インデントを取得または設定します。 |
| [getGlyphSpacing()](#getGlyphSpacing--) | グリフ間隔を取得または設定します。 |
| [getHanging()](#getHanging--) | この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がハンギングかどうかを示す値を取得または設定します。 |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | ハイフン付き単語のサイズを取得または設定します。 |
| [getJustification()](#getJustification--) | 行揃えを取得または設定します。 |
| [getKinsokuOrder()](#getKinsokuOrder--) | 禁則順序を取得または設定します。 |
| [getLeadingType()](#getLeadingType--) | リーディングのタイプを取得または設定します。 |
| [getLetterSpacing()](#getLetterSpacing--) | 文字間隔を取得または設定します。 |
| [getPostHyphen()](#getPostHyphen--) | ポストハイフンを取得または設定します。 |
| [getPreHyphen()](#getPreHyphen--) | 前ハイフンを取得または設定します。 |
| [getSpaceAfter()](#getSpaceAfter--) | 後のスペースを取得または設定します。 |
| [getSpaceBefore()](#getSpaceBefore--) | 前のスペースを取得または設定します。 |
| [getStartIndent()](#getStartIndent--) | 開始インデントを取得または設定します。 |
| [getWordSpacing()](#getWordSpacing--) | 単語間隔を取得または設定します。 |
| [getZone()](#getZone--) | ゾーンを取得または設定します。 |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | 指定された段落が等しいかどうかを判断します。 |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | 自動ハイフネーションかどうかを示す値を取得または設定します。[automatic hyphenate] |
| [setAutoLeading(double value)](#setAutoLeading-double-) | 自動リーディングを取得または設定します。 |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がburasagiriかどうかを示す値を取得または設定します。 |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | 連続ハイフンを取得または設定します。 |
| [setEndIndent(double value)](#setEndIndent-double-) | 行末インデントを取得または設定します。 |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | 毎行コンポーザーかどうかを示す値を取得または設定します。[every line composer] |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | 最初の行インデントを取得または設定します。 |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | グリフ間隔を取得または設定します。 |
| [setHanging(boolean value)](#setHanging-boolean-) | この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がハンギングかどうかを示す値を取得または設定します。 |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | ハイフン付き単語のサイズを取得または設定します。 |
| [setJustification(int value)](#setJustification-int-) | 行揃えを取得または設定します。 |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | 禁則順序を取得または設定します。 |
| [setLeadingType(int value)](#setLeadingType-int-) | リーディングのタイプを取得または設定します。 |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | 文字間隔を取得または設定します。 |
| [setPostHyphen(int value)](#setPostHyphen-int-) | ポストハイフンを取得または設定します。 |
| [setPreHyphen(int value)](#setPreHyphen-int-) | 前ハイフンを取得または設定します。 |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | 後のスペースを取得または設定します。 |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | 前のスペースを取得または設定します。 |
| [setStartIndent(double value)](#setStartIndent-double-) | 開始インデントを取得または設定します。 |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | 単語間隔を取得または設定します。 |
| [setZone(double value)](#setZone-double-) | ゾーンを取得または設定します。 |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


指定された段落を適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


自動ハイフネーションかどうかを示す値を取得または設定します。[automatic hyphenate]

値:  true  の場合は[automatic hyphenate]、それ以外の場合は  false 。

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


自動リーディングを取得または設定します。

値: 自動リーディング。

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がburasagiriかどうかを示す値を取得または設定します。

値:  true  の場合はburasagiri、それ以外の場合は  false 。

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


連続ハイフンを取得または設定します。

値: 連続ハイフン。

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


行末インデントを取得または設定します。

値: 終了インデント。

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


毎行コンポーザーかどうかを示す値を取得または設定します。[every line composer]

値:  true  の場合は[every line composer]、それ以外の場合は  false 。

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


最初の行インデントを取得または設定します。

値: 最初の行インデント。

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


グリフ間隔を取得または設定します。

値: グリフ間隔。

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がハンギングかどうかを示す値を取得または設定します。

値:  true  の場合はhanging、それ以外の場合は  false 。

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


ハイフン付き単語のサイズを取得または設定します。

値: ハイフン付き単語のサイズ。

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


行揃えを取得または設定します。

値: 行揃え。

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


禁則順序を取得または設定します。

値: 禁則順序。

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


リーディングのタイプを取得または設定します。

値: リーディングのタイプ。

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


文字間隔を取得または設定します。

値: 文字間隔。

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


ポストハイフンを取得または設定します。

値: 後ハイフン。

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


前ハイフンを取得または設定します。

値: 前ハイフン。

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


後のスペースを取得または設定します。

値: 後のスペース。

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


前のスペースを取得または設定します。

値: 前のスペース。

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


開始インデントを取得または設定します。

値: 開始インデント。

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


単語間隔を取得または設定します。

値: 単語間隔。

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


ゾーンを取得または設定します。

値: ゾーン。

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


指定された段落が等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | 段落。 |

**Returns:**
ブール型 - 指定された段落が等しい場合は true、そうでない場合は false。
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


自動ハイフネーションかどうかを示す値を取得または設定します。[automatic hyphenate]

値:  true  の場合は[automatic hyphenate]、それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


自動リーディングを取得または設定します。

値: 自動リーディング。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がburasagiriかどうかを示す値を取得または設定します。

値:  true  の場合はburasagiri、それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


連続ハイフンを取得または設定します。

値: 連続ハイフン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


行末インデントを取得または設定します。

値: 終了インデント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


毎行コンポーザーかどうかを示す値を取得または設定します。[every line composer]

値:  true  の場合は[every line composer]、それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


最初の行インデントを取得または設定します。

値: 最初の行インデント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


グリフ間隔を取得または設定します。

値: グリフ間隔。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


この [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) がハンギングかどうかを示す値を取得または設定します。

値:  true  の場合はhanging、それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


ハイフン付き単語のサイズを取得または設定します。

値: ハイフン付き単語のサイズ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


行揃えを取得または設定します。

値: 行揃え。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


禁則順序を取得または設定します。

値: 禁則順序。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


リーディングのタイプを取得または設定します。

値: リーディングのタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


文字間隔を取得または設定します。

値: 文字間隔。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


ポストハイフンを取得または設定します。

値: 後ハイフン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


前ハイフンを取得または設定します。

値: 前ハイフン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


後のスペースを取得または設定します。

値: 後のスペース。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


前のスペースを取得または設定します。

値: 前のスペース。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


開始インデントを取得または設定します。

値: 開始インデント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


単語間隔を取得または設定します。

値: 単語間隔。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


ゾーンを取得または設定します。

値: ゾーン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |


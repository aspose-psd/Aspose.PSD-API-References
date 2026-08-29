---
title: "ITextStyle"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "テキスト スタイルを操作するインターフェイス"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

テキスト スタイルを操作するインターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | 指定されたスタイルを適用します。 |
| [getAutoKerning()](#getAutoKerning--) | 自動カーニングを取得または設定します。 |
| [getAutoLeading()](#getAutoLeading--) | 自動リーディングかどうかを示す値を取得または設定します。[automatic leading] |
| [getBaselineShift()](#getBaselineShift--) | ベースラインシフト。 |
| [getContextualAlternates()](#getContextualAlternates--) | 文字を結合するために使用される文脈代替。 |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | 特にスクリプトフォントで文字を結合するために使用される任意の合字。 |
| [getFauxBold()](#getFauxBold--) | フェイクボールドが有効かどうかを取得または設定します。 |
| [getFauxItalic()](#getFauxItalic--) | フェイクボールドが有効かどうかを取得または設定します。 |
| [getFillColor()](#getFillColor--) | 塗りつぶしの色を取得または設定します。 |
| [getFontBaseline()](#getFontBaseline--) | フォントのベースライン。 |
| [getFontCaps()](#getFontCaps--) | フォントの大文字。 |
| [getFontIndex()](#getFontIndex--) | フォントインデックスを取得します。 |
| [getFontName()](#getFontName--) | フォント名を取得または設定します。 |
| [getFontSize()](#getFontSize--) | フォントサイズを取得または設定します。 |
| [getFractions()](#getFractions--) | 分数記号は特別なグリフに置き換えることができます。 |
| [getHindiNumbers()](#getHindiNumbers--) | ヒンディー数字かどうかを示す値を取得または設定します。[hindi numbers] |
| [getHorizontalScale()](#getHorizontalScale--) | 水平スケール。 |
| [getKerning()](#getKerning--) | カーニングを取得または設定します。 |
| [getLanguageIndex()](#getLanguageIndex--) | 言語インデックスを取得します。 |
| [getLeading()](#getLeading--) | リーディングを取得または設定します。 |
| [getStandardLigatures()](#getStandardLigatures--) | 文字を結合するために使用される標準的な文脈依存リガチャです。 |
| [getStrikethrough()](#getStrikethrough--) | 取り消し線かどうかを示す値を取得または設定します。[strikethrough] |
| [getStrokeColor()](#getStrokeColor--) | ストロークの色を取得または設定します。 |
| [getTracking()](#getTracking--) | トラッキングを取得または設定します。 |
| [getUnderline()](#getUnderline--) | 下線かどうかを示す値を取得または設定します。[underline] |
| [getVerticalScale()](#getVerticalScale--) | 垂直スケールです。 |
| [get_noBreak()](#get-noBreak--) | 改行禁止値を取得または設定します。 |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | 指定されたスタイルが等しいかどうかを判定します。 |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | 標準の垂直ローマン配置を取得または設定します。 |
| [setAutoKerning(int value)](#setAutoKerning-int-) | 自動カーニングを取得または設定します。 |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | 自動リーディングかどうかを示す値を取得または設定します。[automatic leading] |
| [setBaselineShift(double value)](#setBaselineShift-double-) | ベースラインシフト。 |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | 文字を結合するために使用される文脈代替。 |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | 特にスクリプトフォントで文字を結合するために使用される任意の合字。 |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | フェイクボールドが有効かどうかを取得または設定します。 |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | フェイクボールドが有効かどうかを取得または設定します。 |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | 塗りつぶしの色を取得または設定します。 |
| [setFontBaseline(int value)](#setFontBaseline-int-) | フォントのベースライン。 |
| [setFontCaps(int value)](#setFontCaps-int-) | フォントの大文字。 |
| [setFontName(String value)](#setFontName-java.lang.String-) | フォント名を取得または設定します。 |
| [setFontSize(double value)](#setFontSize-double-) | フォントサイズを取得または設定します。 |
| [setFractions(boolean value)](#setFractions-boolean-) | 分数記号は特別なグリフに置き換えることができます。 |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | ヒンディー数字かどうかを示す値を取得または設定します。[hindi numbers] |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | 水平スケール。 |
| [setKerning(int value)](#setKerning-int-) | カーニングを取得または設定します。 |
| [setLeading(double value)](#setLeading-double-) | リーディングを取得または設定します。 |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | 文字を結合するために使用される標準的な文脈依存リガチャです。 |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | 取り消し線かどうかを示す値を取得または設定します。[strikethrough] |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | ストロークの色を取得または設定します。 |
| [setTracking(int value)](#setTracking-int-) | トラッキングを取得または設定します。 |
| [setUnderline(boolean value)](#setUnderline-boolean-) | 下線かどうかを示す値を取得または設定します。[underline] |
| [setVerticalScale(double value)](#setVerticalScale-double-) | 垂直スケールです。 |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | 標準の垂直ローマン配置を取得または設定します。 |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | 改行禁止値を取得または設定します。 |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


指定されたスタイルを適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | スタイルです。 |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


自動カーニングを取得または設定します。

値: 2文字間の自動カーニングです。

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


自動リーディングかどうかを示す値を取得または設定します。[automatic leading]

値:  true  が [automatic leading] の場合; それ以外の場合は false です。

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


ベースラインシフト。

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


文字を結合するために使用される文脈代替。

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


特にスクリプトフォントで文字を結合するために使用される任意の合字。

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


フェイクボールドが有効かどうかを取得または設定します。

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


フェイクボールドが有効かどうかを取得または設定します。

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


塗りつぶしの色を取得または設定します。

値: 塗りつぶしの色です。

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


フォントのベースライン。

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


フォントの大文字。

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


フォントインデックスを取得します。

値: フォントです。

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


フォント名を取得または設定します。

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


フォントサイズを取得または設定します。

値: フォントのサイズです。

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


分数記号は特別なグリフに置き換えることができます。

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


ヒンディー数字かどうかを示す値を取得または設定します。[hindi numbers]

値:  true  が [hindi numbers] の場合; それ以外の場合は false です。

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


水平スケール。

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


カーニングを取得または設定します。

値: 2文字間のカーニングです。

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


言語インデックスを取得します。

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


リーディングを取得または設定します。

値: リーディングです。

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


文字を結合するために使用される標準的な文脈依存リガチャです。

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


取り消し線かどうかを示す値を取得または設定します。[strikethrough]

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


ストロークの色を取得または設定します。

値: ストロークの色です。

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


トラッキングを取得または設定します。

値: トラッキングです。

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


下線かどうかを示す値を取得または設定します。[underline]

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


垂直スケールです。

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


改行禁止値を取得または設定します。

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


指定されたスタイルが等しいかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | スタイルです。 |

**Returns:**
ブール -  true  が指定されたスタイルが等しい場合; それ以外の場合は false。
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


標準の垂直ローマン配置を取得または設定します。これは BaselineDirection リソース値に基づき、テキストの向きが [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) の場合にのみ適用されます。

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


自動カーニングを取得または設定します。

値: 2文字間の自動カーニングです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


自動リーディングかどうかを示す値を取得または設定します。[automatic leading]

値:  true  が [automatic leading] の場合; それ以外の場合は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


ベースラインシフト。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


文字を結合するために使用される文脈代替。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


特にスクリプトフォントで文字を結合するために使用される任意の合字。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


フェイクボールドが有効かどうかを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


フェイクボールドが有効かどうかを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


塗りつぶしの色を取得または設定します。

値: 塗りつぶしの色です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


フォントのベースライン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


フォントの大文字。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


フォント名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


フォントサイズを取得または設定します。

値: フォントのサイズです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


分数記号は特別なグリフに置き換えることができます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


ヒンディー数字かどうかを示す値を取得または設定します。[hindi numbers]

値:  true  が [hindi numbers] の場合; それ以外の場合は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


水平スケール。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


カーニングを取得または設定します。

値: 2文字間のカーニングです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


リーディングを取得または設定します。

値: リーディングです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


文字を結合するために使用される標準的な文脈依存リガチャです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


取り消し線かどうかを示す値を取得または設定します。[strikethrough]

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


ストロークの色を取得または設定します。

値: ストロークの色です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


トラッキングを取得または設定します。

値: トラッキングです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


下線かどうかを示す値を取得または設定します。[underline]

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


垂直スケールです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


標準の垂直ローマン配置を取得または設定します。これは BaselineDirection リソース値に基づき、テキストの向きが [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) の場合にのみ適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


改行禁止値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |


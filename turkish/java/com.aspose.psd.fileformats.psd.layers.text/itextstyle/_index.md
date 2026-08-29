---
title: "ITextStyle"
second_title: "Java için Aspose.PSD API Referansı"
description: "Metin Stili ile çalışmak için arayüz"
type: docs
weight: 14
url: /tr/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Metin Stili ile çalışmak için arayüz
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Belirtilen stili uygular. |
| [getAutoKerning()](#getAutoKerning--) | Otomatik kerning'i alır veya ayarlar. |
| [getAutoLeading()](#getAutoLeading--) | Bir değeri alır veya ayarlar; bu değer [automatic leading] gösterip göstermediğini belirtir. |
| [getBaselineShift()](#getBaselineShift--) | Taban çizgisi kayması. |
| [getContextualAlternates()](#getContextualAlternates--) | Harfleri birleştirmek için kullanılan bağlamsal alternatifler. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Özellikle el yazısı fontlarda harfleri birleştirmek için kullanılan isteğe bağlı ligatürler. |
| [getFauxBold()](#getFauxBold--) | Yapay faux bold etkin olup olmadığını alır veya ayarlar. |
| [getFauxItalic()](#getFauxItalic--) | Yapay faux bold etkin olup olmadığını alır veya ayarlar. |
| [getFillColor()](#getFillColor--) | Dolgunun rengini alır veya ayarlar. |
| [getFontBaseline()](#getFontBaseline--) | Yazı tipi taban çizgisi. |
| [getFontCaps()](#getFontCaps--) | Yazı tipi büyük harfleri. |
| [getFontIndex()](#getFontIndex--) | Yazı tipi indeksini alır. |
| [getFontName()](#getFontName--) | Yazı tipi adını alır veya ayarlar. |
| [getFontSize()](#getFontSize--) | Yazı tipi boyutunu alır veya ayarlar. |
| [getFractions()](#getFractions--) | Kesir sembolleri özel glif ile değiştirilebilir. |
| [getHindiNumbers()](#getHindiNumbers--) | Bir değeri alır veya ayarlar; bu değer [hindi numbers] gösterip göstermediğini belirtir. |
| [getHorizontalScale()](#getHorizontalScale--) | Yatay ölçek. |
| [getKerning()](#getKerning--) | Kerning'i alır veya ayarlar. |
| [getLanguageIndex()](#getLanguageIndex--) | Dil indeksini alır. |
| [getLeading()](#getLeading--) | Leading'i alır veya ayarlar. |
| [getStandardLigatures()](#getStandardLigatures--) | Harfleri birleştirmek için kullanılan standart bağlamsal ligatürler. |
| [getStrikethrough()](#getStrikethrough--) | Çizgi üzerinden geçme [strikethrough] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getStrokeColor()](#getStrokeColor--) | Çizginin rengini alır veya ayarlar. |
| [getTracking()](#getTracking--) | İzlemeyi alır veya ayarlar. |
| [getUnderline()](#getUnderline--) | Alt çizgi [underline] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getVerticalScale()](#getVerticalScale--) | Dikey ölçek. |
| [get_noBreak()](#get-noBreak--) | Kesintisiz değerini alır veya ayarlar. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Belirtilen stilin eşit olup olmadığını belirler. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Standart dikey Roma hizalamasını alır veya ayarlar. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Otomatik kerning'i alır veya ayarlar. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Bir değeri alır veya ayarlar; bu değer [automatic leading] gösterip göstermediğini belirtir. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Taban çizgisi kayması. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Harfleri birleştirmek için kullanılan bağlamsal alternatifler. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Özellikle el yazısı fontlarda harfleri birleştirmek için kullanılan isteğe bağlı ligatürler. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Yapay faux bold etkin olup olmadığını alır veya ayarlar. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Yapay faux bold etkin olup olmadığını alır veya ayarlar. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Dolgunun rengini alır veya ayarlar. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | Yazı tipi taban çizgisi. |
| [setFontCaps(int value)](#setFontCaps-int-) | Yazı tipi büyük harfleri. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Yazı tipi adını alır veya ayarlar. |
| [setFontSize(double value)](#setFontSize-double-) | Yazı tipi boyutunu alır veya ayarlar. |
| [setFractions(boolean value)](#setFractions-boolean-) | Kesir sembolleri özel glif ile değiştirilebilir. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Bir değeri alır veya ayarlar; bu değer [hindi numbers] gösterip göstermediğini belirtir. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | Yatay ölçek. |
| [setKerning(int value)](#setKerning-int-) | Kerning'i alır veya ayarlar. |
| [setLeading(double value)](#setLeading-double-) | Leading'i alır veya ayarlar. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Harfleri birleştirmek için kullanılan standart bağlamsal ligatürler. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Çizgi üzerinden geçme [strikethrough] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Çizginin rengini alır veya ayarlar. |
| [setTracking(int value)](#setTracking-int-) | İzlemeyi alır veya ayarlar. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Alt çizgi [underline] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | Dikey ölçek. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Standart dikey Roma hizalamasını alır veya ayarlar. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Kesintisiz değerini alır veya ayarlar. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Belirtilen stili uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Stil. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Otomatik kerning'i alır veya ayarlar.

Değer: İki karakter arasındaki otomatik kerning.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Bir değeri alır veya ayarlar; bu değer [automatic leading] gösterip göstermediğini belirtir.

Değer:  true  eğer [automatic leading]; aksi takdirde,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Taban çizgisi kayması.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Harfleri birleştirmek için kullanılan bağlamsal alternatifler.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Özellikle el yazısı fontlarda harfleri birleştirmek için kullanılan isteğe bağlı ligatürler.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Yapay faux bold etkin olup olmadığını alır veya ayarlar.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Yapay faux bold etkin olup olmadığını alır veya ayarlar.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Dolgunun rengini alır veya ayarlar.

Değer: Dolgunun rengi.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


Yazı tipi taban çizgisi.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Yazı tipi büyük harfleri.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Yazı tipi indeksini alır.

Değer: Yazı tipi.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Yazı tipi adını alır veya ayarlar.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Yazı tipi boyutunu alır veya ayarlar.

Değer: Yazı tipinin boyutu.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Kesir sembolleri özel glif ile değiştirilebilir.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Bir değeri alır veya ayarlar; bu değer [hindi numbers] gösterip göstermediğini belirtir.

Değer:  true  eğer [hindi numbers]; aksi takdirde,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


Yatay ölçek.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Kerning'i alır veya ayarlar.

Değer: İki karakter arasındaki kerning.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Dil indeksini alır.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Leading'i alır veya ayarlar.

Değer: Satır aralığı.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Harfleri birleştirmek için kullanılan standart bağlamsal ligatürler.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Çizgi üzerinden geçme [strikethrough] olup olmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Çizginin rengini alır veya ayarlar.

Değer: Çizginin rengi.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


İzlemeyi alır veya ayarlar.

Değer: İzleme.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Alt çizgi [underline] olup olmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


Dikey ölçek.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Kesintisiz değerini alır veya ayarlar.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Belirtilen stilin eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Stil. |

**Returns:**
boolean -  true  eğer belirtilen stil eşitse; aksi takdirde,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Standart dikey Roma hizalamasını alır veya ayarlar. Bu, BaselineDirection kaynak değerine dayanır ve yalnızca metin yönelimi [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) olduğunda uygulanır.

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Otomatik kerning'i alır veya ayarlar.

Değer: İki karakter arasındaki otomatik kerning.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Bir değeri alır veya ayarlar; bu değer [automatic leading] gösterip göstermediğini belirtir.

Değer:  true  eğer [automatic leading]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Taban çizgisi kayması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Harfleri birleştirmek için kullanılan bağlamsal alternatifler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Özellikle el yazısı fontlarda harfleri birleştirmek için kullanılan isteğe bağlı ligatürler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Yapay faux bold etkin olup olmadığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Yapay faux bold etkin olup olmadığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Dolgunun rengini alır veya ayarlar.

Değer: Dolgunun rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


Yazı tipi taban çizgisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Yazı tipi büyük harfleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Yazı tipi adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Yazı tipi boyutunu alır veya ayarlar.

Değer: Yazı tipinin boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Kesir sembolleri özel glif ile değiştirilebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Bir değeri alır veya ayarlar; bu değer [hindi numbers] gösterip göstermediğini belirtir.

Değer:  true  eğer [hindi numbers]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


Yatay ölçek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Kerning'i alır veya ayarlar.

Değer: İki karakter arasındaki kerning.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Leading'i alır veya ayarlar.

Değer: Satır aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Harfleri birleştirmek için kullanılan standart bağlamsal ligatürler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Çizgi üzerinden geçme [strikethrough] olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Çizginin rengini alır veya ayarlar.

Değer: Çizginin rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


İzlemeyi alır veya ayarlar.

Değer: İzleme.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Alt çizgi [underline] olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


Dikey ölçek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Standart dikey Roma hizalamasını alır veya ayarlar. Bu, BaselineDirection kaynak değerine dayanır ve yalnızca metin yönelimi [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) olduğunda uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Kesintisiz değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |


---
title: "ITextStyle"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Antarmuka untuk bekerja dengan Gaya Teks"
type: docs
weight: 14
url: /id/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Antarmuka untuk bekerja dengan Gaya Teks
## Metode

| Metode | Deskripsi |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Menerapkan gaya yang ditentukan. |
| [getAutoKerning()](#getAutoKerning--) | Mendapatkan atau mengatur auto kerning. |
| [getAutoLeading()](#getAutoLeading--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | Perpindahan baseline. |
| [getContextualAlternates()](#getContextualAlternates--) | Alternatif kontekstual yang digunakan untuk menghubungkan huruf bersama-sama. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Ligatur diskresi yang digunakan untuk menghubungkan huruf, terutama dalam font skrip. |
| [getFauxBold()](#getFauxBold--) | Mendapatkan atau mengatur apakah faux bold diaktifkan. |
| [getFauxItalic()](#getFauxItalic--) | Mendapatkan atau mengatur apakah faux bold diaktifkan. |
| [getFillColor()](#getFillColor--) | Mendapatkan atau mengatur warna isian. |
| [getFontBaseline()](#getFontBaseline--) | Garis dasar font. |
| [getFontCaps()](#getFontCaps--) | Huruf kapital font. |
| [getFontIndex()](#getFontIndex--) | Mendapatkan indeks font. |
| [getFontName()](#getFontName--) | Mendapatkan atau mengatur nama font. |
| [getFontSize()](#getFontSize--) | Mendapatkan atau mengatur ukuran font. |
| [getFractions()](#getFractions--) | Simbol pecahan dapat diganti dengan glif khusus. |
| [getHindiNumbers()](#getHindiNumbers--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | Skala horizontal. |
| [getKerning()](#getKerning--) | Mendapatkan atau mengatur kerning. |
| [getLanguageIndex()](#getLanguageIndex--) | Mendapatkan indeks bahasa. |
| [getLeading()](#getLeading--) | Mendapatkan atau mengatur leading. |
| [getStandardLigatures()](#getStandardLigatures--) | Ligatur kontekstual standar yang digunakan untuk menghubungkan huruf bersama-sama. |
| [getStrikethrough()](#getStrikethrough--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Mendapatkan atau mengatur warna goresan. |
| [getTracking()](#getTracking--) | Mendapatkan atau mengatur tracking. |
| [getUnderline()](#getUnderline--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [underline]. |
| [getVerticalScale()](#getVerticalScale--) | Skala vertikal. |
| [get_noBreak()](#get-noBreak--) | Mendapatkan atau mengatur nilai no break. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Menentukan apakah gaya yang ditentukan sama. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Mendapatkan atau mengatur perataan Romawi vertikal standar. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Mendapatkan atau mengatur auto kerning. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Perpindahan baseline. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Alternatif kontekstual yang digunakan untuk menghubungkan huruf bersama-sama. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Ligatur diskresi yang digunakan untuk menghubungkan huruf, terutama dalam font skrip. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Mendapatkan atau mengatur apakah faux bold diaktifkan. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Mendapatkan atau mengatur apakah faux bold diaktifkan. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur warna isian. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | Garis dasar font. |
| [setFontCaps(int value)](#setFontCaps-int-) | Huruf kapital font. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Mendapatkan atau mengatur nama font. |
| [setFontSize(double value)](#setFontSize-double-) | Mendapatkan atau mengatur ukuran font. |
| [setFractions(boolean value)](#setFractions-boolean-) | Simbol pecahan dapat diganti dengan glif khusus. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | Skala horizontal. |
| [setKerning(int value)](#setKerning-int-) | Mendapatkan atau mengatur kerning. |
| [setLeading(double value)](#setLeading-double-) | Mendapatkan atau mengatur leading. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Ligatur kontekstual standar yang digunakan untuk menghubungkan huruf bersama-sama. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Mendapatkan atau mengatur warna goresan. |
| [setTracking(int value)](#setTracking-int-) | Mendapatkan atau mengatur tracking. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | Skala vertikal. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Mendapatkan atau mengatur perataan Romawi vertikal standar. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Mendapatkan atau mengatur nilai no break. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Menerapkan gaya yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Gaya. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Mendapatkan atau mengatur auto kerning.

Value: Kerning otomatis antara dua karakter.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [automatic leading].

Value:  true  jika [automatic leading]; selain itu,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Perpindahan baseline.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Alternatif kontekstual yang digunakan untuk menghubungkan huruf bersama-sama.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Ligatur diskresi yang digunakan untuk menghubungkan huruf, terutama dalam font skrip.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Mendapatkan atau mengatur apakah faux bold diaktifkan.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Mendapatkan atau mengatur apakah faux bold diaktifkan.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Mendapatkan atau mengatur warna isian.

Value: Warna isian.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


Garis dasar font.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Huruf kapital font.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Mendapatkan indeks font.

Value: Font.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Mendapatkan atau mengatur nama font.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Mendapatkan atau mengatur ukuran font.

Value: Ukuran font.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Simbol pecahan dapat diganti dengan glif khusus.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [hindi numbers].

Value:  true  jika [hindi numbers]; selain itu,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


Skala horizontal.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Mendapatkan atau mengatur kerning.

Value: Kerning antara dua karakter.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Mendapatkan indeks bahasa.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Mendapatkan atau mengatur leading.

Value: Jarak baris.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Ligatur kontekstual standar yang digunakan untuk menghubungkan huruf bersama-sama.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Mendapatkan atau mengatur warna goresan.

Value: Warna goresan.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Mendapatkan atau mengatur tracking.

Value: Tracking.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


Skala vertikal.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Mendapatkan atau mengatur nilai no break.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Menentukan apakah gaya yang ditentukan sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Gaya. |

**Returns:**
boolean -  true  jika gaya yang ditentukan sama; selain itu,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Mendapatkan atau mengatur perataan Romawi vertikal standar. Ini berdasarkan nilai sumber BaselineDirection hanya berlaku ketika orientasi teks adalah [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Mendapatkan atau mengatur auto kerning.

Value: Kerning otomatis antara dua karakter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [automatic leading].

Value:  true  jika [automatic leading]; selain itu,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Perpindahan baseline.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Alternatif kontekstual yang digunakan untuk menghubungkan huruf bersama-sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Ligatur diskresi yang digunakan untuk menghubungkan huruf, terutama dalam font skrip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Mendapatkan atau mengatur apakah faux bold diaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Mendapatkan atau mengatur apakah faux bold diaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Mendapatkan atau mengatur warna isian.

Value: Warna isian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


Garis dasar font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Huruf kapital font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Mendapatkan atau mengatur nama font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Mendapatkan atau mengatur ukuran font.

Value: Ukuran font.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Simbol pecahan dapat diganti dengan glif khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [hindi numbers].

Value:  true  jika [hindi numbers]; selain itu,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


Skala horizontal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Mendapatkan atau mengatur kerning.

Value: Kerning antara dua karakter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Mendapatkan atau mengatur leading.

Value: Jarak baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Ligatur kontekstual standar yang digunakan untuk menghubungkan huruf bersama-sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [strikethrough].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Mendapatkan atau mengatur warna goresan.

Value: Warna goresan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Mendapatkan atau mengatur tracking.

Value: Tracking.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah [underline].

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


Skala vertikal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Mendapatkan atau mengatur perataan Romawi vertikal standar. Ini berdasarkan nilai sumber BaselineDirection hanya berlaku ketika orientasi teks adalah [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Mendapatkan atau mengatur nilai no break.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |


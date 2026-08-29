---
title: "ITextStyle"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Schnittstelle zur Arbeit mit Textstil"
type: docs
weight: 14
url: /de/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Schnittstelle zur Arbeit mit Textstil
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Wendet den angegebenen Stil an. |
| [getAutoKerning()](#getAutoKerning--) | Liest oder setzt das automatische Kerning. |
| [getAutoLeading()](#getAutoLeading--) | Liest oder setzt einen Wert, der angibt, ob [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | Der Grundlinienversatz. |
| [getContextualAlternates()](#getContextualAlternates--) | Die kontextabhängigen Alternativen, die zum Verbinden von Buchstaben verwendet werden. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Die fakultativen Ligaturen, die zum Verbinden von Buchstaben verwendet werden, insbesondere in Schreibschrift-Schriften. |
| [getFauxBold()](#getFauxBold--) | Liest oder setzt, ob faux bold aktiviert ist. |
| [getFauxItalic()](#getFauxItalic--) | Liest oder setzt, ob faux bold aktiviert ist. |
| [getFillColor()](#getFillColor--) | Liest oder setzt die Füllfarbe. |
| [getFontBaseline()](#getFontBaseline--) | Die Schriftgrundlinie. |
| [getFontCaps()](#getFontCaps--) | Die Schriftkapitalen. |
| [getFontIndex()](#getFontIndex--) | Liest den Schriftindex. |
| [getFontName()](#getFontName--) | Liest oder setzt den Schriftnamen. |
| [getFontSize()](#getFontSize--) | Liest oder setzt die Schriftgröße. |
| [getFractions()](#getFractions--) | Die Bruchzeichen können durch spezielle Glyphen ersetzt werden. |
| [getHindiNumbers()](#getHindiNumbers--) | Liest oder setzt einen Wert, der angibt, ob [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | Die horizontale Skalierung. |
| [getKerning()](#getKerning--) | Liest oder setzt das Kerning. |
| [getLanguageIndex()](#getLanguageIndex--) | Liest den Sprachindex. |
| [getLeading()](#getLeading--) | Liest oder setzt den Zeilenabstand. |
| [getStandardLigatures()](#getStandardLigatures--) | Die standardmäßigen kontextuellen Ligaturen, die zum Verbinden von Buchstaben verwendet werden. |
| [getStrikethrough()](#getStrikethrough--) | Liest oder setzt einen Wert, der angibt, ob [strikethrough] aktiviert ist. |
| [getStrokeColor()](#getStrokeColor--) | Liest oder setzt die Farbe des Strichs. |
| [getTracking()](#getTracking--) | Liest oder setzt das Tracking. |
| [getUnderline()](#getUnderline--) | Liest oder setzt einen Wert, der angibt, ob [underline] aktiviert ist. |
| [getVerticalScale()](#getVerticalScale--) | Die vertikale Skalierung. |
| [get_noBreak()](#get-noBreak--) | Liest oder setzt den No‑Break‑Wert. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Bestimmt, ob der angegebene Stil gleich ist. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Liest oder setzt die standardmäßige vertikale römische Ausrichtung. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Liest oder setzt das automatische Kerning. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Liest oder setzt einen Wert, der angibt, ob [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Der Grundlinienversatz. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Die kontextabhängigen Alternativen, die zum Verbinden von Buchstaben verwendet werden. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Die fakultativen Ligaturen, die zum Verbinden von Buchstaben verwendet werden, insbesondere in Schreibschrift-Schriften. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Liest oder setzt, ob faux bold aktiviert ist. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Liest oder setzt, ob faux bold aktiviert ist. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Liest oder setzt die Füllfarbe. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | Die Schriftgrundlinie. |
| [setFontCaps(int value)](#setFontCaps-int-) | Die Schriftkapitalen. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Liest oder setzt den Schriftnamen. |
| [setFontSize(double value)](#setFontSize-double-) | Liest oder setzt die Schriftgröße. |
| [setFractions(boolean value)](#setFractions-boolean-) | Die Bruchzeichen können durch spezielle Glyphen ersetzt werden. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Liest oder setzt einen Wert, der angibt, ob [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | Die horizontale Skalierung. |
| [setKerning(int value)](#setKerning-int-) | Liest oder setzt das Kerning. |
| [setLeading(double value)](#setLeading-double-) | Liest oder setzt den Zeilenabstand. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Die standardmäßigen kontextuellen Ligaturen, die zum Verbinden von Buchstaben verwendet werden. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Liest oder setzt einen Wert, der angibt, ob [strikethrough] aktiviert ist. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Liest oder setzt die Farbe des Strichs. |
| [setTracking(int value)](#setTracking-int-) | Liest oder setzt das Tracking. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Liest oder setzt einen Wert, der angibt, ob [underline] aktiviert ist. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | Die vertikale Skalierung. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Liest oder setzt die standardmäßige vertikale römische Ausrichtung. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Liest oder setzt den No‑Break‑Wert. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Wendet den angegebenen Stil an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Der Stil. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Liest oder setzt das automatische Kerning.

Wert: Das automatische Kerning zwischen zwei Zeichen.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Liest oder setzt einen Wert, der angibt, ob [automatic leading].

Wert:  true  wenn [automatic leading]; andernfalls  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Der Grundlinienversatz.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Die kontextabhängigen Alternativen, die zum Verbinden von Buchstaben verwendet werden.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Die fakultativen Ligaturen, die zum Verbinden von Buchstaben verwendet werden, insbesondere in Schreibschrift-Schriften.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Liest oder setzt, ob faux bold aktiviert ist.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Liest oder setzt, ob faux bold aktiviert ist.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Liest oder setzt die Füllfarbe.

Wert: Die Füllfarbe.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


Die Schriftgrundlinie.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Die Schriftkapitalen.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Liest den Schriftindex.

Wert: Die Schriftart.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Liest oder setzt den Schriftnamen.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Liest oder setzt die Schriftgröße.

Wert: Die Schriftgröße.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Die Bruchzeichen können durch spezielle Glyphen ersetzt werden.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Liest oder setzt einen Wert, der angibt, ob [hindi numbers].

Wert:  true  wenn [hindi numbers]; andernfalls  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


Die horizontale Skalierung.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Liest oder setzt das Kerning.

Wert: Das Kerning zwischen zwei Zeichen.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Liest den Sprachindex.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Liest oder setzt den Zeilenabstand.

Wert: Der Zeilenabstand.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Die standardmäßigen kontextuellen Ligaturen, die zum Verbinden von Buchstaben verwendet werden.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Liest oder setzt einen Wert, der angibt, ob [strikethrough] aktiviert ist.

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Liest oder setzt die Farbe des Strichs.

Wert: Die Farbe des Strichs.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Liest oder setzt das Tracking.

Wert: Das Tracking.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Liest oder setzt einen Wert, der angibt, ob [underline] aktiviert ist.

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


Die vertikale Skalierung.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Liest oder setzt den No‑Break‑Wert.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Bestimmt, ob der angegebene Stil gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Der Stil. |

**Returns:**
boolesch -  true  wenn der angegebene Stil gleich ist; andernfalls  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Liest oder setzt die standardmäßige vertikale römische Ausrichtung. Dies, basierend auf dem BaselineDirection-Ressourcenwert, gilt nur, wenn die Textausrichtung [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) ist.

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Liest oder setzt das automatische Kerning.

Wert: Das automatische Kerning zwischen zwei Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [automatic leading].

Wert:  true  wenn [automatic leading]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Der Grundlinienversatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Die kontextabhängigen Alternativen, die zum Verbinden von Buchstaben verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Die fakultativen Ligaturen, die zum Verbinden von Buchstaben verwendet werden, insbesondere in Schreibschrift-Schriften.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Liest oder setzt, ob faux bold aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Liest oder setzt, ob faux bold aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Liest oder setzt die Füllfarbe.

Wert: Die Füllfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


Die Schriftgrundlinie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Die Schriftkapitalen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Liest oder setzt den Schriftnamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Liest oder setzt die Schriftgröße.

Wert: Die Schriftgröße.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Die Bruchzeichen können durch spezielle Glyphen ersetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [hindi numbers].

Wert:  true  wenn [hindi numbers]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


Die horizontale Skalierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Liest oder setzt das Kerning.

Wert: Das Kerning zwischen zwei Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Liest oder setzt den Zeilenabstand.

Wert: Der Zeilenabstand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Die standardmäßigen kontextuellen Ligaturen, die zum Verbinden von Buchstaben verwendet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [strikethrough] aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Liest oder setzt die Farbe des Strichs.

Wert: Die Farbe des Strichs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Liest oder setzt das Tracking.

Wert: Das Tracking.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob [underline] aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


Die vertikale Skalierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Liest oder setzt die standardmäßige vertikale römische Ausrichtung. Dies, basierend auf dem BaselineDirection-Ressourcenwert, gilt nur, wenn die Textausrichtung [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Liest oder setzt den No‑Break‑Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |


---
title: "ITextStyle"
second_title: "Aspose.PSD för Java API-referens"
description: "Gränssnitt för att arbeta med textstil"
type: docs
weight: 14
url: /sv/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Gränssnitt för att arbeta med textstil
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Tillämpar den angivna stilen. |
| [getAutoKerning()](#getAutoKerning--) | Hämtar eller anger den automatiska kerning. |
| [getAutoLeading()](#getAutoLeading--) | Hämtar eller anger ett värde som indikerar om [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | Baslinjeförskjutningen. |
| [getContextualAlternates()](#getContextualAlternates--) | De kontextuella alternativen som används för att koppla ihop bokstäver. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | De valfria ligaturerna som används för att koppla ihop bokstäver, särskilt i skriptfonter. |
| [getFauxBold()](#getFauxBold--) | Hämtar eller anger om falsk fetstil är aktiverad. |
| [getFauxItalic()](#getFauxItalic--) | Hämtar eller anger om falsk fetstil är aktiverad. |
| [getFillColor()](#getFillColor--) | Hämtar eller anger fyllningsfärgen. |
| [getFontBaseline()](#getFontBaseline--) | Teckensnittets baslinje. |
| [getFontCaps()](#getFontCaps--) | Teckensnittets versaler. |
| [getFontIndex()](#getFontIndex--) | Hämtar teckensnittets index. |
| [getFontName()](#getFontName--) | Hämtar eller anger teckensnittets namn. |
| [getFontSize()](#getFontSize--) | Hämtar eller anger teckensnittets storlek. |
| [getFractions()](#getFractions--) | Bråksymbolerna kan ersättas med specialtecken. |
| [getHindiNumbers()](#getHindiNumbers--) | Hämtar eller anger ett värde som indikerar om [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | Den horisontella skalan. |
| [getKerning()](#getKerning--) | Hämtar eller anger kerning. |
| [getLanguageIndex()](#getLanguageIndex--) | Hämtar språkindexet. |
| [getLeading()](#getLeading--) | Hämtar eller anger radavståndet. |
| [getStandardLigatures()](#getStandardLigatures--) | De standardkontextuella ligaturerna som används för att koppla ihop bokstäver. |
| [getStrikethrough()](#getStrikethrough--) | Hämtar eller anger ett värde som indikerar om [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Hämtar eller anger färgen på strecket. |
| [getTracking()](#getTracking--) | Hämtar eller anger spårning. |
| [getUnderline()](#getUnderline--) | Hämtar eller anger ett värde som indikerar om [underline]. |
| [getVerticalScale()](#getVerticalScale--) | Den vertikala skalan. |
| [get_noBreak()](#get-noBreak--) | Hämtar eller anger värdet för ingen brytning. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Avgör om den angivna stilen är lika. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Hämtar eller anger standard vertikal Romersk justering. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Hämtar eller anger den automatiska kerning. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Hämtar eller anger ett värde som indikerar om [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Baslinjeförskjutningen. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | De kontextuella alternativen som används för att koppla ihop bokstäver. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | De valfria ligaturerna som används för att koppla ihop bokstäver, särskilt i skriptfonter. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Hämtar eller anger om falsk fetstil är aktiverad. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Hämtar eller anger om falsk fetstil är aktiverad. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Hämtar eller anger fyllningsfärgen. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | Teckensnittets baslinje. |
| [setFontCaps(int value)](#setFontCaps-int-) | Teckensnittets versaler. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Hämtar eller anger teckensnittets namn. |
| [setFontSize(double value)](#setFontSize-double-) | Hämtar eller anger teckensnittets storlek. |
| [setFractions(boolean value)](#setFractions-boolean-) | Bråksymbolerna kan ersättas med specialtecken. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Hämtar eller anger ett värde som indikerar om [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | Den horisontella skalan. |
| [setKerning(int value)](#setKerning-int-) | Hämtar eller anger kerning. |
| [setLeading(double value)](#setLeading-double-) | Hämtar eller anger radavståndet. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | De standardkontextuella ligaturerna som används för att koppla ihop bokstäver. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Hämtar eller anger ett värde som indikerar om [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Hämtar eller anger färgen på strecket. |
| [setTracking(int value)](#setTracking-int-) | Hämtar eller anger spårning. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Hämtar eller anger ett värde som indikerar om [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | Den vertikala skalan. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Hämtar eller anger standard vertikal Romersk justering. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Hämtar eller anger värdet för ingen brytning. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Tillämpar den angivna stilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Stilen. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Hämtar eller anger den automatiska kerning.

Värde: Den automatiska kerning mellan två tecken.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Hämtar eller anger ett värde som indikerar om [automatic leading].

Värde:  true  om [automatic leading]; annars,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Baslinjeförskjutningen.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


De kontextuella alternativen som används för att koppla ihop bokstäver.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


De valfria ligaturerna som används för att koppla ihop bokstäver, särskilt i skriptfonter.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Hämtar eller anger om falsk fetstil är aktiverad.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Hämtar eller anger om falsk fetstil är aktiverad.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Hämtar eller anger fyllningsfärgen.

Värde: Färgen på fyllningen.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


Teckensnittets baslinje.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Teckensnittets versaler.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Hämtar teckensnittets index.

Värde: Typsnittet.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Hämtar eller anger teckensnittets namn.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Hämtar eller anger teckensnittets storlek.

Värde: Typsnittets storlek.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Bråksymbolerna kan ersättas med specialtecken.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Hämtar eller anger ett värde som indikerar om [hindi numbers].

Värde:  true  om [hindi numbers]; annars,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


Den horisontella skalan.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Hämtar eller anger kerning.

Värde: Kerning mellan två tecken.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Hämtar språkindexet.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Hämtar eller anger radavståndet.

Värde: Radavståndet.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


De standardkontextuella ligaturerna som används för att koppla ihop bokstäver.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Hämtar eller anger ett värde som indikerar om [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Hämtar eller anger färgen på strecket.

Värde: Streckets färg.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Hämtar eller anger spårning.

Värde: Spårning.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Hämtar eller anger ett värde som indikerar om [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


Den vertikala skalan.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Hämtar eller anger värdet för ingen brytning.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Avgör om den angivna stilen är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Stilen. |

**Returns:**
boolean -  true  om den angivna stilen är lika; annars,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Hämtar eller anger den standardvertikala romerska justeringen. Detta, baserat på BaselineDirection-resursvärdet, gäller endast när textorienteringen är [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Hämtar eller anger den automatiska kerning.

Värde: Den automatiska kerning mellan två tecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Hämtar eller anger ett värde som indikerar om [automatic leading].

Värde:  true  om [automatic leading]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Baslinjeförskjutningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


De kontextuella alternativen som används för att koppla ihop bokstäver.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


De valfria ligaturerna som används för att koppla ihop bokstäver, särskilt i skriptfonter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Hämtar eller anger om falsk fetstil är aktiverad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Hämtar eller anger om falsk fetstil är aktiverad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Hämtar eller anger fyllningsfärgen.

Värde: Färgen på fyllningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


Teckensnittets baslinje.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Teckensnittets versaler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Hämtar eller anger teckensnittets namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Hämtar eller anger teckensnittets storlek.

Värde: Typsnittets storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Bråksymbolerna kan ersättas med specialtecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Hämtar eller anger ett värde som indikerar om [hindi numbers].

Värde:  true  om [hindi numbers]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


Den horisontella skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Hämtar eller anger kerning.

Värde: Kerning mellan två tecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Hämtar eller anger radavståndet.

Värde: Radavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


De standardkontextuella ligaturerna som används för att koppla ihop bokstäver.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Hämtar eller anger ett värde som indikerar om [strikethrough].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Hämtar eller anger färgen på strecket.

Värde: Streckets färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Hämtar eller anger spårning.

Värde: Spårning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Hämtar eller anger ett värde som indikerar om [underline].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


Den vertikala skalan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Hämtar eller anger den standardvertikala romerska justeringen. Detta, baserat på BaselineDirection-resursvärdet, gäller endast när textorienteringen är [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Hämtar eller anger värdet för ingen brytning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |


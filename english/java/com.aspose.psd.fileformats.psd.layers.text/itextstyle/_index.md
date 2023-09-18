---
title: ITextStyle
second_title: Aspose.PSD for Java API Reference
description: Interface to work with Text Style
type: docs
weight: 14
url: /java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Interface to work with Text Style
## Methods

| Method | Description |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Applies the specified style. |
| [getAutoKerning()](#getAutoKerning--) | Gets or sets the auto kerning. |
| [getAutoLeading()](#getAutoLeading--) | Gets or sets a value indicating whether [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | The baseline shift. |
| [getContextualAlternates()](#getContextualAlternates--) | The contextual alternates used to connect letters together. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | The discretionary ligatures used to connect letters, especially in script fonts. |
| [getFauxBold()](#getFauxBold--) | Gets or sets the faux bold is enabled. |
| [getFauxItalic()](#getFauxItalic--) | Gets or sets the faux bold is enabled. |
| [getFillColor()](#getFillColor--) | Gets or sets the color of the fill. |
| [getFontBaseline()](#getFontBaseline--) | The font baseline. |
| [getFontCaps()](#getFontCaps--) | The font caps. |
| [getFontIndex()](#getFontIndex--) | Gets the font index. |
| [getFontName()](#getFontName--) | Gets or sets the font name. |
| [getFontSize()](#getFontSize--) | Gets or sets the size of the font. |
| [getFractions()](#getFractions--) | The fractions symbols can be replaced with special glyph. |
| [getHindiNumbers()](#getHindiNumbers--) | Gets or sets a value indicating whether [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | The horizontal scale. |
| [getKerning()](#getKerning--) | Gets or sets the kerning. |
| [getLanguageIndex()](#getLanguageIndex--) | Gets the language index. |
| [getLeading()](#getLeading--) | Gets or sets the leading. |
| [getStandardLigatures()](#getStandardLigatures--) | The standard contextual ligatures used to connect letters together. |
| [getStrikethrough()](#getStrikethrough--) | Gets or sets a value indicating whether [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Gets or sets the color of the stroke. |
| [getTracking()](#getTracking--) | Gets or sets the tracking. |
| [getUnderline()](#getUnderline--) | Gets or sets a value indicating whether [underline]. |
| [getVerticalScale()](#getVerticalScale--) | The vertical scale. |
| [get_noBreak()](#get-noBreak--) | Gets ot sets the no break value. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Determines whether the specified style is equal. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Gets or sets the standard vertical Roman alignment. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Gets or sets the auto kerning. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Gets or sets a value indicating whether [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | The baseline shift. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | The contextual alternates used to connect letters together. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | The discretionary ligatures used to connect letters, especially in script fonts. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Gets or sets the faux bold is enabled. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Gets or sets the faux bold is enabled. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Gets or sets the color of the fill. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | The font baseline. |
| [setFontCaps(int value)](#setFontCaps-int-) | The font caps. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Gets or sets the font name. |
| [setFontSize(double value)](#setFontSize-double-) | Gets or sets the size of the font. |
| [setFractions(boolean value)](#setFractions-boolean-) | The fractions symbols can be replaced with special glyph. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Gets or sets a value indicating whether [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | The horizontal scale. |
| [setKerning(int value)](#setKerning-int-) | Gets or sets the kerning. |
| [setLeading(double value)](#setLeading-double-) | Gets or sets the leading. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | The standard contextual ligatures used to connect letters together. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Gets or sets a value indicating whether [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Gets or sets the color of the stroke. |
| [setTracking(int value)](#setTracking-int-) | Gets or sets the tracking. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Gets or sets a value indicating whether [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | The vertical scale. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Gets or sets the standard vertical Roman alignment. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Gets ot sets the no break value. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Applies the specified style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | The style. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Gets or sets the auto kerning.

Value: The auto kerning between two characters.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Gets or sets a value indicating whether [automatic leading].

Value:  true  if [automatic leading]; otherwise,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


The baseline shift.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


The contextual alternates used to connect letters together.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


The discretionary ligatures used to connect letters, especially in script fonts.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Gets or sets the faux bold is enabled.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Gets or sets the faux bold is enabled.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Gets or sets the color of the fill.

Value: The color of the fill.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


The font baseline.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


The font caps.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Gets the font index.

Value: The font.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Gets or sets the font name.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Gets or sets the size of the font.

Value: The size of the font.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


The fractions symbols can be replaced with special glyph.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Gets or sets a value indicating whether [hindi numbers].

Value:  true  if [hindi numbers]; otherwise,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


The horizontal scale.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Gets or sets the kerning.

Value: The kerning between two characters.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Gets the language index.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Gets or sets the leading.

Value: The leading.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


The standard contextual ligatures used to connect letters together.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Gets or sets a value indicating whether [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Gets or sets the color of the stroke.

Value: The color of the stroke.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Gets or sets the tracking.

Value: The tracking.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Gets or sets a value indicating whether [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


The vertical scale.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Gets ot sets the no break value.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Determines whether the specified style is equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | The style. |

**Returns:**
boolean -  true  if the specified style is equal; otherwise,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Gets or sets the standard vertical Roman alignment. This based on BaselineDirection resource value applies only when text orientation is [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Gets or sets the auto kerning.

Value: The auto kerning between two characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Gets or sets a value indicating whether [automatic leading].

Value:  true  if [automatic leading]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


The baseline shift.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


The contextual alternates used to connect letters together.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


The discretionary ligatures used to connect letters, especially in script fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Gets or sets the faux bold is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Gets or sets the faux bold is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Gets or sets the color of the fill.

Value: The color of the fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


The font baseline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


The font caps.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Gets or sets the font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Gets or sets the size of the font.

Value: The size of the font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


The fractions symbols can be replaced with special glyph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Gets or sets a value indicating whether [hindi numbers].

Value:  true  if [hindi numbers]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


The horizontal scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Gets or sets the kerning.

Value: The kerning between two characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Gets or sets the leading.

Value: The leading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


The standard contextual ligatures used to connect letters together.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Gets or sets a value indicating whether [strikethrough].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Gets or sets the color of the stroke.

Value: The color of the stroke.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Gets or sets the tracking.

Value: The tracking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Gets or sets a value indicating whether [underline].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


The vertical scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Gets or sets the standard vertical Roman alignment. This based on BaselineDirection resource value applies only when text orientation is [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Gets ot sets the no break value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |


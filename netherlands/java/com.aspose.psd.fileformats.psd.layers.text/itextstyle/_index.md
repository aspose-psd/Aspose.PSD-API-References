---
title: "ITextStyle"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Interface om met tekststijl te werken"
type: docs
weight: 14
url: /nl/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Interface om met tekststijl te werken
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Past de opgegeven stijl toe. |
| [getAutoKerning()](#getAutoKerning--) | Haalt op of stelt de automatische kerning in. |
| [getAutoLeading()](#getAutoLeading--) | Haalt op of stelt een waarde in die aangeeft of [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | De baselineverschuiving. |
| [getContextualAlternates()](#getContextualAlternates--) | De contextuele alternatieven die worden gebruikt om letters met elkaar te verbinden. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | De discretionaire ligaturen die worden gebruikt om letters te verbinden, vooral in scriptlettertypen. |
| [getFauxBold()](#getFauxBold--) | Haalt op of stelt in of de faux vet is ingeschakeld. |
| [getFauxItalic()](#getFauxItalic--) | Haalt op of stelt in of de faux vet is ingeschakeld. |
| [getFillColor()](#getFillColor--) | Haalt op of stelt de vulkleur in. |
| [getFontBaseline()](#getFontBaseline--) | De lettertype-baseline. |
| [getFontCaps()](#getFontCaps--) | De hoofdletters van het lettertype. |
| [getFontIndex()](#getFontIndex--) | Haalt de lettertype-index op. |
| [getFontName()](#getFontName--) | Haalt op of stelt de lettertype-naam in. |
| [getFontSize()](#getFontSize--) | Haalt op of stelt de grootte van het lettertype in. |
| [getFractions()](#getFractions--) | De breuktekens kunnen worden vervangen door een speciaal glyph. |
| [getHindiNumbers()](#getHindiNumbers--) | Haalt op of stelt een waarde in die aangeeft of [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | De horizontale schaal. |
| [getKerning()](#getKerning--) | Haalt op of stelt de kerning in. |
| [getLanguageIndex()](#getLanguageIndex--) | Haalt de taalindex op. |
| [getLeading()](#getLeading--) | Haalt op of stelt de leading in. |
| [getStandardLigatures()](#getStandardLigatures--) | De standaard contextuele ligaturen die worden gebruikt om letters met elkaar te verbinden. |
| [getStrikethrough()](#getStrikethrough--) | Haalt op of stelt een waarde in die aangeeft of [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Haalt op of stelt de kleur van de lijn in. |
| [getTracking()](#getTracking--) | Haalt op of stelt de tracking in. |
| [getUnderline()](#getUnderline--) | Haalt op of stelt een waarde in die aangeeft of [underline]. |
| [getVerticalScale()](#getVerticalScale--) | De verticale schaal. |
| [get_noBreak()](#get-noBreak--) | Haalt op ot stelt de geen‑onderbrekingswaarde in. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Bepaalt of de opgegeven stijl gelijk is. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Haalt op of stelt de standaard verticale Romeinse uitlijning in. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Haalt op of stelt de automatische kerning in. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Haalt op of stelt een waarde in die aangeeft of [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | De baselineverschuiving. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | De contextuele alternatieven die worden gebruikt om letters met elkaar te verbinden. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | De discretionaire ligaturen die worden gebruikt om letters te verbinden, vooral in scriptlettertypen. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Haalt op of stelt in of de faux vet is ingeschakeld. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Haalt op of stelt in of de faux vet is ingeschakeld. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Haalt op of stelt de vulkleur in. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | De lettertype-baseline. |
| [setFontCaps(int value)](#setFontCaps-int-) | De hoofdletters van het lettertype. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Haalt op of stelt de lettertype-naam in. |
| [setFontSize(double value)](#setFontSize-double-) | Haalt op of stelt de grootte van het lettertype in. |
| [setFractions(boolean value)](#setFractions-boolean-) | De breuktekens kunnen worden vervangen door een speciaal glyph. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Haalt op of stelt een waarde in die aangeeft of [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | De horizontale schaal. |
| [setKerning(int value)](#setKerning-int-) | Haalt op of stelt de kerning in. |
| [setLeading(double value)](#setLeading-double-) | Haalt op of stelt de leading in. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | De standaard contextuele ligaturen die worden gebruikt om letters met elkaar te verbinden. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Haalt op of stelt een waarde in die aangeeft of [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Haalt op of stelt de kleur van de lijn in. |
| [setTracking(int value)](#setTracking-int-) | Haalt op of stelt de tracking in. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Haalt op of stelt een waarde in die aangeeft of [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | De verticale schaal. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Haalt op of stelt de standaard verticale Romeinse uitlijning in. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Haalt op ot stelt de geen‑onderbrekingswaarde in. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Past de opgegeven stijl toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | De stijl. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Haalt op of stelt de automatische kerning in.

Waarde: De automatische kerning tussen twee tekens.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Haalt op of stelt een waarde in die aangeeft of [automatic leading].

Waarde:  true  als [automatic leading]; anders,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


De baselineverschuiving.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


De contextuele alternatieven die worden gebruikt om letters met elkaar te verbinden.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


De discretionaire ligaturen die worden gebruikt om letters te verbinden, vooral in scriptlettertypen.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Haalt op of stelt in of de faux vet is ingeschakeld.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Haalt op of stelt in of de faux vet is ingeschakeld.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Haalt op of stelt de vulkleur in.

Waarde: De kleur van de vulling.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


De lettertype-baseline.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


De hoofdletters van het lettertype.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Haalt de lettertype-index op.

Waarde: Het lettertype.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Haalt op of stelt de lettertype-naam in.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Haalt op of stelt de grootte van het lettertype in.

Waarde: De grootte van het lettertype.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


De breuktekens kunnen worden vervangen door een speciaal glyph.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Haalt op of stelt een waarde in die aangeeft of [hindi numbers].

Waarde:  true  als [hindi numbers]; anders,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


De horizontale schaal.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Haalt op of stelt de kerning in.

Waarde: De kerning tussen twee tekens.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Haalt de taalindex op.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Haalt op of stelt de leading in.

Waarde: De leading.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


De standaard contextuele ligaturen die worden gebruikt om letters met elkaar te verbinden.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Haalt op of stelt een waarde in die aangeeft of [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Haalt op of stelt de kleur van de lijn in.

Waarde: De kleur van de streep.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Haalt op of stelt de tracking in.

Waarde: De tracking.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Haalt op of stelt een waarde in die aangeeft of [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


De verticale schaal.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Haalt op ot stelt de geen‑onderbrekingswaarde in.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Bepaalt of de opgegeven stijl gelijk is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | De stijl. |

**Returns:**
boolean -  true  als de opgegeven stijl gelijk is; anders,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Haalt op of stelt de standaard verticale Romeinse uitlijning in. Deze, gebaseerd op de BaselineDirection resourcewaarde, is alleen van toepassing wanneer de tekstoriëntatie [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) is.

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Haalt op of stelt de automatische kerning in.

Waarde: De automatische kerning tussen twee tekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [automatic leading].

Waarde:  true  als [automatic leading]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


De baselineverschuiving.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


De contextuele alternatieven die worden gebruikt om letters met elkaar te verbinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


De discretionaire ligaturen die worden gebruikt om letters te verbinden, vooral in scriptlettertypen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Haalt op of stelt in of de faux vet is ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Haalt op of stelt in of de faux vet is ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Haalt op of stelt de vulkleur in.

Waarde: De kleur van de vulling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


De lettertype-baseline.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


De hoofdletters van het lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Haalt op of stelt de lettertype-naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Haalt op of stelt de grootte van het lettertype in.

Waarde: De grootte van het lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


De breuktekens kunnen worden vervangen door een speciaal glyph.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [hindi numbers].

Waarde:  true  als [hindi numbers]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


De horizontale schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Haalt op of stelt de kerning in.

Waarde: De kerning tussen twee tekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Haalt op of stelt de leading in.

Waarde: De leading.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


De standaard contextuele ligaturen die worden gebruikt om letters met elkaar te verbinden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [strikethrough].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Haalt op of stelt de kleur van de lijn in.

Waarde: De kleur van de streep.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Haalt op of stelt de tracking in.

Waarde: De tracking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [underline].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


De verticale schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Haalt op of stelt de standaard verticale Romeinse uitlijning in. Deze, gebaseerd op de BaselineDirection resourcewaarde, is alleen van toepassing wanneer de tekstoriëntatie [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical) is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Haalt op ot stelt de geen‑onderbrekingswaarde in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |


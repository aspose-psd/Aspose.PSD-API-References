---
title: "ITextStyle"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Interfaccia per lavorare con lo stile del testo"
type: docs
weight: 14
url: /it/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Interfaccia per lavorare con lo stile del testo
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Applica lo stile specificato. |
| [getAutoKerning()](#getAutoKerning--) | Ottiene o imposta il kerning automatico. |
| [getAutoLeading()](#getAutoLeading--) | Ottiene o imposta un valore che indica se [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | Lo spostamento della linea di base. |
| [getContextualAlternates()](#getContextualAlternates--) | Gli alternanti contestuali usati per collegare le lettere insieme. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Le legature discrezionali usate per collegare le lettere, specialmente nei font script. |
| [getFauxBold()](#getFauxBold--) | Ottiene o imposta se il faux bold è abilitato. |
| [getFauxItalic()](#getFauxItalic--) | Ottiene o imposta se il faux bold è abilitato. |
| [getFillColor()](#getFillColor--) | Ottiene o imposta il colore del riempimento. |
| [getFontBaseline()](#getFontBaseline--) | La linea di base del carattere. |
| [getFontCaps()](#getFontCaps--) | Le maiuscole del carattere. |
| [getFontIndex()](#getFontIndex--) | Ottiene l'indice del carattere. |
| [getFontName()](#getFontName--) | Ottiene o imposta il nome del carattere. |
| [getFontSize()](#getFontSize--) | Ottiene o imposta la dimensione del carattere. |
| [getFractions()](#getFractions--) | I simboli delle frazioni possono essere sostituiti con un glifo speciale. |
| [getHindiNumbers()](#getHindiNumbers--) | Ottiene o imposta un valore che indica se [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | La scala orizzontale. |
| [getKerning()](#getKerning--) | Ottiene o imposta il kerning. |
| [getLanguageIndex()](#getLanguageIndex--) | Ottiene l'indice della lingua. |
| [getLeading()](#getLeading--) | Ottiene o imposta il leading. |
| [getStandardLigatures()](#getStandardLigatures--) | Le legature contestuali standard usate per collegare le lettere insieme. |
| [getStrikethrough()](#getStrikethrough--) | Ottiene o imposta un valore che indica se [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Ottiene o imposta il colore del tratto. |
| [getTracking()](#getTracking--) | Ottiene o imposta il tracking. |
| [getUnderline()](#getUnderline--) | Ottiene o imposta un valore che indica se [underline]. |
| [getVerticalScale()](#getVerticalScale--) | La scala verticale. |
| [get_noBreak()](#get-noBreak--) | Ottiene o imposta il valore no break. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Determina se lo stile specificato è uguale. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Ottiene o imposta l'allineamento verticale romano standard. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Ottiene o imposta il kerning automatico. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Ottiene o imposta un valore che indica se [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Lo spostamento della linea di base. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Gli alternanti contestuali usati per collegare le lettere insieme. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Le legature discrezionali usate per collegare le lettere, specialmente nei font script. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Ottiene o imposta se il faux bold è abilitato. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Ottiene o imposta se il faux bold è abilitato. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Ottiene o imposta il colore del riempimento. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | La linea di base del carattere. |
| [setFontCaps(int value)](#setFontCaps-int-) | Le maiuscole del carattere. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Ottiene o imposta il nome del carattere. |
| [setFontSize(double value)](#setFontSize-double-) | Ottiene o imposta la dimensione del carattere. |
| [setFractions(boolean value)](#setFractions-boolean-) | I simboli delle frazioni possono essere sostituiti con un glifo speciale. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Ottiene o imposta un valore che indica se [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | La scala orizzontale. |
| [setKerning(int value)](#setKerning-int-) | Ottiene o imposta il kerning. |
| [setLeading(double value)](#setLeading-double-) | Ottiene o imposta il leading. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Le legature contestuali standard usate per collegare le lettere insieme. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Ottiene o imposta un valore che indica se [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Ottiene o imposta il colore del tratto. |
| [setTracking(int value)](#setTracking-int-) | Ottiene o imposta il tracking. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Ottiene o imposta un valore che indica se [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | La scala verticale. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Ottiene o imposta l'allineamento verticale romano standard. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Ottiene o imposta il valore no break. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Applica lo stile specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Lo stile. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Ottiene o imposta il kerning automatico.

Valore: la spaziatura automatica tra due caratteri.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Ottiene o imposta un valore che indica se [automatic leading].

Valore:  true  se [automatic leading]; altrimenti,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Lo spostamento della linea di base.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Gli alternanti contestuali usati per collegare le lettere insieme.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Le legature discrezionali usate per collegare le lettere, specialmente nei font script.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Ottiene o imposta se il faux bold è abilitato.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Ottiene o imposta se il faux bold è abilitato.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Ottiene o imposta il colore del riempimento.

Valore: il colore del riempimento.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


La linea di base del carattere.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Le maiuscole del carattere.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Ottiene l'indice del carattere.

Valore: il font.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Ottiene o imposta il nome del carattere.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Ottiene o imposta la dimensione del carattere.

Valore: la dimensione del font.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


I simboli delle frazioni possono essere sostituiti con un glifo speciale.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Ottiene o imposta un valore che indica se [hindi numbers].

Valore:  true  se [hindi numbers]; altrimenti,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


La scala orizzontale.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Ottiene o imposta il kerning.

Valore: la spaziatura tra due caratteri.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Ottiene l'indice della lingua.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Ottiene o imposta il leading.

Valore: l'interlinea.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Le legature contestuali standard usate per collegare le lettere insieme.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Ottiene o imposta un valore che indica se [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Ottiene o imposta il colore del tratto.

Valore: il colore del tratto.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Ottiene o imposta il tracking.

Valore: il tracking.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Ottiene o imposta un valore che indica se [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


La scala verticale.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Ottiene o imposta il valore no break.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Determina se lo stile specificato è uguale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Lo stile. |

**Returns:**
boolean -  true  se lo stile specificato è uguale; altrimenti,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Ottiene o imposta l'allineamento romano verticale standard. Questo basato sul valore della risorsa BaselineDirection si applica solo quando l'orientamento del testo è [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Ottiene o imposta il kerning automatico.

Valore: la spaziatura automatica tra due caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Ottiene o imposta un valore che indica se [automatic leading].

Valore:  true  se [automatic leading]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Lo spostamento della linea di base.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Gli alternanti contestuali usati per collegare le lettere insieme.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Le legature discrezionali usate per collegare le lettere, specialmente nei font script.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Ottiene o imposta se il faux bold è abilitato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Ottiene o imposta se il faux bold è abilitato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Ottiene o imposta il colore del riempimento.

Valore: il colore del riempimento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


La linea di base del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Le maiuscole del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Ottiene o imposta il nome del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Ottiene o imposta la dimensione del carattere.

Valore: la dimensione del font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


I simboli delle frazioni possono essere sostituiti con un glifo speciale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Ottiene o imposta un valore che indica se [hindi numbers].

Valore:  true  se [hindi numbers]; altrimenti,  false .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


La scala orizzontale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Ottiene o imposta il kerning.

Valore: la spaziatura tra due caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Ottiene o imposta il leading.

Valore: l'interlinea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Le legature contestuali standard usate per collegare le lettere insieme.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Ottiene o imposta un valore che indica se [strikethrough].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Ottiene o imposta il colore del tratto.

Valore: il colore del tratto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Ottiene o imposta il tracking.

Valore: il tracking.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Ottiene o imposta un valore che indica se [underline].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


La scala verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Ottiene o imposta l'allineamento romano verticale standard. Questo basato sul valore della risorsa BaselineDirection si applica solo quando l'orientamento del testo è [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Ottiene o imposta il valore no break.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |


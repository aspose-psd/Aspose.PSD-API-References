---
title: "ITextStyle"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Interface pour travailler avec le style de texte"
type: docs
weight: 14
url: /fr/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Interface pour travailler avec le style de texte
## Méthodes

| Méthode | Description |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Applique le style spécifié. |
| [getAutoKerning()](#getAutoKerning--) | Obtient ou définit le crénage automatique. |
| [getAutoLeading()](#getAutoLeading--) | Obtient ou définit une valeur indiquant si [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | Le décalage de ligne de base. |
| [getContextualAlternates()](#getContextualAlternates--) | Les alternatives contextuelles utilisées pour connecter les lettres entre elles. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Les ligatures discrétionnaires utilisées pour connecter les lettres, en particulier dans les polices script. |
| [getFauxBold()](#getFauxBold--) | Obtient ou définit si le faux bold est activé. |
| [getFauxItalic()](#getFauxItalic--) | Obtient ou définit si le faux bold est activé. |
| [getFillColor()](#getFillColor--) | Obtient ou définit la couleur du remplissage. |
| [getFontBaseline()](#getFontBaseline--) | La ligne de base de la police. |
| [getFontCaps()](#getFontCaps--) | Les majuscules de la police. |
| [getFontIndex()](#getFontIndex--) | Obtient l'index de la police. |
| [getFontName()](#getFontName--) | Obtient ou définit le nom de la police. |
| [getFontSize()](#getFontSize--) | Obtient ou définit la taille de la police. |
| [getFractions()](#getFractions--) | Les symboles de fractions peuvent être remplacés par un glyphe spécial. |
| [getHindiNumbers()](#getHindiNumbers--) | Obtient ou définit une valeur indiquant si [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | L'échelle horizontale. |
| [getKerning()](#getKerning--) | Obtient ou définit le crénage. |
| [getLanguageIndex()](#getLanguageIndex--) | Obtient l'index de la langue. |
| [getLeading()](#getLeading--) | Obtient ou définit l'interligne. |
| [getStandardLigatures()](#getStandardLigatures--) | Les ligatures contextuelles standard utilisées pour connecter les lettres entre elles. |
| [getStrikethrough()](#getStrikethrough--) | Obtient ou définit une valeur indiquant si [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Obtient ou définit la couleur du trait. |
| [getTracking()](#getTracking--) | Obtient ou définit le suivi. |
| [getUnderline()](#getUnderline--) | Obtient ou définit une valeur indiquant si [underline]. |
| [getVerticalScale()](#getVerticalScale--) | L'échelle verticale. |
| [get_noBreak()](#get-noBreak--) | Obtient ou définit la valeur de non‑saut. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Détermine si le style spécifié est égal. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Obtient ou définit l'alignement romain vertical standard. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Obtient ou définit le crénage automatique. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Obtient ou définit une valeur indiquant si [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Le décalage de ligne de base. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Les alternatives contextuelles utilisées pour connecter les lettres entre elles. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Les ligatures discrétionnaires utilisées pour connecter les lettres, en particulier dans les polices script. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Obtient ou définit si le faux bold est activé. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Obtient ou définit si le faux bold est activé. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Obtient ou définit la couleur du remplissage. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | La ligne de base de la police. |
| [setFontCaps(int value)](#setFontCaps-int-) | Les majuscules de la police. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Obtient ou définit le nom de la police. |
| [setFontSize(double value)](#setFontSize-double-) | Obtient ou définit la taille de la police. |
| [setFractions(boolean value)](#setFractions-boolean-) | Les symboles de fractions peuvent être remplacés par un glyphe spécial. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Obtient ou définit une valeur indiquant si [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | L'échelle horizontale. |
| [setKerning(int value)](#setKerning-int-) | Obtient ou définit le crénage. |
| [setLeading(double value)](#setLeading-double-) | Obtient ou définit l'interligne. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Les ligatures contextuelles standard utilisées pour connecter les lettres entre elles. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Obtient ou définit une valeur indiquant si [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Obtient ou définit la couleur du trait. |
| [setTracking(int value)](#setTracking-int-) | Obtient ou définit le suivi. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Obtient ou définit une valeur indiquant si [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | L'échelle verticale. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Obtient ou définit l'alignement romain vertical standard. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Obtient ou définit la valeur de non‑saut. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Applique le style spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Le style. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Obtient ou définit le crénage automatique.

Valeur : le crénage automatique entre deux caractères.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Obtient ou définit une valeur indiquant si [automatic leading].

Valeur :  true  si [automatic leading] ; sinon,  false .

**Returns:**
booléen
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Le décalage de ligne de base.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Les alternatives contextuelles utilisées pour connecter les lettres entre elles.

**Returns:**
booléen
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Les ligatures discrétionnaires utilisées pour connecter les lettres, en particulier dans les polices script.

**Returns:**
booléen
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Obtient ou définit si le faux bold est activé.

**Returns:**
booléen
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Obtient ou définit si le faux bold est activé.

**Returns:**
booléen
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Obtient ou définit la couleur du remplissage.

Valeur : la couleur du remplissage.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


La ligne de base de la police.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Les majuscules de la police.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Obtient l'index de la police.

Valeur : la police.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Obtient ou définit le nom de la police.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Obtient ou définit la taille de la police.

Valeur : la taille de la police.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Les symboles de fractions peuvent être remplacés par un glyphe spécial.

**Returns:**
booléen
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Obtient ou définit une valeur indiquant si [hindi numbers].

Valeur :  true  si [hindi numbers] ; sinon,  false .

**Returns:**
booléen
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


L'échelle horizontale.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Obtient ou définit le crénage.

Valeur : le crénage entre deux caractères.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Obtient l'index de la langue.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Obtient ou définit l'interligne.

Valeur : l'interligne.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Les ligatures contextuelles standard utilisées pour connecter les lettres entre elles.

**Returns:**
booléen
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Obtient ou définit une valeur indiquant si [strikethrough].

**Returns:**
booléen
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Obtient ou définit la couleur du trait.

Valeur : la couleur du trait.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Obtient ou définit le suivi.

Valeur : le suivi.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Obtient ou définit une valeur indiquant si [underline].

**Returns:**
booléen
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


L'échelle verticale.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Obtient ou définit la valeur de non‑saut.

**Returns:**
booléen
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Détermine si le style spécifié est égal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Le style. |

**Returns:**
booléen -  true  si le style spécifié est égal ; sinon,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Obtient ou définit l'alignement romain vertical standard. Ceci, basé sur la valeur de la ressource BaselineDirection, ne s'applique que lorsque l'orientation du texte est [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
booléen
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Obtient ou définit le crénage automatique.

Valeur : le crénage automatique entre deux caractères.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Obtient ou définit une valeur indiquant si [automatic leading].

Valeur :  true  si [automatic leading] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Le décalage de ligne de base.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Les alternatives contextuelles utilisées pour connecter les lettres entre elles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Les ligatures discrétionnaires utilisées pour connecter les lettres, en particulier dans les polices script.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Obtient ou définit si le faux bold est activé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Obtient ou définit si le faux bold est activé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Obtient ou définit la couleur du remplissage.

Valeur : la couleur du remplissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


La ligne de base de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Les majuscules de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Obtient ou définit le nom de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Obtient ou définit la taille de la police.

Valeur : la taille de la police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Les symboles de fractions peuvent être remplacés par un glyphe spécial.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Obtient ou définit une valeur indiquant si [hindi numbers].

Valeur :  true  si [hindi numbers] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


L'échelle horizontale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Obtient ou définit le crénage.

Valeur : le crénage entre deux caractères.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Obtient ou définit l'interligne.

Valeur : l'interligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Les ligatures contextuelles standard utilisées pour connecter les lettres entre elles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Obtient ou définit une valeur indiquant si [strikethrough].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Obtient ou définit la couleur du trait.

Valeur : la couleur du trait.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Obtient ou définit le suivi.

Valeur : le suivi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Obtient ou définit une valeur indiquant si [underline].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


L'échelle verticale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Obtient ou définit l'alignement romain vertical standard. Ceci, basé sur la valeur de la ressource BaselineDirection, ne s'applique que lorsque l'orientation du texte est [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Obtient ou définit la valeur de non‑saut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |


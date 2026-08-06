---
title: "ITextParagraph"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "L'interface pour travailler avec le paragraphe"
type: docs
weight: 12
url: /fr/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

L'interface pour travailler avec le paragraphe
## Méthodes

| Méthode | Description |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Applique le paragraphe spécifié. |
| [getAutoHyphenate()](#getAutoHyphenate--) | Obtient ou définit une valeur indiquant si [automatic hyphenate]. |
| [getAutoLeading()](#getAutoLeading--) | Obtient ou définit le interligne automatique. |
| [getBurasagari()](#getBurasagari--) | Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est burasagiri. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | Obtient ou définit les tirets consécutifs. |
| [getEndIndent()](#getEndIndent--) | Obtient ou définit le retrait de fin. |
| [getEveryLineComposer()](#getEveryLineComposer--) | Obtient ou définit une valeur indiquant si [every line composer]. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Obtient ou définit le retrait de la première ligne. |
| [getGlyphSpacing()](#getGlyphSpacing--) | Obtient ou définit l'espacement des glyphes. |
| [getHanging()](#getHanging--) | Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est suspendu. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | Obtient ou définit la taille du mot hyphéné. |
| [getJustification()](#getJustification--) | Obtient ou définit la justification. |
| [getKinsokuOrder()](#getKinsokuOrder--) | Obtient ou définit l'ordre kinsoku. |
| [getLeadingType()](#getLeadingType--) | Obtient ou définit le type de l'interligne. |
| [getLetterSpacing()](#getLetterSpacing--) | Obtient ou définit l'espacement des lettres. |
| [getPostHyphen()](#getPostHyphen--) | Obtient ou définit le tiret postérieur. |
| [getPreHyphen()](#getPreHyphen--) | Obtient ou définit le pré-hyphène. |
| [getSpaceAfter()](#getSpaceAfter--) | Obtient ou définit l'espace après. |
| [getSpaceBefore()](#getSpaceBefore--) | Obtient ou définit l'espace avant. |
| [getStartIndent()](#getStartIndent--) | Obtient ou définit le retrait de départ. |
| [getWordSpacing()](#getWordSpacing--) | Obtient ou définit l'espacement des mots. |
| [getZone()](#getZone--) | Obtient ou définit la zone. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Détermine si le paragraphe spécifié est égal. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | Obtient ou définit une valeur indiquant si [automatic hyphenate]. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | Obtient ou définit le interligne automatique. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est burasagiri. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | Obtient ou définit les tirets consécutifs. |
| [setEndIndent(double value)](#setEndIndent-double-) | Obtient ou définit le retrait de fin. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | Obtient ou définit une valeur indiquant si [every line composer]. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | Obtient ou définit le retrait de la première ligne. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | Obtient ou définit l'espacement des glyphes. |
| [setHanging(boolean value)](#setHanging-boolean-) | Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est suspendu. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | Obtient ou définit la taille du mot hyphéné. |
| [setJustification(int value)](#setJustification-int-) | Obtient ou définit la justification. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | Obtient ou définit l'ordre kinsoku. |
| [setLeadingType(int value)](#setLeadingType-int-) | Obtient ou définit le type de l'interligne. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | Obtient ou définit l'espacement des lettres. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | Obtient ou définit le tiret postérieur. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | Obtient ou définit le pré-hyphène. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | Obtient ou définit l'espace après. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | Obtient ou définit l'espace avant. |
| [setStartIndent(double value)](#setStartIndent-double-) | Obtient ou définit le retrait de départ. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | Obtient ou définit l'espacement des mots. |
| [setZone(double value)](#setZone-double-) | Obtient ou définit la zone. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


Applique le paragraphe spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Le paragraphe. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


Obtient ou définit une valeur indiquant si [automatic hyphenate].

Valeur :  true  si [automatic hyphenate] ; sinon,  false .

**Returns:**
booléen
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


Obtient ou définit le interligne automatique.

Valeur : L'interligne automatique.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est burasagiri.

Valeur :  true  si burasagiri ; sinon,  false .

**Returns:**
booléen
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


Obtient ou définit les tirets consécutifs.

Valeur : Les tirets consécutifs.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


Obtient ou définit le retrait de fin.

Valeur : Le retrait de fin.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


Obtient ou définit une valeur indiquant si [every line composer].

Valeur :  true  si [every line composer] ; sinon,  false .

**Returns:**
booléen
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


Obtient ou définit le retrait de la première ligne.

Valeur : Le retrait de la première ligne.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


Obtient ou définit l'espacement des glyphes.

Valeur : L'espacement des glyphes.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est suspendu.

Valeur :  true  si hanging ; sinon,  false .

**Returns:**
booléen
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


Obtient ou définit la taille du mot hyphéné.

Valeur : La taille du mot hyphéné.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Obtient ou définit la justification.

Valeur : La justification.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


Obtient ou définit l'ordre kinsoku.

Valeur : L'ordre kinsoku.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


Obtient ou définit le type de l'interligne.

Valeur : Le type d'interligne.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


Obtient ou définit l'espacement des lettres.

Valeur : L'espacement des lettres.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


Obtient ou définit le tiret postérieur.

Valeur : Le post-hyphène.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


Obtient ou définit le pré-hyphène.

Valeur : Le pré-hyphène.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


Obtient ou définit l'espace après.

Valeur : L'espace après.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


Obtient ou définit l'espace avant.

Valeur: L'espace avant.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


Obtient ou définit le retrait de départ.

Valeur: L'indentation de départ.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


Obtient ou définit l'espacement des mots.

Valeur: L'espacement des mots.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


Obtient ou définit la zone.

Valeur: La zone.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


Détermine si le paragraphe spécifié est égal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Le paragraphe. |

**Returns:**
booléen -  vrai  si le paragraphe spécifié est égal ; sinon,  faux .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


Obtient ou définit une valeur indiquant si [automatic hyphenate].

Valeur :  true  si [automatic hyphenate] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


Obtient ou définit le interligne automatique.

Valeur : L'interligne automatique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est burasagiri.

Valeur :  true  si burasagiri ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


Obtient ou définit les tirets consécutifs.

Valeur : Les tirets consécutifs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


Obtient ou définit le retrait de fin.

Valeur : Le retrait de fin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


Obtient ou définit une valeur indiquant si [every line composer].

Valeur :  true  si [every line composer] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


Obtient ou définit le retrait de la première ligne.

Valeur : Le retrait de la première ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


Obtient ou définit l'espacement des glyphes.

Valeur : L'espacement des glyphes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


Obtient ou définit une valeur indiquant si cet [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) est suspendu.

Valeur :  true  si hanging ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


Obtient ou définit la taille du mot hyphéné.

Valeur : La taille du mot hyphéné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Obtient ou définit la justification.

Valeur : La justification.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


Obtient ou définit l'ordre kinsoku.

Valeur : L'ordre kinsoku.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


Obtient ou définit le type de l'interligne.

Valeur : Le type d'interligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


Obtient ou définit l'espacement des lettres.

Valeur : L'espacement des lettres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


Obtient ou définit le tiret postérieur.

Valeur : Le post-hyphène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


Obtient ou définit le pré-hyphène.

Valeur : Le pré-hyphène.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


Obtient ou définit l'espace après.

Valeur : L'espace après.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


Obtient ou définit l'espace avant.

Valeur: L'espace avant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


Obtient ou définit le retrait de départ.

Valeur: L'indentation de départ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


Obtient ou définit l'espacement des mots.

Valeur: L'espacement des mots.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


Obtient ou définit la zone.

Valeur: La zone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |


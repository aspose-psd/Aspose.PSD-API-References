---
title: "ITextParagraph"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Schnittstelle zur Arbeit mit Absätzen"
type: docs
weight: 12
url: /de/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

Die Schnittstelle zur Arbeit mit Absätzen
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Wendet den angegebenen Absatz an. |
| [getAutoHyphenate()](#getAutoHyphenate--) | Liefert oder setzt einen Wert, der angibt, ob [automatic hyphenate]. |
| [getAutoLeading()](#getAutoLeading--) | Liefert oder setzt den automatischen Zeilenabstand. |
| [getBurasagari()](#getBurasagari--) | Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri ist. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | Liefert oder setzt die aufeinanderfolgenden Bindestriche. |
| [getEndIndent()](#getEndIndent--) | Liefert oder setzt den Endeinzug. |
| [getEveryLineComposer()](#getEveryLineComposer--) | Liefert oder setzt einen Wert, der angibt, ob [every line composer]. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Liefert oder setzt den ersten Zeileneinzug. |
| [getGlyphSpacing()](#getGlyphSpacing--) | Liefert oder setzt den Glyphenabstand. |
| [getHanging()](#getHanging--) | Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hängend ist. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | Liefert oder setzt die Größe des mit Bindestrich getrennten Wortes. |
| [getJustification()](#getJustification--) | Liefert oder setzt die Ausrichtung. |
| [getKinsokuOrder()](#getKinsokuOrder--) | Liefert oder setzt die Kinsoku-Reihenfolge. |
| [getLeadingType()](#getLeadingType--) | Liefert oder setzt den Typ des Zeilenabstands. |
| [getLetterSpacing()](#getLetterSpacing--) | Liefert oder setzt den Buchstabenabstand. |
| [getPostHyphen()](#getPostHyphen--) | Liefert oder setzt den nachfolgenden Bindestrich. |
| [getPreHyphen()](#getPreHyphen--) | Liest oder setzt den Prä-Hyphen. |
| [getSpaceAfter()](#getSpaceAfter--) | Liest oder setzt den Abstand danach. |
| [getSpaceBefore()](#getSpaceBefore--) | Liest oder setzt den Abstand davor. |
| [getStartIndent()](#getStartIndent--) | Liest oder setzt den Anfangseinzug. |
| [getWordSpacing()](#getWordSpacing--) | Liest oder setzt den Wortabstand. |
| [getZone()](#getZone--) | Liest oder setzt die Zone. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Bestimmt, ob der angegebene Absatz gleich ist. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | Liefert oder setzt einen Wert, der angibt, ob [automatic hyphenate]. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | Liefert oder setzt den automatischen Zeilenabstand. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri ist. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | Liefert oder setzt die aufeinanderfolgenden Bindestriche. |
| [setEndIndent(double value)](#setEndIndent-double-) | Liefert oder setzt den Endeinzug. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | Liefert oder setzt einen Wert, der angibt, ob [every line composer]. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | Liefert oder setzt den ersten Zeileneinzug. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | Liefert oder setzt den Glyphenabstand. |
| [setHanging(boolean value)](#setHanging-boolean-) | Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hängend ist. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | Liefert oder setzt die Größe des mit Bindestrich getrennten Wortes. |
| [setJustification(int value)](#setJustification-int-) | Liefert oder setzt die Ausrichtung. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | Liefert oder setzt die Kinsoku-Reihenfolge. |
| [setLeadingType(int value)](#setLeadingType-int-) | Liefert oder setzt den Typ des Zeilenabstands. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | Liefert oder setzt den Buchstabenabstand. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | Liefert oder setzt den nachfolgenden Bindestrich. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | Liest oder setzt den Prä-Hyphen. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | Liest oder setzt den Abstand danach. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | Liest oder setzt den Abstand davor. |
| [setStartIndent(double value)](#setStartIndent-double-) | Liest oder setzt den Anfangseinzug. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | Liest oder setzt den Wortabstand. |
| [setZone(double value)](#setZone-double-) | Liest oder setzt die Zone. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


Wendet den angegebenen Absatz an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Der Absatz. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


Liefert oder setzt einen Wert, der angibt, ob [automatic hyphenate].

Wert:  true  wenn [automatic hyphenate]; andernfalls  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


Liefert oder setzt den automatischen Zeilenabstand.

Wert: Der automatische Zeilenabstand.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri ist.

Wert:  true  wenn burasagiri; andernfalls  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


Liefert oder setzt die aufeinanderfolgenden Bindestriche.

Wert: Die aufeinanderfolgenden Bindestriche.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


Liefert oder setzt den Endeinzug.

Wert: Der Endeinzug.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


Liefert oder setzt einen Wert, der angibt, ob [every line composer].

Wert:  true  wenn [every line composer]; andernfalls  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


Liefert oder setzt den ersten Zeileneinzug.

Wert: Der erste Zeileneinzug.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


Liefert oder setzt den Glyphenabstand.

Wert: Der Glyphenabstand.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hängend ist.

Wert:  true  wenn hanging; andernfalls  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


Liefert oder setzt die Größe des mit Bindestrich getrennten Wortes.

Wert: Die Größe des getrennten Wortes.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Liefert oder setzt die Ausrichtung.

Wert: Der Blocksatz.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


Liefert oder setzt die Kinsoku-Reihenfolge.

Wert: Die Kinsoku-Reihenfolge.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


Liefert oder setzt den Typ des Zeilenabstands.

Wert: Der Typ des Zeilenabstands.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


Liefert oder setzt den Buchstabenabstand.

Wert: Der Buchstabenabstand.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


Liefert oder setzt den nachfolgenden Bindestrich.

Wert: Der Nach-Hyphen.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


Liest oder setzt den Prä-Hyphen.

Wert: Der Prä-Hyphen.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


Liest oder setzt den Abstand danach.

Wert: Der Abstand danach.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


Liest oder setzt den Abstand davor.

Wert: Der Abstand davor.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


Liest oder setzt den Anfangseinzug.

Wert: Der Anfangseinzug.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


Liest oder setzt den Wortabstand.

Wert: Der Wortabstand.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


Liest oder setzt die Zone.

Wert: Die Zone.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


Bestimmt, ob der angegebene Absatz gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Der Absatz. |

**Returns:**
boolean -  true  wenn der angegebene Absatz gleich ist; andernfalls,  false .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob [automatic hyphenate].

Wert:  true  wenn [automatic hyphenate]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


Liefert oder setzt den automatischen Zeilenabstand.

Wert: Der automatische Zeilenabstand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri ist.

Wert:  true  wenn burasagiri; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


Liefert oder setzt die aufeinanderfolgenden Bindestriche.

Wert: Die aufeinanderfolgenden Bindestriche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


Liefert oder setzt den Endeinzug.

Wert: Der Endeinzug.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob [every line composer].

Wert:  true  wenn [every line composer]; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


Liefert oder setzt den ersten Zeileneinzug.

Wert: Der erste Zeileneinzug.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


Liefert oder setzt den Glyphenabstand.

Wert: Der Glyphenabstand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob dieses [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hängend ist.

Wert:  true  wenn hanging; andernfalls  false .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


Liefert oder setzt die Größe des mit Bindestrich getrennten Wortes.

Wert: Die Größe des getrennten Wortes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Liefert oder setzt die Ausrichtung.

Wert: Der Blocksatz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


Liefert oder setzt die Kinsoku-Reihenfolge.

Wert: Die Kinsoku-Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


Liefert oder setzt den Typ des Zeilenabstands.

Wert: Der Typ des Zeilenabstands.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


Liefert oder setzt den Buchstabenabstand.

Wert: Der Buchstabenabstand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


Liefert oder setzt den nachfolgenden Bindestrich.

Wert: Der Nach-Hyphen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


Liest oder setzt den Prä-Hyphen.

Wert: Der Prä-Hyphen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


Liest oder setzt den Abstand danach.

Wert: Der Abstand danach.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


Liest oder setzt den Abstand davor.

Wert: Der Abstand davor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


Liest oder setzt den Anfangseinzug.

Wert: Der Anfangseinzug.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


Liest oder setzt den Wortabstand.

Wert: Der Wortabstand.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


Liest oder setzt die Zone.

Wert: Die Zone.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |


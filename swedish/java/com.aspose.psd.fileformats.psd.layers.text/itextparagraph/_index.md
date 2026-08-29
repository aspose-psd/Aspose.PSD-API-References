---
title: "ITextParagraph"
second_title: "Aspose.PSD för Java API-referens"
description: "Gränssnittet för att arbeta med stycke"
type: docs
weight: 12
url: /sv/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

Gränssnittet för att arbeta med stycke
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Tillämpar det angivna stycket. |
| [getAutoHyphenate()](#getAutoHyphenate--) | Hämtar eller anger ett värde som indikerar om [automatic hyphenate]. |
| [getAutoLeading()](#getAutoLeading--) | Hämtar eller anger det automatiska radavståndet. |
| [getBurasagari()](#getBurasagari--) | Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är burasagiri. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | Hämtar eller anger de på varandra följande bindestrecken. |
| [getEndIndent()](#getEndIndent--) | Hämtar eller anger slutindraget. |
| [getEveryLineComposer()](#getEveryLineComposer--) | Hämtar eller anger ett värde som indikerar om [every line composer]. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Hämtar eller anger indraget för den första raden. |
| [getGlyphSpacing()](#getGlyphSpacing--) | Hämtar eller anger teckenavståndet. |
| [getHanging()](#getHanging--) | Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är hängande. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | Hämtar eller anger storleken på det avstavade ordet. |
| [getJustification()](#getJustification--) | Hämtar eller anger justeringen. |
| [getKinsokuOrder()](#getKinsokuOrder--) | Hämtar eller anger kinsoku-ordningen. |
| [getLeadingType()](#getLeadingType--) | Hämtar eller anger typen av radavstånd. |
| [getLetterSpacing()](#getLetterSpacing--) | Hämtar eller anger teckenavståndet. |
| [getPostHyphen()](#getPostHyphen--) | Hämtar eller anger efterbindestrecket. |
| [getPreHyphen()](#getPreHyphen--) | Hämtar eller anger förbindestrecket. |
| [getSpaceAfter()](#getSpaceAfter--) | Hämtar eller anger utrymmet efter. |
| [getSpaceBefore()](#getSpaceBefore--) | Hämtar eller anger utrymmet före. |
| [getStartIndent()](#getStartIndent--) | Hämtar eller anger startindraget. |
| [getWordSpacing()](#getWordSpacing--) | Hämtar eller anger ordavståndet. |
| [getZone()](#getZone--) | Hämtar eller anger zonen. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Bestämmer om det angivna stycket är lika. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | Hämtar eller anger ett värde som indikerar om [automatic hyphenate]. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | Hämtar eller anger det automatiska radavståndet. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är burasagiri. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | Hämtar eller anger de på varandra följande bindestrecken. |
| [setEndIndent(double value)](#setEndIndent-double-) | Hämtar eller anger slutindraget. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | Hämtar eller anger ett värde som indikerar om [every line composer]. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | Hämtar eller anger indraget för den första raden. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | Hämtar eller anger teckenavståndet. |
| [setHanging(boolean value)](#setHanging-boolean-) | Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är hängande. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | Hämtar eller anger storleken på det avstavade ordet. |
| [setJustification(int value)](#setJustification-int-) | Hämtar eller anger justeringen. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | Hämtar eller anger kinsoku-ordningen. |
| [setLeadingType(int value)](#setLeadingType-int-) | Hämtar eller anger typen av radavstånd. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | Hämtar eller anger teckenavståndet. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | Hämtar eller anger efterbindestrecket. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | Hämtar eller anger förbindestrecket. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | Hämtar eller anger utrymmet efter. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | Hämtar eller anger utrymmet före. |
| [setStartIndent(double value)](#setStartIndent-double-) | Hämtar eller anger startindraget. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | Hämtar eller anger ordavståndet. |
| [setZone(double value)](#setZone-double-) | Hämtar eller anger zonen. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


Tillämpar det angivna stycket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Stycket. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


Hämtar eller anger ett värde som indikerar om [automatic hyphenate].

Värde:  true  om [automatic hyphenate]; annars,  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


Hämtar eller anger det automatiska radavståndet.

Värde: Det automatiska radavståndet.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är burasagiri.

Värde:  true  om burasagiri; annars,  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


Hämtar eller anger de på varandra följande bindestrecken.

Värde: De på varandra följande bindestrecken.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


Hämtar eller anger slutindraget.

Värde: Slutindraget.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


Hämtar eller anger ett värde som indikerar om [every line composer].

Värde:  true  om [every line composer]; annars,  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


Hämtar eller anger indraget för den första raden.

Värde: Första radens indrag.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


Hämtar eller anger teckenavståndet.

Värde: Teckengapet.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är hängande.

Värde:  true  om hängande; annars,  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


Hämtar eller anger storleken på det avstavade ordet.

Värde: Storleken på det avstavade ordet.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Hämtar eller anger justeringen.

Värde: Justeringen.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


Hämtar eller anger kinsoku-ordningen.

Värde: Kinsoku-ordningen.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


Hämtar eller anger typen av radavstånd.

Värde: Typen av radavståndet.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


Hämtar eller anger teckenavståndet.

Värde: Teckenavståndet.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


Hämtar eller anger efterbindestrecket.

Värde: Efterbindestrecket.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


Hämtar eller anger förbindestrecket.

Värde: Förebindestrecket.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


Hämtar eller anger utrymmet efter.

Värde: Utrymmet efter.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


Hämtar eller anger utrymmet före.

Värde: Utrymmet före.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


Hämtar eller anger startindraget.

Värde: Startindraget.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


Hämtar eller anger ordavståndet.

Värde: Ordavståndet.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


Hämtar eller anger zonen.

Värde: Zonen.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


Bestämmer om det angivna stycket är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Stycket. |

**Returns:**
boolean -  true  om det angivna stycket är lika; annars,  false .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


Hämtar eller anger ett värde som indikerar om [automatic hyphenate].

Värde:  true  om [automatic hyphenate]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


Hämtar eller anger det automatiska radavståndet.

Värde: Det automatiska radavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är burasagiri.

Värde:  true  om burasagiri; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


Hämtar eller anger de på varandra följande bindestrecken.

Värde: De på varandra följande bindestrecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


Hämtar eller anger slutindraget.

Värde: Slutindraget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


Hämtar eller anger ett värde som indikerar om [every line composer].

Värde:  true  om [every line composer]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


Hämtar eller anger indraget för den första raden.

Värde: Första radens indrag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


Hämtar eller anger teckenavståndet.

Värde: Teckengapet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


Hämtar eller anger ett värde som indikerar om detta [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) är hängande.

Värde:  true  om hängande; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


Hämtar eller anger storleken på det avstavade ordet.

Värde: Storleken på det avstavade ordet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Hämtar eller anger justeringen.

Värde: Justeringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


Hämtar eller anger kinsoku-ordningen.

Värde: Kinsoku-ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


Hämtar eller anger typen av radavstånd.

Värde: Typen av radavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


Hämtar eller anger teckenavståndet.

Värde: Teckenavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


Hämtar eller anger efterbindestrecket.

Värde: Efterbindestrecket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


Hämtar eller anger förbindestrecket.

Värde: Förebindestrecket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


Hämtar eller anger utrymmet efter.

Värde: Utrymmet efter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


Hämtar eller anger utrymmet före.

Värde: Utrymmet före.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


Hämtar eller anger startindraget.

Värde: Startindraget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


Hämtar eller anger ordavståndet.

Värde: Ordavståndet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


Hämtar eller anger zonen.

Värde: Zonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |


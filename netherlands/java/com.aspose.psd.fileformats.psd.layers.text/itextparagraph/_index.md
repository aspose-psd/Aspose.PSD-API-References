---
title: "ITextParagraph"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De interface om met alinea's te werken"
type: docs
weight: 12
url: /nl/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

De interface om met alinea's te werken
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Past de opgegeven alinea toe. |
| [getAutoHyphenate()](#getAutoHyphenate--) | Haalt een waarde op of stelt deze in die aangeeft of [automatic hyphenate]. |
| [getAutoLeading()](#getAutoLeading--) | Haalt de automatische regelafstand op of stelt deze in. |
| [getBurasagari()](#getBurasagari--) | Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri is. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | Haalt de opeenvolgende koppeltekens op of stelt deze in. |
| [getEndIndent()](#getEndIndent--) | Haalt de eindinspringing op of stelt deze in. |
| [getEveryLineComposer()](#getEveryLineComposer--) | Haalt een waarde op of stelt deze in die aangeeft of [every line composer]. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Haalt de eerste regelinspringing op of stelt deze in. |
| [getGlyphSpacing()](#getGlyphSpacing--) | Haalt de glyph-spatiëring op of stelt deze in. |
| [getHanging()](#getHanging--) | Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hangend is. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | Haalt de grootte van het afgebroken woord op of stelt deze in. |
| [getJustification()](#getJustification--) | Haalt de uitlijning op of stelt deze in. |
| [getKinsokuOrder()](#getKinsokuOrder--) | Haalt de kinsoku-volgorde op of stelt deze in. |
| [getLeadingType()](#getLeadingType--) | Haalt het type van de regelafstand op of stelt dit in. |
| [getLetterSpacing()](#getLetterSpacing--) | Haalt de letterspatiëring op of stelt deze in. |
| [getPostHyphen()](#getPostHyphen--) | Haalt het achterste koppelteken op of stelt dit in. |
| [getPreHyphen()](#getPreHyphen--) | Haalt het voorste koppelteken op of stelt dit in. |
| [getSpaceAfter()](#getSpaceAfter--) | Haalt de spatie erna op of stelt deze in. |
| [getSpaceBefore()](#getSpaceBefore--) | Haalt de spatie ervoor op of stelt deze in. |
| [getStartIndent()](#getStartIndent--) | Haalt de begininspringing op of stelt deze in. |
| [getWordSpacing()](#getWordSpacing--) | Haalt de woordspatiëring op of stelt deze in. |
| [getZone()](#getZone--) | Haalt de zone op of stelt deze in. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Bepaalt of de opgegeven alinea gelijk is. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of [automatic hyphenate]. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | Haalt de automatische regelafstand op of stelt deze in. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri is. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | Haalt de opeenvolgende koppeltekens op of stelt deze in. |
| [setEndIndent(double value)](#setEndIndent-double-) | Haalt de eindinspringing op of stelt deze in. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of [every line composer]. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | Haalt de eerste regelinspringing op of stelt deze in. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | Haalt de glyph-spatiëring op of stelt deze in. |
| [setHanging(boolean value)](#setHanging-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hangend is. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | Haalt de grootte van het afgebroken woord op of stelt deze in. |
| [setJustification(int value)](#setJustification-int-) | Haalt de uitlijning op of stelt deze in. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | Haalt de kinsoku-volgorde op of stelt deze in. |
| [setLeadingType(int value)](#setLeadingType-int-) | Haalt het type van de regelafstand op of stelt dit in. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | Haalt de letterspatiëring op of stelt deze in. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | Haalt het achterste koppelteken op of stelt dit in. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | Haalt het voorste koppelteken op of stelt dit in. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | Haalt de spatie erna op of stelt deze in. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | Haalt de spatie ervoor op of stelt deze in. |
| [setStartIndent(double value)](#setStartIndent-double-) | Haalt de begininspringing op of stelt deze in. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | Haalt de woordspatiëring op of stelt deze in. |
| [setZone(double value)](#setZone-double-) | Haalt de zone op of stelt deze in. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


Past de opgegeven alinea toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | De alinea. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


Haalt een waarde op of stelt deze in die aangeeft of [automatic hyphenate].

Waarde:  true  als [automatic hyphenate]; anders,  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


Haalt de automatische regelafstand op of stelt deze in.

Waarde: De automatische regelafstand.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri is.

Waarde:  true  als burasagiri; anders,  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


Haalt de opeenvolgende koppeltekens op of stelt deze in.

Waarde: De opeenvolgende koppeltekens.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


Haalt de eindinspringing op of stelt deze in.

Waarde: De eindinspringing.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


Haalt een waarde op of stelt deze in die aangeeft of [every line composer].

Waarde:  true  als [every line composer]; anders,  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


Haalt de eerste regelinspringing op of stelt deze in.

Waarde: De eerste regelinspringing.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


Haalt de glyph-spatiëring op of stelt deze in.

Waarde: De glyph-spatiëring.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hangend is.

Waarde:  true  als hanging; anders,  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


Haalt de grootte van het afgebroken woord op of stelt deze in.

Waarde: De grootte van het woord met koppelteken.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Haalt de uitlijning op of stelt deze in.

Waarde: De uitlijning.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


Haalt de kinsoku-volgorde op of stelt deze in.

Waarde: De kinsoku-volgorde.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


Haalt het type van de regelafstand op of stelt dit in.

Waarde: Het type van de leading.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


Haalt de letterspatiëring op of stelt deze in.

Waarde: De letterspatiëring.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


Haalt het achterste koppelteken op of stelt dit in.

Waarde: Het achterste koppelteken.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


Haalt het voorste koppelteken op of stelt dit in.

Waarde: Het voorste koppelteken.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


Haalt de spatie erna op of stelt deze in.

Waarde: De spatie erna.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


Haalt de spatie ervoor op of stelt deze in.

Waarde: De spatie ervoor.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


Haalt de begininspringing op of stelt deze in.

Waarde: De begininspringing.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


Haalt de woordspatiëring op of stelt deze in.

Waarde: De woordspatiëring.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


Haalt de zone op of stelt deze in.

Waarde: De zone.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


Bepaalt of de opgegeven alinea gelijk is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | De alinea. |

**Returns:**
boolean -  true  als de opgegeven alinea gelijk is; anders,  false .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of [automatic hyphenate].

Waarde:  true  als [automatic hyphenate]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


Haalt de automatische regelafstand op of stelt deze in.

Waarde: De automatische regelafstand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri is.

Waarde:  true  als burasagiri; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


Haalt de opeenvolgende koppeltekens op of stelt deze in.

Waarde: De opeenvolgende koppeltekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


Haalt de eindinspringing op of stelt deze in.

Waarde: De eindinspringing.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of [every line composer].

Waarde:  true  als [every line composer]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


Haalt de eerste regelinspringing op of stelt deze in.

Waarde: De eerste regelinspringing.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


Haalt de glyph-spatiëring op of stelt deze in.

Waarde: De glyph-spatiëring.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of dit [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) hangend is.

Waarde:  true  als hanging; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


Haalt de grootte van het afgebroken woord op of stelt deze in.

Waarde: De grootte van het woord met koppelteken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Haalt de uitlijning op of stelt deze in.

Waarde: De uitlijning.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


Haalt de kinsoku-volgorde op of stelt deze in.

Waarde: De kinsoku-volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


Haalt het type van de regelafstand op of stelt dit in.

Waarde: Het type van de leading.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


Haalt de letterspatiëring op of stelt deze in.

Waarde: De letterspatiëring.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


Haalt het achterste koppelteken op of stelt dit in.

Waarde: Het achterste koppelteken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


Haalt het voorste koppelteken op of stelt dit in.

Waarde: Het voorste koppelteken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


Haalt de spatie erna op of stelt deze in.

Waarde: De spatie erna.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


Haalt de spatie ervoor op of stelt deze in.

Waarde: De spatie ervoor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


Haalt de begininspringing op of stelt deze in.

Waarde: De begininspringing.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


Haalt de woordspatiëring op of stelt deze in.

Waarde: De woordspatiëring.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


Haalt de zone op of stelt deze in.

Waarde: De zone.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |


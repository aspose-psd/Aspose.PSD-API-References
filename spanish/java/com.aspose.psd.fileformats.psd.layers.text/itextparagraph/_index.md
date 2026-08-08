---
title: "ITextParagraph"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La interfaz para trabajar con párrafos"
type: docs
weight: 12
url: /es/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

La interfaz para trabajar con párrafos
## Métodos

| Método | Descripción |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Aplica el párrafo especificado. |
| [getAutoHyphenate()](#getAutoHyphenate--) | Obtiene o establece un valor que indica si [automatic hyphenate]. |
| [getAutoLeading()](#getAutoLeading--) | Obtiene o establece el interlineado automático. |
| [getBurasagari()](#getBurasagari--) | Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) es burasagiri. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | Obtiene o establece los guiones consecutivos. |
| [getEndIndent()](#getEndIndent--) | Obtiene o establece la sangría final. |
| [getEveryLineComposer()](#getEveryLineComposer--) | Obtiene o establece un valor que indica si [every line composer]. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Obtiene o establece la sangría de la primera línea. |
| [getGlyphSpacing()](#getGlyphSpacing--) | Obtiene o establece el espaciado de glifos. |
| [getHanging()](#getHanging--) | Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) está colgante. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | Obtiene o establece el tamaño de la palabra con guión. |
| [getJustification()](#getJustification--) | Obtiene o establece la justificación. |
| [getKinsokuOrder()](#getKinsokuOrder--) | Obtiene o establece el orden kinsoku. |
| [getLeadingType()](#getLeadingType--) | Obtiene o establece el tipo de interlineado. |
| [getLetterSpacing()](#getLetterSpacing--) | Obtiene o establece el espaciado de letras. |
| [getPostHyphen()](#getPostHyphen--) | Obtiene o establece el guión posterior. |
| [getPreHyphen()](#getPreHyphen--) | Obtiene o establece el guión previo. |
| [getSpaceAfter()](#getSpaceAfter--) | Obtiene o establece el espacio después. |
| [getSpaceBefore()](#getSpaceBefore--) | Obtiene o establece el espacio antes. |
| [getStartIndent()](#getStartIndent--) | Obtiene o establece la sangría inicial. |
| [getWordSpacing()](#getWordSpacing--) | Obtiene o establece el espaciado de palabras. |
| [getZone()](#getZone--) | Obtiene o establece la zona. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Determina si el párrafo especificado es igual. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | Obtiene o establece un valor que indica si [automatic hyphenate]. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | Obtiene o establece el interlineado automático. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) es burasagiri. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | Obtiene o establece los guiones consecutivos. |
| [setEndIndent(double value)](#setEndIndent-double-) | Obtiene o establece la sangría final. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | Obtiene o establece un valor que indica si [every line composer]. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | Obtiene o establece la sangría de la primera línea. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | Obtiene o establece el espaciado de glifos. |
| [setHanging(boolean value)](#setHanging-boolean-) | Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) está colgante. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | Obtiene o establece el tamaño de la palabra con guión. |
| [setJustification(int value)](#setJustification-int-) | Obtiene o establece la justificación. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | Obtiene o establece el orden kinsoku. |
| [setLeadingType(int value)](#setLeadingType-int-) | Obtiene o establece el tipo de interlineado. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | Obtiene o establece el espaciado de letras. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | Obtiene o establece el guión posterior. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | Obtiene o establece el guión previo. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | Obtiene o establece el espacio después. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | Obtiene o establece el espacio antes. |
| [setStartIndent(double value)](#setStartIndent-double-) | Obtiene o establece la sangría inicial. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | Obtiene o establece el espaciado de palabras. |
| [setZone(double value)](#setZone-double-) | Obtiene o establece la zona. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


Aplica el párrafo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | El párrafo. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


Obtiene o establece un valor que indica si [automatic hyphenate].

Valor:  true  si [automatic hyphenate]; de lo contrario,  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


Obtiene o establece el interlineado automático.

Valor: El interlineado automático.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) es burasagiri.

Valor:  true  si burasagiri; de lo contrario,  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


Obtiene o establece los guiones consecutivos.

Valor: Los guiones consecutivos.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


Obtiene o establece la sangría final.

Valor: La sangría final.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


Obtiene o establece un valor que indica si [every line composer].

Valor:  true  si [every line composer]; de lo contrario,  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


Obtiene o establece la sangría de la primera línea.

Valor: La sangría de la primera línea.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


Obtiene o establece el espaciado de glifos.

Valor: El espaciado de glifos.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) está colgante.

Valor:  true  si colgante; de lo contrario,  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


Obtiene o establece el tamaño de la palabra con guión.

Valor: El tamaño de la palabra con guión.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Obtiene o establece la justificación.

Valor: La justificación.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


Obtiene o establece el orden kinsoku.

Valor: El orden kinsoku.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


Obtiene o establece el tipo de interlineado.

Valor: El tipo de interlineado.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


Obtiene o establece el espaciado de letras.

Valor: El espaciado entre letras.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


Obtiene o establece el guión posterior.

Valor: El guion posterior.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


Obtiene o establece el guión previo.

Valor: El guion anterior.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


Obtiene o establece el espacio después.

Valor: El espacio posterior.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


Obtiene o establece el espacio antes.

Valor: El espacio anterior.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


Obtiene o establece la sangría inicial.

Valor: La sangría inicial.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


Obtiene o establece el espaciado de palabras.

Valor: El espaciado de palabras.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


Obtiene o establece la zona.

Valor: La zona.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


Determina si el párrafo especificado es igual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | El párrafo. |

**Returns:**
boolean -  true  si el párrafo especificado es igual; de lo contrario,  false .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


Obtiene o establece un valor que indica si [automatic hyphenate].

Valor:  true  si [automatic hyphenate]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


Obtiene o establece el interlineado automático.

Valor: El interlineado automático.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) es burasagiri.

Valor:  true  si burasagiri; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


Obtiene o establece los guiones consecutivos.

Valor: Los guiones consecutivos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


Obtiene o establece la sangría final.

Valor: La sangría final.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


Obtiene o establece un valor que indica si [every line composer].

Valor:  true  si [every line composer]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


Obtiene o establece la sangría de la primera línea.

Valor: La sangría de la primera línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


Obtiene o establece el espaciado de glifos.

Valor: El espaciado de glifos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


Obtiene o establece un valor que indica si este [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) está colgante.

Valor:  true  si colgante; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


Obtiene o establece el tamaño de la palabra con guión.

Valor: El tamaño de la palabra con guión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Obtiene o establece la justificación.

Valor: La justificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


Obtiene o establece el orden kinsoku.

Valor: El orden kinsoku.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


Obtiene o establece el tipo de interlineado.

Valor: El tipo de interlineado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


Obtiene o establece el espaciado de letras.

Valor: El espaciado entre letras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


Obtiene o establece el guión posterior.

Valor: El guion posterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


Obtiene o establece el guión previo.

Valor: El guion anterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


Obtiene o establece el espacio después.

Valor: El espacio posterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


Obtiene o establece el espacio antes.

Valor: El espacio anterior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


Obtiene o establece la sangría inicial.

Valor: La sangría inicial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


Obtiene o establece el espaciado de palabras.

Valor: El espaciado de palabras.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


Obtiene o establece la zona.

Valor: La zona.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |


---
title: "ITextParagraph"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الواجهة للعمل مع الفقرة."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

الواجهة للعمل مع الفقرة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | يطبق الفقرة المحددة. |
| [getAutoHyphenate()](#getAutoHyphenate--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [automatic hyphenate]. |
| [getAutoLeading()](#getAutoLeading--) | يحصل أو يعيّن المسافة الرائدة التلقائية. |
| [getBurasagari()](#getBurasagari--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) هو burasagiri. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | يحصل أو يعيّن الشرطات المتتالية. |
| [getEndIndent()](#getEndIndent--) | يحصل أو يعيّن مسافة الإزاحة النهائية. |
| [getEveryLineComposer()](#getEveryLineComposer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [every line composer]. |
| [getFirstLineIndent()](#getFirstLineIndent--) | يحصل أو يعيّن مسافة إزاحة السطر الأول. |
| [getGlyphSpacing()](#getGlyphSpacing--) | يحصل أو يعيّن تباعد الرموز. |
| [getHanging()](#getHanging--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) معلقًا. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | يحصل أو يعيّن حجم الكلمة المقطعة. |
| [getJustification()](#getJustification--) | يحصل أو يعيّن المحاذاة. |
| [getKinsokuOrder()](#getKinsokuOrder--) | يحصل أو يعيّن ترتيب كينسوكو. |
| [getLeadingType()](#getLeadingType--) | يحصل أو يعيّن نوع المسافة الرائدة. |
| [getLetterSpacing()](#getLetterSpacing--) | يحصل أو يعيّن تباعد الحروف. |
| [getPostHyphen()](#getPostHyphen--) | يحصل أو يعيّن الفاصلة بعد الواصل. |
| [getPreHyphen()](#getPreHyphen--) | يحصل أو يضبط الفاصل القبلي. |
| [getSpaceAfter()](#getSpaceAfter--) | يحصل أو يضبط المسافة بعد. |
| [getSpaceBefore()](#getSpaceBefore--) | يحصل أو يضبط المسافة قبل. |
| [getStartIndent()](#getStartIndent--) | يحصل أو يضبط مسافة البادئة البداية. |
| [getWordSpacing()](#getWordSpacing--) | يحصل أو يضبط تباعد الكلمات. |
| [getZone()](#getZone--) | يحصل أو يضبط المنطقة. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | يحدد ما إذا كان الفقرة المحددة متساوية. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [automatic hyphenate]. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | يحصل أو يعيّن المسافة الرائدة التلقائية. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) هو burasagiri. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | يحصل أو يعيّن الشرطات المتتالية. |
| [setEndIndent(double value)](#setEndIndent-double-) | يحصل أو يعيّن مسافة الإزاحة النهائية. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [every line composer]. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | يحصل أو يعيّن مسافة إزاحة السطر الأول. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | يحصل أو يعيّن تباعد الرموز. |
| [setHanging(boolean value)](#setHanging-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) معلقًا. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | يحصل أو يعيّن حجم الكلمة المقطعة. |
| [setJustification(int value)](#setJustification-int-) | يحصل أو يعيّن المحاذاة. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | يحصل أو يعيّن ترتيب كينسوكو. |
| [setLeadingType(int value)](#setLeadingType-int-) | يحصل أو يعيّن نوع المسافة الرائدة. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | يحصل أو يعيّن تباعد الحروف. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | يحصل أو يعيّن الفاصلة بعد الواصل. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | يحصل أو يضبط الفاصل القبلي. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | يحصل أو يضبط المسافة بعد. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | يحصل أو يضبط المسافة قبل. |
| [setStartIndent(double value)](#setStartIndent-double-) | يحصل أو يضبط مسافة البادئة البداية. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | يحصل أو يضبط تباعد الكلمات. |
| [setZone(double value)](#setZone-double-) | يحصل أو يضبط المنطقة. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


يطبق الفقرة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | الفقرة. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [automatic hyphenate].

القيمة:  true  إذا [automatic hyphenate]; وإلا،  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


يحصل أو يعيّن المسافة الرائدة التلقائية.

القيمة: التباعد التلقائي.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) هو burasagiri.

القيمة:  true  إذا burasagiri; وإلا،  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


يحصل أو يعيّن الشرطات المتتالية.

القيمة: الفواصل المتتالية.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


يحصل أو يعيّن مسافة الإزاحة النهائية.

القيمة: مسافة البادئة النهائية.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [every line composer].

القيمة:  true  إذا [every line composer]; وإلا،  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


يحصل أو يعيّن مسافة إزاحة السطر الأول.

القيمة: مسافة البادئة للسطر الأول.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


يحصل أو يعيّن تباعد الرموز.

القيمة: تباعد الرموز.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) معلقًا.

القيمة:  true  إذا hanging; وإلا،  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


يحصل أو يعيّن حجم الكلمة المقطعة.

القيمة: حجم الكلمة المقطعة.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


يحصل أو يعيّن المحاذاة.

القيمة: المحاذاة.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


يحصل أو يعيّن ترتيب كينسوكو.

القيمة: ترتيب كينسوكو.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


يحصل أو يعيّن نوع المسافة الرائدة.

القيمة: نوع التباعد.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


يحصل أو يعيّن تباعد الحروف.

القيمة: تباعد الحروف.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


يحصل أو يعيّن الفاصلة بعد الواصل.

القيمة: الفاصل اللاحق.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


يحصل أو يضبط الفاصل القبلي.

القيمة: الفاصل القبلي.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


يحصل أو يضبط المسافة بعد.

القيمة: المسافة بعد.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


يحصل أو يضبط المسافة قبل.

القيمة: المسافة قبل.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


يحصل أو يضبط مسافة البادئة البداية.

القيمة: المسافة البادئة للبدء.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


يحصل أو يضبط تباعد الكلمات.

القيمة: تباعد الكلمات.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


يحصل أو يضبط المنطقة.

القيمة: المنطقة.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


يحدد ما إذا كان الفقرة المحددة متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | الفقرة. |

**Returns:**
منطقي -  true  إذا كان الفقرة المحددة متساوية؛ وإلا،  false .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [automatic hyphenate].

القيمة:  true  إذا [automatic hyphenate]; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


يحصل أو يعيّن المسافة الرائدة التلقائية.

القيمة: التباعد التلقائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) هو burasagiri.

القيمة:  true  إذا burasagiri; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


يحصل أو يعيّن الشرطات المتتالية.

القيمة: الفواصل المتتالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


يحصل أو يعيّن مسافة الإزاحة النهائية.

القيمة: مسافة البادئة النهائية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان [every line composer].

القيمة:  true  إذا [every line composer]; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


يحصل أو يعيّن مسافة إزاحة السطر الأول.

القيمة: مسافة البادئة للسطر الأول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


يحصل أو يعيّن تباعد الرموز.

القيمة: تباعد الرموز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) معلقًا.

القيمة:  true  إذا hanging; وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


يحصل أو يعيّن حجم الكلمة المقطعة.

القيمة: حجم الكلمة المقطعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


يحصل أو يعيّن المحاذاة.

القيمة: المحاذاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


يحصل أو يعيّن ترتيب كينسوكو.

القيمة: ترتيب كينسوكو.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


يحصل أو يعيّن نوع المسافة الرائدة.

القيمة: نوع التباعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


يحصل أو يعيّن تباعد الحروف.

القيمة: تباعد الحروف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


يحصل أو يعيّن الفاصلة بعد الواصل.

القيمة: الفاصل اللاحق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


يحصل أو يضبط الفاصل القبلي.

القيمة: الفاصل القبلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


يحصل أو يضبط المسافة بعد.

القيمة: المسافة بعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


يحصل أو يضبط المسافة قبل.

القيمة: المسافة قبل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


يحصل أو يضبط مسافة البادئة البداية.

القيمة: المسافة البادئة للبدء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


يحصل أو يضبط تباعد الكلمات.

القيمة: تباعد الكلمات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


يحصل أو يضبط المنطقة.

القيمة: المنطقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |


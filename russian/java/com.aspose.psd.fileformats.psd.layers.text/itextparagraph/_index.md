---
title: "ITextParagraph"
second_title: "Aspose.PSD for Java API Справочник"
description: "Интерфейс для работы с абзацем."
type: docs
weight: 12
url: /ru/java/com.aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
```
public interface ITextParagraph
```

Интерфейс для работы с абзацем.
## Методы

| Метод | Описание |
| --- | --- |
| [apply(ITextParagraph paragraph)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Применяет указанный абзац. |
| [getAutoHyphenate()](#getAutoHyphenate--) | Получает или задает значение, указывающее, включено ли [automatic hyphenate]. |
| [getAutoLeading()](#getAutoLeading--) | Получает или задает автоматический интерлиньяж. |
| [getBurasagari()](#getBurasagari--) | Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri. |
| [getConsecutiveHyphens()](#getConsecutiveHyphens--) | Получает или задает последовательные дефисы. |
| [getEndIndent()](#getEndIndent--) | Получает или задает отступ в конце. |
| [getEveryLineComposer()](#getEveryLineComposer--) | Получает или задает значение, указывающее, включен ли [every line composer]. |
| [getFirstLineIndent()](#getFirstLineIndent--) | Получает или задает отступ первой строки. |
| [getGlyphSpacing()](#getGlyphSpacing--) | Получает или задает интервал между глифами. |
| [getHanging()](#getHanging--) | Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) висячим. |
| [getHyphenatedWordSize()](#getHyphenatedWordSize--) | Получает или задает размер переносимого слова. |
| [getJustification()](#getJustification--) | Получает или задает выравнивание. |
| [getKinsokuOrder()](#getKinsokuOrder--) | Получает или задает порядок кинсоку. |
| [getLeadingType()](#getLeadingType--) | Получает или задает тип интерлиньяжа. |
| [getLetterSpacing()](#getLetterSpacing--) | Получает или задает межбуквенный интервал. |
| [getPostHyphen()](#getPostHyphen--) | Получает или задает постдефис. |
| [getPreHyphen()](#getPreHyphen--) | Получает или задает преддефис. |
| [getSpaceAfter()](#getSpaceAfter--) | Получает или задает отступ после. |
| [getSpaceBefore()](#getSpaceBefore--) | Получает или задает отступ перед. |
| [getStartIndent()](#getStartIndent--) | Получает или задает начальный отступ. |
| [getWordSpacing()](#getWordSpacing--) | Получает или задает интервал между словами. |
| [getZone()](#getZone--) | Получает или задает зону. |
| [isEqual(ITextParagraph paragraph)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Определяет, равен ли указанный абзац. |
| [setAutoHyphenate(boolean value)](#setAutoHyphenate-boolean-) | Получает или задает значение, указывающее, включено ли [automatic hyphenate]. |
| [setAutoLeading(double value)](#setAutoLeading-double-) | Получает или задает автоматический интерлиньяж. |
| [setBurasagari(boolean value)](#setBurasagari-boolean-) | Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri. |
| [setConsecutiveHyphens(int value)](#setConsecutiveHyphens-int-) | Получает или задает последовательные дефисы. |
| [setEndIndent(double value)](#setEndIndent-double-) | Получает или задает отступ в конце. |
| [setEveryLineComposer(boolean value)](#setEveryLineComposer-boolean-) | Получает или задает значение, указывающее, включен ли [every line composer]. |
| [setFirstLineIndent(double value)](#setFirstLineIndent-double-) | Получает или задает отступ первой строки. |
| [setGlyphSpacing(double[] value)](#setGlyphSpacing-double---) | Получает или задает интервал между глифами. |
| [setHanging(boolean value)](#setHanging-boolean-) | Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) висячим. |
| [setHyphenatedWordSize(int value)](#setHyphenatedWordSize-int-) | Получает или задает размер переносимого слова. |
| [setJustification(int value)](#setJustification-int-) | Получает или задает выравнивание. |
| [setKinsokuOrder(int value)](#setKinsokuOrder-int-) | Получает или задает порядок кинсоку. |
| [setLeadingType(int value)](#setLeadingType-int-) | Получает или задает тип интерлиньяжа. |
| [setLetterSpacing(double[] value)](#setLetterSpacing-double---) | Получает или задает межбуквенный интервал. |
| [setPostHyphen(int value)](#setPostHyphen-int-) | Получает или задает постдефис. |
| [setPreHyphen(int value)](#setPreHyphen-int-) | Получает или задает преддефис. |
| [setSpaceAfter(double value)](#setSpaceAfter-double-) | Получает или задает отступ после. |
| [setSpaceBefore(double value)](#setSpaceBefore-double-) | Получает или задает отступ перед. |
| [setStartIndent(double value)](#setStartIndent-double-) | Получает или задает начальный отступ. |
| [setWordSpacing(double[] value)](#setWordSpacing-double---) | Получает или задает интервал между словами. |
| [setZone(double value)](#setZone-double-) | Получает или задает зону. |
### apply(ITextParagraph paragraph) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract void apply(ITextParagraph paragraph)
```


Применяет указанный абзац.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Абзац. |

### getAutoHyphenate() {#getAutoHyphenate--}
```
public abstract boolean getAutoHyphenate()
```


Получает или задает значение, указывающее, включено ли [automatic hyphenate].

Значение:  true  если [automatic hyphenate]; иначе,  false .

**Returns:**
boolean
### getAutoLeading() {#getAutoLeading--}
```
public abstract double getAutoLeading()
```


Получает или задает автоматический интерлиньяж.

Значение: Автоматический интерлиньяж.

**Returns:**
double
### getBurasagari() {#getBurasagari--}
```
public abstract boolean getBurasagari()
```


Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri.

Значение:  true  если burasagiri; иначе,  false .

**Returns:**
boolean
### getConsecutiveHyphens() {#getConsecutiveHyphens--}
```
public abstract int getConsecutiveHyphens()
```


Получает или задает последовательные дефисы.

Значение: Последовательные дефисы.

**Returns:**
int
### getEndIndent() {#getEndIndent--}
```
public abstract double getEndIndent()
```


Получает или задает отступ в конце.

Значение: Конечный отступ.

**Returns:**
double
### getEveryLineComposer() {#getEveryLineComposer--}
```
public abstract boolean getEveryLineComposer()
```


Получает или задает значение, указывающее, включен ли [every line composer].

Значение:  true  если [every line composer]; иначе,  false .

**Returns:**
boolean
### getFirstLineIndent() {#getFirstLineIndent--}
```
public abstract double getFirstLineIndent()
```


Получает или задает отступ первой строки.

Значение: Отступ первой строки.

**Returns:**
double
### getGlyphSpacing() {#getGlyphSpacing--}
```
public abstract double[] getGlyphSpacing()
```


Получает или задает интервал между глифами.

Значение: Интервал между глифами.

**Returns:**
double[]
### getHanging() {#getHanging--}
```
public abstract boolean getHanging()
```


Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) висячим.

Значение:  true  если hanging; иначе,  false .

**Returns:**
boolean
### getHyphenatedWordSize() {#getHyphenatedWordSize--}
```
public abstract int getHyphenatedWordSize()
```


Получает или задает размер переносимого слова.

Значение: Размер переносного слова.

**Returns:**
int
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Получает или задает выравнивание.

Значение: Выравнивание.

**Returns:**
int
### getKinsokuOrder() {#getKinsokuOrder--}
```
public abstract int getKinsokuOrder()
```


Получает или задает порядок кинсоку.

Значение: Порядок кинсоку.

**Returns:**
int
### getLeadingType() {#getLeadingType--}
```
public abstract int getLeadingType()
```


Получает или задает тип интерлиньяжа.

Значение: Тип межстрочного интервала.

**Returns:**
int
### getLetterSpacing() {#getLetterSpacing--}
```
public abstract double[] getLetterSpacing()
```


Получает или задает межбуквенный интервал.

Значение: Межбуквенный интервал.

**Returns:**
double[]
### getPostHyphen() {#getPostHyphen--}
```
public abstract int getPostHyphen()
```


Получает или задает постдефис.

Значение: Постфикс дефиса.

**Returns:**
int
### getPreHyphen() {#getPreHyphen--}
```
public abstract int getPreHyphen()
```


Получает или задает преддефис.

Значение: Префикс дефиса.

**Returns:**
int
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract double getSpaceAfter()
```


Получает или задает отступ после.

Значение: Пробел после.

**Returns:**
double
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract double getSpaceBefore()
```


Получает или задает отступ перед.

Значение: Пробел перед.

**Returns:**
double
### getStartIndent() {#getStartIndent--}
```
public abstract double getStartIndent()
```


Получает или задает начальный отступ.

Значение: Начальный отступ.

**Returns:**
double
### getWordSpacing() {#getWordSpacing--}
```
public abstract double[] getWordSpacing()
```


Получает или задает интервал между словами.

Значение: Интервал между словами.

**Returns:**
double[]
### getZone() {#getZone--}
```
public abstract double getZone()
```


Получает или задает зону.

Значение: Зона.

**Returns:**
double
### isEqual(ITextParagraph paragraph) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract boolean isEqual(ITextParagraph paragraph)
```


Определяет, равен ли указанный абзац.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| paragraph | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Абзац. |

**Returns:**
boolean -  true  если указанный абзац равен; иначе,  false .
### setAutoHyphenate(boolean value) {#setAutoHyphenate-boolean-}
```
public abstract void setAutoHyphenate(boolean value)
```


Получает или задает значение, указывающее, включено ли [automatic hyphenate].

Значение:  true  если [automatic hyphenate]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAutoLeading(double value) {#setAutoLeading-double-}
```
public abstract void setAutoLeading(double value)
```


Получает или задает автоматический интерлиньяж.

Значение: Автоматический интерлиньяж.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setBurasagari(boolean value) {#setBurasagari-boolean-}
```
public abstract void setBurasagari(boolean value)
```


Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) burasagiri.

Значение:  true  если burasagiri; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setConsecutiveHyphens(int value) {#setConsecutiveHyphens-int-}
```
public abstract void setConsecutiveHyphens(int value)
```


Получает или задает последовательные дефисы.

Значение: Последовательные дефисы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEndIndent(double value) {#setEndIndent-double-}
```
public abstract void setEndIndent(double value)
```


Получает или задает отступ в конце.

Значение: Конечный отступ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setEveryLineComposer(boolean value) {#setEveryLineComposer-boolean-}
```
public abstract void setEveryLineComposer(boolean value)
```


Получает или задает значение, указывающее, включен ли [every line composer].

Значение:  true  если [every line composer]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFirstLineIndent(double value) {#setFirstLineIndent-double-}
```
public abstract void setFirstLineIndent(double value)
```


Получает или задает отступ первой строки.

Значение: Отступ первой строки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setGlyphSpacing(double[] value) {#setGlyphSpacing-double---}
```
public abstract void setGlyphSpacing(double[] value)
```


Получает или задает интервал между глифами.

Значение: Интервал между глифами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setHanging(boolean value) {#setHanging-boolean-}
```
public abstract void setHanging(boolean value)
```


Получает или задает значение, указывающее, является ли этот [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) висячим.

Значение:  true  если hanging; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setHyphenatedWordSize(int value) {#setHyphenatedWordSize-int-}
```
public abstract void setHyphenatedWordSize(int value)
```


Получает или задает размер переносимого слова.

Значение: Размер переносного слова.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Получает или задает выравнивание.

Значение: Выравнивание.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setKinsokuOrder(int value) {#setKinsokuOrder-int-}
```
public abstract void setKinsokuOrder(int value)
```


Получает или задает порядок кинсоку.

Значение: Порядок кинсоку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLeadingType(int value) {#setLeadingType-int-}
```
public abstract void setLeadingType(int value)
```


Получает или задает тип интерлиньяжа.

Значение: Тип межстрочного интервала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLetterSpacing(double[] value) {#setLetterSpacing-double---}
```
public abstract void setLetterSpacing(double[] value)
```


Получает или задает межбуквенный интервал.

Значение: Межбуквенный интервал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setPostHyphen(int value) {#setPostHyphen-int-}
```
public abstract void setPostHyphen(int value)
```


Получает или задает постдефис.

Значение: Постфикс дефиса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPreHyphen(int value) {#setPreHyphen-int-}
```
public abstract void setPreHyphen(int value)
```


Получает или задает преддефис.

Значение: Префикс дефиса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSpaceAfter(double value) {#setSpaceAfter-double-}
```
public abstract void setSpaceAfter(double value)
```


Получает или задает отступ после.

Значение: Пробел после.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setSpaceBefore(double value) {#setSpaceBefore-double-}
```
public abstract void setSpaceBefore(double value)
```


Получает или задает отступ перед.

Значение: Пробел перед.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setStartIndent(double value) {#setStartIndent-double-}
```
public abstract void setStartIndent(double value)
```


Получает или задает начальный отступ.

Значение: Начальный отступ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setWordSpacing(double[] value) {#setWordSpacing-double---}
```
public abstract void setWordSpacing(double[] value)
```


Получает или задает интервал между словами.

Значение: Интервал между словами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setZone(double value) {#setZone-double-}
```
public abstract void setZone(double value)
```


Получает или задает зону.

Значение: Зона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |


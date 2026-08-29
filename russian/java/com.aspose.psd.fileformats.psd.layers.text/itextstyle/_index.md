---
title: "ITextStyle"
second_title: "Aspose.PSD for Java API Справочник"
description: "Интерфейс для работы со стилем текста."
type: docs
weight: 14
url: /ru/java/com.aspose.psd.fileformats.psd.layers.text/itextstyle/
---
```
public interface ITextStyle
```

Интерфейс для работы со стилем текста.
## Методы

| Метод | Описание |
| --- | --- |
| [apply(ITextStyle style)](#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Применяет указанный стиль. |
| [getAutoKerning()](#getAutoKerning--) | Получает или задает автоматическое кернинг. |
| [getAutoLeading()](#getAutoLeading--) | Получает или задает значение, указывающее, включено ли [automatic leading]. |
| [getBaselineShift()](#getBaselineShift--) | Смещение базовой линии. |
| [getContextualAlternates()](#getContextualAlternates--) | Контекстные альтернативы, используемые для соединения букв вместе. |
| [getDiscretionaryLigatures()](#getDiscretionaryLigatures--) | Дискреционные лигатуры, используемые для соединения букв, особенно в курсивных шрифтах. |
| [getFauxBold()](#getFauxBold--) | Получает или задает, включён ли имитационный полужирный шрифт. |
| [getFauxItalic()](#getFauxItalic--) | Получает или задает, включён ли имитационный полужирный шрифт. |
| [getFillColor()](#getFillColor--) | Получает или задает цвет заливки. |
| [getFontBaseline()](#getFontBaseline--) | Базовая линия шрифта. |
| [getFontCaps()](#getFontCaps--) | Верхний регистр шрифта. |
| [getFontIndex()](#getFontIndex--) | Получает индекс шрифта. |
| [getFontName()](#getFontName--) | Получает или задает имя шрифта. |
| [getFontSize()](#getFontSize--) | Получает или задает размер шрифта. |
| [getFractions()](#getFractions--) | Символы дробей могут быть заменены специальным глифом. |
| [getHindiNumbers()](#getHindiNumbers--) | Получает или задает значение, указывающее, [hindi numbers]. |
| [getHorizontalScale()](#getHorizontalScale--) | Горизонтальный масштаб. |
| [getKerning()](#getKerning--) | Получает или задает кернинг. |
| [getLanguageIndex()](#getLanguageIndex--) | Получает индекс языка. |
| [getLeading()](#getLeading--) | Получает или задает межстрочный интервал. |
| [getStandardLigatures()](#getStandardLigatures--) | Стандартные контекстные лигатуры, используемые для соединения букв вместе. |
| [getStrikethrough()](#getStrikethrough--) | Получает или задает значение, указывающее, [strikethrough]. |
| [getStrokeColor()](#getStrokeColor--) | Получает или задает цвет обводки. |
| [getTracking()](#getTracking--) | Получает или задает трекинг. |
| [getUnderline()](#getUnderline--) | Получает или задает значение, указывающее, [underline]. |
| [getVerticalScale()](#getVerticalScale--) | Вертикальный масштаб. |
| [get_noBreak()](#get-noBreak--) | Получает ot задает значение без разрыва. |
| [isEqual(ITextStyle style)](#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-) | Определяет, равен ли указанный стиль. |
| [is_isStandardVerticalRomanAlignmentEnabled()](#is-isStandardVerticalRomanAlignmentEnabled--) | Получает или задает стандартное вертикальное римское выравнивание. |
| [setAutoKerning(int value)](#setAutoKerning-int-) | Получает или задает автоматическое кернинг. |
| [setAutoLeading(boolean value)](#setAutoLeading-boolean-) | Получает или задает значение, указывающее, включено ли [automatic leading]. |
| [setBaselineShift(double value)](#setBaselineShift-double-) | Смещение базовой линии. |
| [setContextualAlternates(boolean value)](#setContextualAlternates-boolean-) | Контекстные альтернативы, используемые для соединения букв вместе. |
| [setDiscretionaryLigatures(boolean value)](#setDiscretionaryLigatures-boolean-) | Дискреционные лигатуры, используемые для соединения букв, особенно в курсивных шрифтах. |
| [setFauxBold(boolean value)](#setFauxBold-boolean-) | Получает или задает, включён ли имитационный полужирный шрифт. |
| [setFauxItalic(boolean value)](#setFauxItalic-boolean-) | Получает или задает, включён ли имитационный полужирный шрифт. |
| [setFillColor(Color value)](#setFillColor-com.aspose.psd.Color-) | Получает или задает цвет заливки. |
| [setFontBaseline(int value)](#setFontBaseline-int-) | Базовая линия шрифта. |
| [setFontCaps(int value)](#setFontCaps-int-) | Верхний регистр шрифта. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Получает или задает имя шрифта. |
| [setFontSize(double value)](#setFontSize-double-) | Получает или задает размер шрифта. |
| [setFractions(boolean value)](#setFractions-boolean-) | Символы дробей могут быть заменены специальным глифом. |
| [setHindiNumbers(boolean value)](#setHindiNumbers-boolean-) | Получает или задает значение, указывающее, [hindi numbers]. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | Горизонтальный масштаб. |
| [setKerning(int value)](#setKerning-int-) | Получает или задает кернинг. |
| [setLeading(double value)](#setLeading-double-) | Получает или задает межстрочный интервал. |
| [setStandardLigatures(boolean value)](#setStandardLigatures-boolean-) | Стандартные контекстные лигатуры, используемые для соединения букв вместе. |
| [setStrikethrough(boolean value)](#setStrikethrough-boolean-) | Получает или задает значение, указывающее, [strikethrough]. |
| [setStrokeColor(Color value)](#setStrokeColor-com.aspose.psd.Color-) | Получает или задает цвет обводки. |
| [setTracking(int value)](#setTracking-int-) | Получает или задает трекинг. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Получает или задает значение, указывающее, [underline]. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | Вертикальный масштаб. |
| [set_isStandardVerticalRomanAlignmentEnabled(boolean value)](#set-isStandardVerticalRomanAlignmentEnabled-boolean-) | Получает или задает стандартное вертикальное римское выравнивание. |
| [set_noBreak(boolean value)](#set-noBreak-boolean-) | Получает ot задает значение без разрыва. |
### apply(ITextStyle style) {#apply-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract void apply(ITextStyle style)
```


Применяет указанный стиль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Стиль. |

### getAutoKerning() {#getAutoKerning--}
```
public abstract int getAutoKerning()
```


Получает или задает автоматическое кернинг.

Value: Автоматическое кернинг между двумя символами.

**Returns:**
int
### getAutoLeading() {#getAutoLeading--}
```
public abstract boolean getAutoLeading()
```


Получает или задает значение, указывающее, включено ли [automatic leading].

Value:  true  если [automatic leading]; иначе,  false .

**Returns:**
boolean
### getBaselineShift() {#getBaselineShift--}
```
public abstract double getBaselineShift()
```


Смещение базовой линии.

**Returns:**
double
### getContextualAlternates() {#getContextualAlternates--}
```
public abstract boolean getContextualAlternates()
```


Контекстные альтернативы, используемые для соединения букв вместе.

**Returns:**
boolean
### getDiscretionaryLigatures() {#getDiscretionaryLigatures--}
```
public abstract boolean getDiscretionaryLigatures()
```


Дискреционные лигатуры, используемые для соединения букв, особенно в курсивных шрифтах.

**Returns:**
boolean
### getFauxBold() {#getFauxBold--}
```
public abstract boolean getFauxBold()
```


Получает или задает, включён ли имитационный полужирный шрифт.

**Returns:**
boolean
### getFauxItalic() {#getFauxItalic--}
```
public abstract boolean getFauxItalic()
```


Получает или задает, включён ли имитационный полужирный шрифт.

**Returns:**
boolean
### getFillColor() {#getFillColor--}
```
public abstract Color getFillColor()
```


Получает или задает цвет заливки.

Value: Цвет заливки.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFontBaseline() {#getFontBaseline--}
```
public abstract int getFontBaseline()
```


Базовая линия шрифта.

**Returns:**
int
### getFontCaps() {#getFontCaps--}
```
public abstract int getFontCaps()
```


Верхний регистр шрифта.

**Returns:**
int
### getFontIndex() {#getFontIndex--}
```
public abstract int getFontIndex()
```


Получает индекс шрифта.

Value: Шрифт.

**Returns:**
int
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Получает или задает имя шрифта.

**Returns:**
java.lang.String
### getFontSize() {#getFontSize--}
```
public abstract double getFontSize()
```


Получает или задает размер шрифта.

Value: Размер шрифта.

**Returns:**
double
### getFractions() {#getFractions--}
```
public abstract boolean getFractions()
```


Символы дробей могут быть заменены специальным глифом.

**Returns:**
boolean
### getHindiNumbers() {#getHindiNumbers--}
```
public abstract boolean getHindiNumbers()
```


Получает или задает значение, указывающее, [hindi numbers].

Value:  true  если [hindi numbers]; иначе,  false .

**Returns:**
boolean
### getHorizontalScale() {#getHorizontalScale--}
```
public abstract double getHorizontalScale()
```


Горизонтальный масштаб.

**Returns:**
double
### getKerning() {#getKerning--}
```
public abstract int getKerning()
```


Получает или задает кернинг.

Value: Кернинг между двумя символами.

**Returns:**
int
### getLanguageIndex() {#getLanguageIndex--}
```
public abstract int getLanguageIndex()
```


Получает индекс языка.

**Returns:**
int
### getLeading() {#getLeading--}
```
public abstract double getLeading()
```


Получает или задает межстрочный интервал.

Value: Межстрочный интервал.

**Returns:**
double
### getStandardLigatures() {#getStandardLigatures--}
```
public abstract boolean getStandardLigatures()
```


Стандартные контекстные лигатуры, используемые для соединения букв вместе.

**Returns:**
boolean
### getStrikethrough() {#getStrikethrough--}
```
public abstract boolean getStrikethrough()
```


Получает или задает значение, указывающее, [strikethrough].

**Returns:**
boolean
### getStrokeColor() {#getStrokeColor--}
```
public abstract Color getStrokeColor()
```


Получает или задает цвет обводки.

Value: Цвет обводки.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTracking() {#getTracking--}
```
public abstract int getTracking()
```


Получает или задает трекинг.

Value: Трекинг.

**Returns:**
int
### getUnderline() {#getUnderline--}
```
public abstract boolean getUnderline()
```


Получает или задает значение, указывающее, [underline].

**Returns:**
boolean
### getVerticalScale() {#getVerticalScale--}
```
public abstract double getVerticalScale()
```


Вертикальный масштаб.

**Returns:**
double
### get_noBreak() {#get-noBreak--}
```
public abstract boolean get_noBreak()
```


Получает ot задает значение без разрыва.

**Returns:**
boolean
### isEqual(ITextStyle style) {#isEqual-com.aspose.psd.fileformats.psd.layers.text.ITextStyle-}
```
public abstract boolean isEqual(ITextStyle style)
```


Определяет, равен ли указанный стиль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| style | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Стиль. |

**Returns:**
boolean -  true  если указанный стиль равен; иначе,  false .
### is_isStandardVerticalRomanAlignmentEnabled() {#is-isStandardVerticalRomanAlignmentEnabled--}
```
public abstract boolean is_isStandardVerticalRomanAlignmentEnabled()
```


Получает или задает стандартное вертикальное выравнивание Roman. Это основано на значении ресурса BaselineDirection и применяется только когда ориентация текста — [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Returns:**
boolean
### setAutoKerning(int value) {#setAutoKerning-int-}
```
public abstract void setAutoKerning(int value)
```


Получает или задает автоматическое кернинг.

Value: Автоматическое кернинг между двумя символами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setAutoLeading(boolean value) {#setAutoLeading-boolean-}
```
public abstract void setAutoLeading(boolean value)
```


Получает или задает значение, указывающее, включено ли [automatic leading].

Value:  true  если [automatic leading]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBaselineShift(double value) {#setBaselineShift-double-}
```
public abstract void setBaselineShift(double value)
```


Смещение базовой линии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setContextualAlternates(boolean value) {#setContextualAlternates-boolean-}
```
public abstract void setContextualAlternates(boolean value)
```


Контекстные альтернативы, используемые для соединения букв вместе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setDiscretionaryLigatures(boolean value) {#setDiscretionaryLigatures-boolean-}
```
public abstract void setDiscretionaryLigatures(boolean value)
```


Дискреционные лигатуры, используемые для соединения букв, особенно в курсивных шрифтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFauxBold(boolean value) {#setFauxBold-boolean-}
```
public abstract void setFauxBold(boolean value)
```


Получает или задает, включён ли имитационный полужирный шрифт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFauxItalic(boolean value) {#setFauxItalic-boolean-}
```
public abstract void setFauxItalic(boolean value)
```


Получает или задает, включён ли имитационный полужирный шрифт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFillColor(Color value) {#setFillColor-com.aspose.psd.Color-}
```
public abstract void setFillColor(Color value)
```


Получает или задает цвет заливки.

Value: Цвет заливки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setFontBaseline(int value) {#setFontBaseline-int-}
```
public abstract void setFontBaseline(int value)
```


Базовая линия шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFontCaps(int value) {#setFontCaps-int-}
```
public abstract void setFontCaps(int value)
```


Верхний регистр шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public abstract void setFontName(String value)
```


Получает или задает имя шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFontSize(double value) {#setFontSize-double-}
```
public abstract void setFontSize(double value)
```


Получает или задает размер шрифта.

Value: Размер шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setFractions(boolean value) {#setFractions-boolean-}
```
public abstract void setFractions(boolean value)
```


Символы дробей могут быть заменены специальным глифом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setHindiNumbers(boolean value) {#setHindiNumbers-boolean-}
```
public abstract void setHindiNumbers(boolean value)
```


Получает или задает значение, указывающее, [hindi numbers].

Value:  true  если [hindi numbers]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public abstract void setHorizontalScale(double value)
```


Горизонтальный масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setKerning(int value) {#setKerning-int-}
```
public abstract void setKerning(int value)
```


Получает или задает кернинг.

Value: Кернинг между двумя символами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLeading(double value) {#setLeading-double-}
```
public abstract void setLeading(double value)
```


Получает или задает межстрочный интервал.

Value: Межстрочный интервал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setStandardLigatures(boolean value) {#setStandardLigatures-boolean-}
```
public abstract void setStandardLigatures(boolean value)
```


Стандартные контекстные лигатуры, используемые для соединения букв вместе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setStrikethrough(boolean value) {#setStrikethrough-boolean-}
```
public abstract void setStrikethrough(boolean value)
```


Получает или задает значение, указывающее, [strikethrough].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setStrokeColor(Color value) {#setStrokeColor-com.aspose.psd.Color-}
```
public abstract void setStrokeColor(Color value)
```


Получает или задает цвет обводки.

Value: Цвет обводки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setTracking(int value) {#setTracking-int-}
```
public abstract void setTracking(int value)
```


Получает или задает трекинг.

Value: Трекинг.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public abstract void setUnderline(boolean value)
```


Получает или задает значение, указывающее, [underline].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public abstract void setVerticalScale(double value)
```


Вертикальный масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### set_isStandardVerticalRomanAlignmentEnabled(boolean value) {#set-isStandardVerticalRomanAlignmentEnabled-boolean-}
```
public abstract void set_isStandardVerticalRomanAlignmentEnabled(boolean value)
```


Получает или задает стандартное вертикальное выравнивание Roman. Это основано на значении ресурса BaselineDirection и применяется только когда ориентация текста — [TextOrientation.Vertical](../../com.aspose.psd.fileformats.psd.layers.text.rendering/textorientation\#Vertical).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### set_noBreak(boolean value) {#set-noBreak-boolean-}
```
public abstract void set_noBreak(boolean value)
```


Получает ot задает значение без разрыва.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |


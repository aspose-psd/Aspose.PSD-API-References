---
title: "Шрифт"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет конкретный формат текста, включая гарнитуру, размер и атрибуты стиля."
type: docs
weight: 46
url: /ru/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Определяет конкретный формат текста, включая гарнитуру, размер и атрибуты стиля. Этот класс не может быть унаследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Инициализирует новый  com.aspose.psd.Font , использующий указанный существующий  com.aspose.psd.Font  и перечисление  com.aspose.psd.FontStyle . |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Инициализирует новый  com.aspose.psd.Font  с указанным размером. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Инициализирует новый  com.aspose.psd.Font  с указанным размером и стилем. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Инициализирует новый  com.aspose.psd.Font  с указанным размером, стилем, единицей измерения и набором символов. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Инициализирует новый  com.aspose.psd.Font  с указанным размером, стилем и единицей измерения. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone()](#deepClone--) | Создаёт точную глубокую копию этого  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, является ли указанный объект  com.aspose.psd.Font  и имеет ли те же значения свойств, что и этот  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Возвращает значение, указывающее, является ли этот  Font  полужирным. |
| [getCharacterSet()](#getCharacterSet--) | Возвращает байтовое значение, которое указывает набор символов, используемый этим  Font . |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Возвращает значение, указывающее, является ли этот  Font  курсивным. |
| [getName()](#getName--) | Возвращает название гарнитуры этого  Font . |
| [getSize()](#getSize--) | Возвращает размер em этого  Font , измеренный в единицах, указанных свойством  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Возвращает значение, указывающее, содержит ли этот  Font  горизонтальную линию через шрифт. |
| [getStyle()](#getStyle--) | Возвращает информацию о стиле этого  Font . |
| [getUnderline()](#getUnderline--) | Возвращает значение, указывающее, подчёркнут ли этот  Font . |
| [getUnit()](#getUnit--) | Возвращает единицу измерения этого  Font . |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этого  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Инициализирует новый  com.aspose.psd.Font  с указанным размером и единицей измерения. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает человекочитаемое строковое представление этого  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Инициализирует новый  com.aspose.psd.Font , использующий указанный существующий  com.aspose.psd.Font  и перечисление  com.aspose.psd.FontStyle .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Существующий  com.aspose.psd.Font , из которого создаётся новый  com.aspose.psd.Font . |
| newStyle | int | Тип  com.aspose.psd.FontStyle , который следует применить к новому  com.aspose.psd.Font . Несколько значений перечисления  com.aspose.psd.FontStyle  могут быть объединены оператором OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Инициализирует новый  com.aspose.psd.Font  с указанным размером. Набор символов установлен в  F:Aspose.Imaging.CharacterSet.Default , графическая единица измерения —  F:Aspose.Imaging.GraphicsUnit.Point , стиль шрифта —  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени  com.aspose.psd.Font . |
| emSize | float | Размер em в пунктах нового шрифта. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Инициализирует новый  com.aspose.psd.Font , используя указанный размер и стиль. Набор символов устанавливается в  F:Aspose.Imaging.CharacterSet.Default , графическая единица — в  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени  com.aspose.psd.Font . |
| emSize | float | Размер em в пунктах нового шрифта. |
| style | int | Стиль  com.aspose.psd.FontStyle  нового шрифта. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Инициализирует новый  com.aspose.psd.Font  с указанным размером, стилем, единицей измерения и набором символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени  com.aspose.psd.Font . |
| emSize | float | Размер em нового шрифта в единицах, указанных параметром  unit . |
| style | int | Стиль  com.aspose.psd.FontStyle  нового шрифта. |
| unit | int | Графическая единица  com.aspose.psd.GraphicsUnit  нового шрифта. |
| characterSet | int | Набор символов, используемый для этого шрифта. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Инициализирует новый  com.aspose.psd.Font  с указанным размером, стилем и единицей измерения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени  com.aspose.psd.Font . |
| emSize | float | Размер em нового шрифта в единицах, указанных параметром  unit . |
| style | int | Стиль  com.aspose.psd.FontStyle  нового шрифта. |
| unit | int | Графическая единица  com.aspose.psd.GraphicsUnit  нового шрифта. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Создаёт точную глубокую копию этого  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, является ли указанный объект  com.aspose.psd.Font  и имеет ли те же значения свойств, что и этот  com.aspose.psd.Font .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для тестирования. |

**Returns:**
boolean — true, если параметр  obj  является  com.aspose.psd.Font  и имеет те же значения свойств, что и этот  com.aspose.psd.Font ; иначе — false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Возвращает значение, указывающее, является ли этот  Font  полужирным.

**Returns:**
boolean — true, если этот  Font  полужирный; иначе — false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Возвращает байтовое значение, которое указывает набор символов, используемый этим  Font .

**Returns:**
int — набор символов, используемый этим  Font .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Возвращает значение, указывающее, является ли этот  Font  курсивным.

**Returns:**
boolean — true, если этот  Font  курсивный; иначе — false.
### getName() {#getName--}
```
public String getName()
```


Возвращает название гарнитуры этого  Font .

**Returns:**
java.lang.String — строковое представление названия гарнитуры этого  Font .
### getSize() {#getSize--}
```
public float getSize()
```


Возвращает размер em этого  Font , измеренный в единицах, указанных свойством  P:Aspose.Imaging.Font.Unit .

**Returns:**
float — размер em этого  Font .
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Возвращает значение, указывающее, содержит ли этот  Font  горизонтальную линию через шрифт.

**Returns:**
boolean — true, если у этого  Font  есть горизонтальная черта; иначе — false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Возвращает информацию о стиле этого  Font .

**Returns:**
int — перечисление  FontStyle , содержащее информацию о стиле этого  Font .
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Возвращает значение, указывающее, подчёркнут ли этот  Font .

**Returns:**
boolean — true, если этот  Font  подчёркнут; иначе — false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Возвращает единицу измерения этого  Font .

**Returns:**
int —  GraphicsUnit , представляющий единицу измерения для этого  Font .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этого  com.aspose.psd.Font .

**Returns:**
int — хеш‑код этого  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Инициализирует новый  com.aspose.psd.Font , используя указанный размер и единицу измерения. Набор символов устанавливается в  F:Aspose.Imaging.CharacterSet.Default , стиль — в  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Строковое представление имени  com.aspose.psd.Font . |
| emSize | float | Размер em нового шрифта в единицах, указанных параметром  unit . |
| unit | int | Графическая единица  com.aspose.psd.GraphicsUnit  нового шрифта. |

**Returns:**
[Font](../../com.aspose.psd/font)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Возвращает человекочитаемое строковое представление этого  com.aspose.psd.Font .

**Returns:**
java.lang.String — строка, представляющая этот  com.aspose.psd.Font .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


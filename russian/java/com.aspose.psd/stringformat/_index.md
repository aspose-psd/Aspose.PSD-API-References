---
title: "StringFormat"
second_title: "Aspose.PSD for Java API Справочник"
description: "Инкапсулирует информацию о размещении текста, такую как выравнивание, ориентацию и табуляцию, а также манипуляции отображением, такие как вставка многоточия и замена национальных цифр, и функции OpenType."
type: docs
weight: 106
url: /ru/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Инкапсулирует информацию о размещении текста (например, выравнивание, ориентацию и табуляцию), манипуляции отображением (например, вставка многоточия и замена национальных цифр) и функции OpenType. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StringFormat()](#StringFormat--) | Инициализирует новый объект  com.aspose.psd.StringFormat  . |
| [StringFormat(int options)](#StringFormat-int-) | Инициализирует новый объект  com.aspose.psd.StringFormat  с указанным перечислением  com.aspose.psd.StringFormatFlags  и языком. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Инициализирует новый объект  com.aspose.psd.StringFormat  из указанного существующего объекта  com.aspose.psd.StringFormat . |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Создаёт глубокую копию этого объекта  com.aspose.psd.StringFormat . |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Получает информацию о выравнивании текста по вертикали. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Получает язык, используемый при замене локальных цифр на западные. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Получает метод, используемый для замены цифр. |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Получает количество пробелов между началом строки текста и первой табуляцией. |
| [getFormatFlags()](#getFormatFlags--) | Получает перечисление  com.aspose.psd.StringFormatFlags , содержащее информацию о форматировании. |
| [getGenericDefault()](#getGenericDefault--) | Получает общий объект по умолчанию  com.aspose.psd.StringFormat . |
| [getGenericTypographic()](#getGenericTypographic--) | Получает общий типографический объект  com.aspose.psd.StringFormat . |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Получает объект  com.aspose.psd.HotkeyPrefix  для этого объекта  com.aspose.psd.StringFormat . |
| [getLineAlignment()](#getLineAlignment--) | Получает выравнивание строки по горизонтали. |
| [getTabStops()](#getTabStops--) | Получает массив расстояний между табуляциями в единицах, указанных свойством  P:Aspose.Imaging.getGraphics().PageUnit . |
| [getTrimming()](#getTrimming--) | Получает перечисление  com.aspose.psd.StringTrimming  для этого объекта  com.aspose.psd.StringFormat . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Устанавливает информацию о выравнивании текста по вертикали. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Устанавливает язык, используемый при замене локальных цифр на западные. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Устанавливает метод, используемый для замены цифр. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Устанавливает перечисление  com.aspose.psd.StringFormatFlags , содержащие информацию о форматировании. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Устанавливает объект  com.aspose.psd.HotkeyPrefix  для этого объекта  com.aspose.psd.StringFormat . |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Устанавливает выравнивание строк по горизонтали. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Устанавливает табуляцию для этого объекта  com.aspose.psd.StringFormat . |
| [setTrimming(int value)](#setTrimming-int-) | Устанавливает перечисление  com.aspose.psd.StringTrimming  для этого объекта  com.aspose.psd.StringFormat . |
| [toString()](#toString--) | Преобразует объект  com.aspose.psd.StringFormat  в читаемую строку. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Инициализирует новый объект  com.aspose.psd.StringFormat  .

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Инициализирует новый объект  com.aspose.psd.StringFormat  с указанным перечислением  com.aspose.psd.StringFormatFlags  и языком.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| опции | int | Перечисление  com.aspose.psd.StringFormatFlags  для нового объекта  com.aspose.psd.StringFormat . |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Инициализирует новый объект  com.aspose.psd.StringFormat  из указанного существующего объекта  com.aspose.psd.StringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Объект  com.aspose.psd.StringFormat , из которого инициализируется новый объект  com.aspose.psd.StringFormat . |

### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Создаёт глубокую копию этого объекта  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Получает информацию о выравнивании текста по вертикали.

**Returns:**
int — перечисление  com.aspose.psd.StringAlignment , определяющее информацию о выравнивании текста.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Получает язык, используемый при замене локальных цифр на западные.

**Returns:**
int — Идентификатор языка National Language Support (NLS), определяющий язык, который будет использоваться при замене локальных цифр на западные. Вы можете передать свойство  P:System.Globalization.CultureInfo.LCID  объекта  System.Globalization.CultureInfo  в качестве NLS‑идентификатора языка. Например, предположим, что вы создаёте объект  System.Globalization.CultureInfo , передавая строку "ar-EG" в конструктор  System.Globalization.CultureInfo . Если вы передадите свойство  P:System.Globalization.CultureInfo.LCID  этого объекта  System.Globalization.CultureInfo  вместе с  com.aspose.psd.StringDigitSubstitute.Traditional  в метод  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) , то арабско‑индианские цифры будут заменены на западные при отображении.

Сеттер введён для устаревшего метода setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Получает метод, используемый для замены цифр.

**Returns:**
int — значение перечисления  com.aspose.psd.StringDigitSubstitute , определяющее способ замены символов в строке, которые не могут быть отображены, потому что текущий шрифт их не поддерживает.

Сеттер введён для устаревшего метода SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Получает количество пробелов между началом строки текста и первой табуляцией.

**Returns:**
float — первое смещение табуляции.

Свойство введено для удалённого метода GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Получает перечисление  com.aspose.psd.StringFormatFlags , содержащее информацию о форматировании.

**Returns:**
int — перечисление  com.aspose.psd.StringFormatFlags , содержащее информацию о форматировании.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Получает общий объект по умолчанию  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Получает общий типографический объект  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Получает объект  com.aspose.psd.HotkeyPrefix  для этого объекта  com.aspose.psd.StringFormat .

**Returns:**
int — объект  com.aspose.psd.HotkeyPrefix  для этого объекта  com.aspose.psd.StringFormat , по умолчанию  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Получает выравнивание строки по горизонтали.

**Returns:**
int — перечисление  com.aspose.psd.StringAlignment , представляющее выравнивание строк.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Получает массив расстояний между табуляциями в единицах, указанных свойством  P:Aspose.Imaging.getGraphics().PageUnit .

**Returns:**
float[] — табуляции.

Свойство введено для удалённого метода GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Получает перечисление  com.aspose.psd.StringTrimming  для этого объекта  com.aspose.psd.StringFormat .

**Returns:**
int — перечисление  com.aspose.psd.StringTrimming , указывающее, как обрезается текст, нарисованный этим объектом  com.aspose.psd.StringFormat , когда он выходит за пределы прямоугольника макета.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Устанавливает информацию о выравнивании текста по вертикали.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Перечисление  com.aspose.psd.StringAlignment , определяющее информацию о выравнивании текста. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Устанавливает язык, используемый при замене локальных цифр на западные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Идентификатор языка National Language Support (NLS), определяющий язык, который будет использоваться при замене локальных цифр на западные. Вы можете передать свойство  P:System.Globalization.CultureInfo.LCID  объекта  System.Globalization.CultureInfo  в качестве NLS‑идентификатора языка. Например, предположим, что вы создаёте объект  System.Globalization.CultureInfo , передавая строку "ar-EG" в конструктор  System.Globalization.CultureInfo . Если вы передадите свойство  P:System.Globalization.CultureInfo.LCID  этого объекта  System.Globalization.CultureInfo  вместе с  com.aspose.psd.StringDigitSubstitute.Traditional  в метод  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) , то арабско‑индианские цифры будут заменены на западные при отображении. |

Сеттер введён для устаревшего метода SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Устанавливает метод, используемый для замены цифр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Значение перечисления com.aspose.psd.StringDigitSubstitute, которое указывает, как заменять символы в строке, которые не могут быть отображены, потому что текущий шрифт их не поддерживает. |

Сеттер введён для устаревшего метода SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Устанавливает перечисление  com.aspose.psd.StringFormatFlags , содержащие информацию о форматировании.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Перечисление com.aspose.psd.StringFormatFlags, содержащее информацию о форматировании. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Устанавливает объект  com.aspose.psd.HotkeyPrefix  для этого объекта  com.aspose.psd.StringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Объект com.aspose.psd.HotkeyPrefix для данного объекта com.aspose.psd.StringFormat, по умолчанию — F:Aspose.Imaging.HotkeyPrefix.None. |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Устанавливает выравнивание строк по горизонтали.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Перечисление com.aspose.psd.StringAlignment, представляющее выравнивание строки. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Устанавливает табуляцию для этого объекта  com.aspose.psd.StringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstTabOffset | float | Количество пробелов между началом строки текста и первой табуляцией. |
| tabStops | float[] | Массив расстояний между табуляциями в единицах, указанных свойством com.aspose.psd.Graphics.PageUnit. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Устанавливает перечисление  com.aspose.psd.StringTrimming  для этого объекта  com.aspose.psd.StringFormat .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Перечисление com.aspose.psd.StringTrimming, указывающее, как обрезается текст, отрисованный с помощью объекта com.aspose.psd.StringFormat, когда он превышает границы прямоугольника разметки. |

### toString() {#toString--}
```
public String toString()
```


Преобразует объект  com.aspose.psd.StringFormat  в читаемую строку.

**Returns:**
java.lang.String — строковое представление объекта com.aspose.psd.StringFormat.
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


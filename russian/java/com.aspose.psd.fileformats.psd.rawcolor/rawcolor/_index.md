---
title: "RawColor"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс Raw Color помогает хранить цвета с любым количеством каналов, любым режимом цвета и любой глубиной битов. Обратите внимание, что некоторые внутренние классы могут иметь проблемы с преобразованием RawColor в его родной формат, поэтому, если API предоставляет вам цвет CMYK, надёжнее использовать предоставленный формат."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Класс Raw Color помогает хранить цвета с любым количеством каналов, любым режимом цвета и любой глубиной битов. Обратите внимание, что некоторые внутренние классы могут иметь проблемы с преобразованием RawColor в его родной формат, поэтому, если API предоставляет вам цвет CMYK, надёжнее использовать предоставленный формат. Кроме того, могут быть случаи, когда Raw Color может быть преобразован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Инициализирует новый экземпляр класса [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Инициализирует новый экземпляр класса [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) из формата пиксельных данных с использованием предопределённых режимов цвета. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект этому экземпляру. |
| [getAsInt()](#getAsInt--) | Получает цвет как int, если это возможно. |
| [getAsLong()](#getAsLong--) | Получает цвет как long, если это возможно. |
| [getBitDepth()](#getBitDepth--) | Получает глубину битов Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Режим, которому следует цвет. |
| [getColorModeName()](#getColorModeName--) | Получает название режима цвета. |
| [getComponents()](#getComponents--) | Получает компоненты цвета. |
| [hashCode()](#hashCode--) | Получает хеш-код текущего объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Реализует оператор ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Реализует оператор !=. |
| [setAsInt(int value)](#setAsInt-int-) | Устанавливает данные во все каналы из аргумента типа int, если это возможно. |
| [setAsLong(long value)](#setAsLong-long-) | Устанавливает данные во все каналы из аргумента типа int, если это возможно. |
| [setColorMode(short value)](#setColorMode-short-) | Режим, которому следует цвет. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Инициализирует новый экземпляр класса [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | Пользовательские компоненты цвета. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Инициализирует новый экземпляр класса [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) из формата пиксельных данных с использованием предопределённых режимов цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Формат данных пикселей. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с этим экземпляром. |

**Returns:**
boolean — true, если указанный объект равен этому экземпляру; иначе — false.
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Получает цвет как int, если это возможно.

**Returns:**
int — данные каналов, хранящиеся в Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Получает цвет как long, если это возможно.

**Returns:**
long — данные каналов, хранящиеся в Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Получает глубину цвета Raw Color. Например, для цвета ARGB с 8 битами на канал/компонент глубина составляет 32 бита. Полная глубина ARGB цвета с 16 битами на канал/компонент составляет 64. Глубина цвета складывается из суммы глубин битов каналов. Это возможно, если разные каналы имеют разную глубину битов.

**Returns:**
int — Сумма глубин битов всех каналов
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Режим, которому следует цвет.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Получает название режима цвета. Название режима цвета формируется из названий каналов/компонентов.

**Returns:**
java.lang.String — Строка с названием режима цвета
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Получает компоненты цвета. Каждый компонент представляет отдельный канал, и если вы используете непопулярную цветовую схему, лучше работать с каждым каналом отдельно.

Значение: Компоненты цвета

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш-код текущего объекта.

**Returns:**
int — Хеш-код.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


Реализует оператор ==.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Первый RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Второй RawColor. |

**Returns:**
boolean — Результат операции.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Реализует оператор !=.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Первый RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Второй RawColor. |

**Returns:**
boolean — Результат операции.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Устанавливает данные во все каналы из аргумента типа int, если это возможно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Целочисленное значение, содержащее данные компонента |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Устанавливает данные во все каналы из аргумента типа int, если это возможно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Целочисленное значение, содержащее данные компонента |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Режим, которому следует цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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


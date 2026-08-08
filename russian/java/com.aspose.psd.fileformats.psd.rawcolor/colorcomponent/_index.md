---
title: "ColorComponent"
second_title: "Aspose.PSD for Java API Справочник"
description: "Компонент цвета — это абстракция над значением канала и значением канала."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Компонент цвета — это абстракция над значением канала. Любой цвет состоит из массива ColorComponent.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Инициализирует новый экземпляр класса [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Получает глубину битов компонента цвета/канала |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Получает описание компонента цвета |
| [getFullName()](#getFullName--) | Получает полное название компонента цвета, включающее имя и описание, разделённые пробелом |
| [getName()](#getName--) | Получает название компонента цвета. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Получает разрешённые полные названия. |
| [getValue()](#getValue--) | Получает или задает значение. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Получает или задает значение. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Инициализирует новый экземпляр класса [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent). Пожалуйста, проверьте

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bitDepth | byte | Битовая глубина. |
| fullName | java.lang.String | Полное название. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Получает глубину битов компонента цвета/канала

Значение: Глубина битов.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Получает описание компонента цвета

Значение: Описание.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Получает полное название компонента цвета, включающее имя и описание, разделённые пробелом

Значение: Полное название.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Получает название компонента цвета.

Значение: имя.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Получает разрешённые полные названия.

Значение: разрешённые полные имена.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Получает или задаёт значение. Обратите внимание, если вы попытаетесь установить значение, превышающее возможное, хранимое при текущей глубине цвета, вы получите исключение.

Значение: Значение.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Получает или задаёт значение. Обратите внимание, если вы попытаетесь установить значение, превышающее возможное, хранимое при текущей глубине цвета, вы получите исключение.

Значение: Значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

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


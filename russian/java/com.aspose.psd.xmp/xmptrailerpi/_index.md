---
title: "XmpTrailerPi"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет инструкцию обработки трейлера XMP."
type: docs
weight: 22
url: /ru/java/com.aspose.psd.xmp/xmptrailerpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Представляет инструкцию обработки трейлера XMP.

Часть end="w" или end="r" должна использоваться процессорами сканирования пакетов для определения, может ли XMP быть изменён на месте.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Инициализирует новый экземпляр класса XmpTrailerPi. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Инициализирует новый экземпляр класса XmpTrailerPi. |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный  System.Object , этому экземпляру. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Преобразует значение xmp в представление xml. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.psd.xmp.XmpTrailerPi-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [isWritable()](#isWritable--) | Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWritable(boolean value)](#setWritable-boolean-) | Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Инициализирует новый экземпляр класса XmpTrailerPi.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isWritable | boolean | Указывает, доступен ли трейлер для записи. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Инициализирует новый экземпляр класса XmpTrailerPi.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpTrailerPi deepClone_internalized()
```


Клонирует этот экземпляр.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный  System.Object , этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  System.Object  для сравнения с этим экземпляром. |

**Returns:**
boolean -  true  если указанный  System.Object  равен этому экземпляру; иначе,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение xmp в представление xml.

**Returns:**
java.lang.String - Возвращает XML-представление XMP.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.psd.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру  other ; иначе, false.
### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи.

Значение: true, если этот экземпляр доступен для записи; иначе false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Получает или задаёт значение, указывающее, доступен ли этот экземпляр для записи.

Значение: true, если этот экземпляр доступен для записи; иначе false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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


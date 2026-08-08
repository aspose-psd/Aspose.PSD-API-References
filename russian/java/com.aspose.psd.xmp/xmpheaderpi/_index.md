---
title: "XmpHeaderPi"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет инструкцию обработки заголовка XMP."
type: docs
weight: 16
url: /ru/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Представляет инструкцию обработки заголовка XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Инициализирует новый экземпляр класса  XmpHeaderPi  . |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Инициализирует новый экземпляр класса  XmpHeaderPi  . |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный  System.Object , этому экземпляру. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | Представляет GUID заголовка. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в представление XML. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | Представляет GUID заголовка. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Инициализирует новый экземпляр класса  XmpHeaderPi  .

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Инициализирует новый экземпляр класса  XmpHeaderPi  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| guid | java.lang.String | Уникальный идентификатор. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


Клонирует этот экземпляр.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
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
### getGuid() {#getGuid--}
```
public String getGuid()
```


Представляет GUID заголовка.

Текст заголовка PI содержит GUID, что делает его маловероятным для случайного появления в потоке данных.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение XMP в представление XML.

**Returns:**
java.lang.String - Возвращает значение XMP, преобразованное в представление XML.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру  other ; иначе, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Представляет GUID заголовка.

Текст заголовка PI содержит GUID, что делает его маловероятным для случайного появления в потоке данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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


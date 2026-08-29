---
title: "XmpDate"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет дату в пакете XMP."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Представляет дату в пакете XMP.

Значение даты и времени представляется с использованием подмножества форматов, определённых в «Date and Time Formats»: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Инициализирует новый экземпляр класса  XmpDate . |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Инициализирует новый экземпляр класса  XmpDate . |
## Поля

| Поле | Описание |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | Строка формата ISO 8601 (roundtrip). |
## Методы

| Метод | Описание |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Получает строку формата для текущего значения. |
| [getValue()](#getValue--) | Получает или задает значение даты. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Возвращает строковое значение в формате XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Получает или задает значение даты. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Инициализирует новый экземпляр класса  XmpDate .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dateTime | java.util.Date | Значение даты и времени, представленное с использованием подмножества формата ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Инициализирует новый экземпляр класса  XmpDate .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dateString | java.lang.String | Строковое представление даты. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


Строка формата ISO 8601 (roundtrip).

Смотрите подробнее: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFormat() {#getFormat--}
```
public String getFormat()
```


Получает строку формата для текущего значения.

Значение: Строка формата для текущего значения.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Получает или задает значение даты.

Значение: Значение даты.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Возвращает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Получает или задает значение даты.

Значение: Значение даты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date |  |

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


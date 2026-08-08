---
title: "XmpMeta"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет xmpmeta."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Представляет xmpmeta. Необязательно. Цель этого элемента — идентифицировать XMP‑метаданные в общем XML‑тексте, который может содержать другие не‑XMP использования RDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Инициализирует новый экземпляр класса  XmpMeta  . |
| [XmpMeta()](#XmpMeta--) | Инициализирует новый экземпляр класса  XmpMeta  . |
## Методы

| Метод | Описание |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Добавляет атрибут. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Назначает указанный элемент XMP текущему. |
| [clearAttributes()](#clearAttributes--) | Удаляет все атрибуты. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [equals(Object other)](#equals-java.lang.Object-) | Определяет, равен ли указанный  System.Object , этому экземпляру. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Получает или задает версию набора инструментов Adobe Xmp. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Получает атрибут. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в представление XML. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Получает или задает версию набора инструментов Adobe Xmp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Инициализирует новый экземпляр класса  XmpMeta  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Версия набора инструментов Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Инициализирует новый экземпляр класса  XmpMeta  .

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Добавляет атрибут.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| attribute | java.lang.String | Атрибут. |
| значение | java.lang.String | Значение. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Назначает указанный элемент XMP текущему.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Элемент XMP. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Удаляет все атрибуты.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Клонирует этот экземпляр.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Определяет, равен ли указанный  System.Object , этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | java.lang.Object | Объект  System.Object  для сравнения с этим экземпляром. |

**Returns:**
boolean -  true  если указанный  System.Object  равен этому экземпляру; иначе,  false .
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Получает или задает версию набора инструментов Adobe Xmp.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Получает атрибут.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| attribute | java.lang.String | Атрибут. |

**Returns:**
java.lang.String - Возвращает атрибут для указанного имени атрибута.
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
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Объект для сравнения с этим объектом. |

**Returns:**
boolean - true, если текущий объект равен параметру  other ; иначе, false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Объект для сравнения с этим объектом. |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Получает или задает версию набора инструментов Adobe Xmp.

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


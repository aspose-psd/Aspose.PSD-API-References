---
title: "XmpRdfRoot"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет элемент rdfRDF."
type: docs
weight: 21
url: /ru/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Представляет элемент rdf:RDF. Один XMP пакет должен сериализоваться с использованием одного XML-элемента rdf:RDF. Содержимое элемента rdf:RDF должно состоять только из нуля или более элементов rdf:Description.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Инициализирует новый экземпляр класса  XmpRdfRoot  . |
## Методы

| Метод | Описание |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Добавляет атрибут. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Назначает указанный элемент XMP текущему. |
| [clearAttributes()](#clearAttributes--) | Удаляет все атрибуты. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный  Object , этому экземпляру. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Получает атрибут. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Получает URI пространства имён по конкретному префиксу. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение xmp в представление xml. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Добавляет URI пространства имён по префиксу. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Инициализирует новый экземпляр класса  XmpRdfRoot  .

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный  Object , этому экземпляру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект  Object  для сравнения с этим экземпляром. |

**Returns:**
boolean -  true  если указанный  Object  равен этому экземпляру; иначе,  false .
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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Получает URI пространства имён по конкретному префиксу. Префикс может начинаться без xmlns.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | java.lang.String | Префикс. |

**Returns:**
java.lang.String - Возвращает URI схемы пакета.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение xmp в представление xml.

**Returns:**
java.lang.String - Возвращает значение XMP, преобразованное в строку XML.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Добавляет URI пространства имён по префиксу. Префикс может начинаться без xmlns.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | java.lang.String | Префикс. |
| namespaceUri | java.lang.String | URI схемы пакета. |

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


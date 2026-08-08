---
title: "XmpArray"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет Xmp Array в XmpPackage."
type: docs
weight: 12
url: /ru/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Представляет Xmp Array в  XmpPackage . todo: Array может содержать сложные данные.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Инициализирует новый экземпляр класса  XmpArray . |
| [XmpArray(int type)](#XmpArray-int-) | Инициализирует новый экземпляр класса  XmpArray . |
## Методы

| Метод | Описание |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | Добавляет новый элемент. |
| [addItem(String item)](#addItem-java.lang.String-) | Добавляет новый элемент. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | Получает массив значений внутри [XmpArray](../../com.aspose.psd.xmp/xmparray). |
| [getValues()](#getValues--) | Получает массив значений внутри XmpArray. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в представление XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает  System.String  который представляет этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Инициализирует новый экземпляр класса  XmpArray .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип массива. |
| items | java.lang.String[] | Список элементов. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Инициализирует новый экземпляр класса  XmpArray .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип массива. |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


Добавляет новый элемент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Элемент, который будет добавлен в список элементов. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Добавляет новый элемент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | java.lang.String | Элемент, который будет добавлен в список элементов. |

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
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


Получает массив значений внутри [XmpArray](../../com.aspose.psd.xmp/xmparray).

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


Получает массив значений внутри XmpArray.

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение XMP в представление XML.

**Returns:**
java.lang.String - Возвращает значение XMP, преобразованное в представление XML.
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




### toString() {#toString--}
```
public String toString()
```


Возвращает  System.String  который представляет этот экземпляр.

**Returns:**
java.lang.String -  System.String  представляющий этот экземпляр.
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


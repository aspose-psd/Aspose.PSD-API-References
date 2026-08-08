---
title: "LengthRecord"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс записи длины подпути"
type: docs
weight: 13
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Класс записи длины подпути
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord). |
| [LengthRecord()](#LengthRecord--) | Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Получает или задает количество записей узлов Bezier. |
| [getClass()](#getClass--) |  |
| [getLength_internalized()](#getLength-internalized--) | Получает длину. |
| [getPathOperations()](#getPathOperations--) | Получает или задает операции пути. |
| [getRecordCount()](#getRecordCount--) | Получает или задает количество записей. |
| [getShapeIndex()](#getShapeIndex--) | Получает или задаёт индекс текущей формы пути в слое. |
| [getSourceData_internalized()](#getSourceData-internalized--) | Получить исходные байты данных. |
| [getType()](#getType--) | Получает тип. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Получает или задает значение, указывающее, закрыт ли этот экземпляр. |
| [isOpen()](#isOpen--) | Получает или задает значение, указывающее, открыт ли этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Получает или задает количество записей узлов Bezier. |
| [setClosed(boolean value)](#setClosed-boolean-) | Получает или задает значение, указывающее, закрыт ли этот экземпляр. |
| [setOpen(boolean value)](#setOpen-boolean-) | Получает или задает значение, указывающее, открыт ли этот экземпляр. |
| [setPathOperations(int value)](#setPathOperations-int-) | Получает или задает операции пути. |
| [setRecordCount(int value)](#setRecordCount-int-) | Получает или задает количество записей. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Получает или задаёт индекс текущей формы пути в слое. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные записи. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Инициализирует новый экземпляр класса [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord).

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
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Получает или задает количество записей узлов Bezier.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength_internalized() {#getLength-internalized--}
```
public final int getLength_internalized()
```


Получает длину.

Значение: Длина.

**Returns:**
int
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Получает или задает операции пути.

**Returns:**
int
### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Получает или задает количество записей.

Значение: количество записей.

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Получает или задаёт индекс текущей формы пути в слое.

**Returns:**
int
### getSourceData_internalized() {#getSourceData-internalized--}
```
public final byte[] getSourceData_internalized()
```


Получить исходные байты данных.

**Returns:**
byte[] - массив байтов.
### getType() {#getType--}
```
public short getType()
```


Получает тип.

Значение: тип.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Получает или задает значение, указывающее, закрыт ли этот экземпляр.

Значение:  true  если этот экземпляр закрыт; иначе,  false .

**Returns:**
boolean
### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Получает или задает значение, указывающее, открыт ли этот экземпляр.

Значение:  true  если этот экземпляр открыт; иначе,  false .

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




### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Получает или задает количество записей узлов Bezier.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Получает или задает значение, указывающее, закрыт ли этот экземпляр.

Значение:  true  если этот экземпляр закрыт; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Получает или задает значение, указывающее, открыт ли этот экземпляр.

Значение:  true  если этот экземпляр открыт; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Получает или задает операции пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Получает или задает количество записей.

Значение: количество записей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Получает или задаёт индекс текущей формы пути в слое.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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


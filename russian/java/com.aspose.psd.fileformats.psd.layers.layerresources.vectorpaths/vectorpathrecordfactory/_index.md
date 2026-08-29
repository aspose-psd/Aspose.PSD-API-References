---
title: "VectorPathRecordFactory"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс фабрики записей векторного пути"
type: docs
weight: 21
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecordfactory/
---

**Inheritance:**
java.lang.Object
```
public final class VectorPathRecordFactory
```

Класс фабрики записей векторного пути
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VectorPathRecordFactory()](#VectorPathRecordFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [producePathRecord(byte[] data)](#producePathRecord-byte---) | Создаёт запись пути. |
| [producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)](#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-) | Создаёт наследника VectorPathRecordSerializer в зависимости от типа VectorPathRecord. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathRecordFactory() {#VectorPathRecordFactory--}
```
public VectorPathRecordFactory()
```


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




### producePathRecord(byte[] data) {#producePathRecord-byte---}
```
public static VectorPathRecord producePathRecord(byte[] data)
```


Создаёт запись пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные записи. |

**Returns:**
[VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) - Created [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
### producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord) {#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-}
```
public static VectorPathRecordSerializer producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)
```


Создаёт наследника VectorPathRecordSerializer в зависимости от типа VectorPathRecord.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorPathRecord | [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) | Объект VectorPathRecord, который должен быть сериализован. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.vectorpaths.serializer.VectorPathRecordSerializer - экземпляр VectorPathRecordSerializer.
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


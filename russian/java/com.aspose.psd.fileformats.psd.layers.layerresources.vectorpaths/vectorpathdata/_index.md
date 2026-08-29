---
title: "VectorPathData"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс для работы с векторным путём."
type: docs
weight: 18
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

Класс для работы с векторным путём.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Инициализирует новый экземпляр класса [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
| [VectorPathData()](#VectorPathData--) | Инициализирует новый экземпляр класса [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata). |
## Поля

| Поле | Описание |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | Размер общей информации, такой как версия и флаги. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Получает в виде массива байтов. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Получает длину данных векторного пути в ресурсе в байтах. |
| [getPaths()](#getPaths--) | Получает или задает записи пути. |
| [getVersion()](#getVersion--) | Получает или задает версию. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| [isInverted()](#isInverted--) | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| [isNotLinked()](#isNotLinked--) | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| [setInverted(boolean value)](#setInverted-boolean-) | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Получает или задает записи пути. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает версию. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Инициализирует новый экземпляр класса [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные ресурса. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Инициализирует новый экземпляр класса [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata).

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


Размер общей информации, такой как версия и флаги.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Получает в виде массива байтов.

**Returns:**
byte[] - Ресурс в виде массива байтов.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Получает длину данных векторного пути в ресурсе в байтах.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Получает или задает записи пути.

Значение: Пути.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает или задает версию.

Значение: Версия.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Получает или задает значение, указывающее, отключен ли этот экземпляр.

Значение:  true  если этот экземпляр отключен; иначе  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Получает или задает значение, указывающее, инвертирован ли этот экземпляр.

Значение:  true  если этот экземпляр инвертирован; иначе  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Получает или задает значение, указывающее, не связан ли этот экземпляр.

Значение:  true  если этот экземпляр не связан; иначе  false .

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Получает или задает значение, указывающее, отключен ли этот экземпляр.

Значение:  true  если этот экземпляр отключен; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Получает или задает значение, указывающее, инвертирован ли этот экземпляр.

Значение:  true  если этот экземпляр инвертирован; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Получает или задает значение, указывающее, не связан ли этот экземпляр.

Значение:  true  если этот экземпляр не связан; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Получает или задает записи пути.

Значение: Пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Получает или задает версию.

Значение: Версия.

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


---
title: "WorkingPathResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Ресурс рабочего пути."
type: docs
weight: 43
url: /ru/java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

Ресурс рабочего пути.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | Инициализирует новый экземпляр класса [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource). |
## Поля

| Поле | Описание |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Сигнатура ресурса ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Обычная сигнатура ресурса Photoshop. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Получает размер данных ресурса в байтах. |
| [getID()](#getID--) | Получает или задает уникальный идентификатор ресурса. |
| [getMinimalVersion()](#getMinimalVersion--) | Получает минимальную требуемую версию PSD. |
| [getName()](#getName--) | Получает или задает имя ресурса. |
| [getPaths()](#getPaths--) | Получает или задает записи пути. |
| [getSignature()](#getSignature--) | Получает сигнатуру ресурса. |
| [getSize()](#getSize--) | Получает размер блока ресурса в байтах, включая его данные. |
| [getVersion()](#getVersion--) | Получает или задает версию. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| [isInverted()](#isInverted--) | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| [isNotLinked()](#isNotLinked--) | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Сохраняет блок ресурса в указанный поток. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Получает или задает значение, указывающее, отключен ли этот экземпляр. |
| [setID(short value)](#setID-short-) | Получает или задает уникальный идентификатор ресурса. |
| [setInverted(boolean value)](#setInverted-boolean-) | Получает или задает значение, указывающее, инвертирован ли этот экземпляр. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Получает или задает информацию о слое и маске. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя ресурса. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Получает или задает значение, указывающее, не связан ли этот экземпляр. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Получает или задает записи пути. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Получает или задает состояние блока ресурса. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает версию. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Проверяет значения ресурса. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


Инициализирует новый экземпляр класса [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataBytes | byte[] | Данные векторного пути. |

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Сигнатура ресурса ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Обычная сигнатура ресурса Photoshop.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Получает размер данных ресурса в байтах.

Значение: Размер данных ресурса.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Получает или задает уникальный идентификатор ресурса.

Значение: Уникальный идентификатор ресурса.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Получает минимальную требуемую версию PSD.

Значение: Минимальная версия PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0).

Значение: Имя ресурса.

**Returns:**
java.lang.String
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Получает или задает записи пути.

Значение: Пути.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Получает подпись ресурса. Должна всегда быть '8BIM'.

Значение: Подпись ресурса.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Получает размер блока ресурса в байтах, включая его данные.

Значение: Размер блока ресурса.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Сохраняет блок ресурса в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Поток, в который сохраняется блок ресурса. |

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

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Получает или задает уникальный идентификатор ресурса.

Значение: Уникальный идентификатор ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Получает или задает информацию о слое и маске.

Значение: Информация о слоях и масках.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0).

Значение: Имя ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| подпись | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Получает или задает состояние блока ресурса.

Значение: Состояние блока ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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
### validateValues() {#validateValues--}
```
public void validateValues()
```


Проверяет значения ресурса.

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


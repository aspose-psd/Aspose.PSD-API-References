---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD for Java API Справочник"
description: "Менеджер для Curves Adjustment Layer, который управляет картой пикселей"
type: docs
weight: 25
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Менеджер слоя корректировки кривых, который управляет картой пикселей
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Инициализирует новый экземпляр класса [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Получает байты ресурса. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Получает карту для обработки фильтра. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Получает максимальное количество каналов. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Получает значение в позиции. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Загружает данные из байтов. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Устанавливает значение по умолчанию в позиции. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Устанавливает значение в позиции. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Устанавливает значение всего канала. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Инициализирует новый экземпляр класса [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxChannelCount | int | Максимальное количество каналов. |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Получает байты ресурса.

**Returns:**
byte[] - Байты для составления CurvResource
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Получает карту для обработки фильтра.

**Returns:**
byte[][] - карта преобразования
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Получает максимальное количество каналов.

Значение: Максимальное количество каналов.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Получает значение в позиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| position | byte | Позиция. |

**Returns:**
byte - значение кривой по её позиции
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


Загружает данные из байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | byte[] | Байты. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Устанавливает значение по умолчанию в позиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| position | byte | Позиция. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Устанавливает значение в позиции.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| position | byte | Позиция. |
| значение | byte | Значение. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Устанавливает значение всего канала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| channelValue | byte[] | Значение канала. |

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


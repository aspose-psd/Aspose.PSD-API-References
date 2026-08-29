---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD for Java API Справочник"
description: "Менеджер слоя корректировки кривых, который управляет кривыми"
type: docs
weight: 24
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Менеджер слоя корректировки кривых, который управляет кривыми
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Инициализирует новый экземпляр класса [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager). |
## Методы

| Метод | Описание |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Добавляет точку кривой. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Получает байты ресурса. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Получает точку кривой по индексу. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Получает количество точек кривой. |
| [getMap_internalized()](#getMap-internalized--) | Получает карту для фильтра обработки. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Получает максимальное количество каналов. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Загружает данные из байтов. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Удаляет точку кривой. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Обновляет точку кривой. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Инициализирует новый экземпляр класса [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxChannelCount | int | Максимальное количество каналов. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Добавляет точку кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| x | byte | Координата x. |
| y | byte | Координата y. |

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
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Получает точку кривой по индексу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| pointIndex | int | Индекс точки. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Получает количество точек кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |

**Returns:**
int - Количество точек кривой в канале
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Получает карту для фильтра обработки.

**Returns:**
byte[][] - Карта для обработки канала.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Получает максимальное количество каналов.

Значение: Максимальное количество каналов.

**Returns:**
int
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




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Удаляет точку кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| pointIndex | int | Индекс точки. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y) {#updateCurvePoint-int-int-byte-byte-}
```
public final void updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)
```


Обновляет точку кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| channelIndex | int | Индекс канала. |
| pointIndex | int | Индекс точки. |
| x | byte | Координата x. |
| y | byte | Координата y. |

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


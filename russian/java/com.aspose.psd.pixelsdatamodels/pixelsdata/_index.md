---
title: "PixelsData"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс для хранения данных пикселей изображения и их границ."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

Класс для хранения данных пикселей изображения и их границ.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PixelsData()](#PixelsData--) | Инициализирует новый экземпляр класса [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
## Методы

| Метод | Описание |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | Создаёт экземпляр PixelsDataLoader для текущего экземпляра [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [createSaver_internalized()](#createSaver-internalized--) | Создаёт экземпляр PixelsDataSaver для текущего экземпляра [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata). |
| [deepClone()](#deepClone--) | Создаёт полную копию экземпляра. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Получает или задаёт границы данных пикселей. |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | Получает или задаёт данные пикселей. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Получает или задаёт границы данных пикселей. |
| [setPixels(int[] value)](#setPixels-int---) | Получает или задаёт данные пикселей. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


Инициализирует новый экземпляр класса [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


Инициализирует новый экземпляр класса [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | Данные пикселей. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Прямоугольник границ пикселей. |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


Создаёт экземпляр PixelsDataLoader для текущего экземпляра [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


Создаёт экземпляр PixelsDataSaver для текущего экземпляра [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).

**Returns:**
com.aspose.internal.IPixelsSaver — новый экземпляр PixelsDataSaver, основанный на текущем экземпляре [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Создаёт полную копию экземпляра.

**Returns:**
java.lang.Object - копия экземпляра.
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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Получает или задаёт границы данных пикселей.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


Получает или задаёт данные пикселей.

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Получает или задаёт границы данных пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


Получает или задаёт данные пикселей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] |  |

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


---
title: "Thumbnail4Resource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет ресурс миниатюры для PSD 4.0."
type: docs
weight: 34
url: /ru/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

Представляет ресурс миниатюры для PSD 4.0.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | Инициализирует новый экземпляр класса [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource). |
## Поля

| Поле | Описание |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Сигнатура ресурса ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Обычная сигнатура ресурса Photoshop. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | Получает или задает количество битов на пиксель. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Получает размер данных ресурса в байтах. |
| [getFormat()](#getFormat--) | Получает или задает формат данных миниатюры. |
| [getHeight()](#getHeight--) | Получает или задает высоту миниатюры в пикселях. |
| [getID()](#getID--) | Получает или задает уникальный идентификатор ресурса. |
| [getJpegOptions()](#getJpegOptions--) | Получает или задает параметры JPEG. |
| [getMinimalVersion()](#getMinimalVersion--) | Получает минимальную требуемую версию PSD. |
| [getName()](#getName--) | Получает или задает имя ресурса. |
| [getPlanesCount()](#getPlanesCount--) | Получает или задает количество плоскостей. |
| [getSignature()](#getSignature--) | Получает сигнатуру ресурса. |
| [getSize()](#getSize--) | Получает размер блока ресурса в байтах, включая его данные. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | Получает или задает размер после сжатия. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | Получает или задает данные миниатюры в формате 32-бит ARGB. |
| [getThumbnailData()](#getThumbnailData--) | Получает или задает данные миниатюры. |
| [getTotalSize()](#getTotalSize--) | Получает общий размер данных. |
| [getWidth()](#getWidth--) | Получает или задает ширину миниатюры в пикселях. |
| [getWidthBytes()](#getWidthBytes--) | Получает ширину строки в байтах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Сохраняет блок ресурса в указанный поток. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | Получает или задает количество битов на пиксель. |
| [setFormat(int value)](#setFormat-int-) | Получает или задает формат данных миниатюры. |
| [setHeight(int value)](#setHeight-int-) | Получает или задает высоту миниатюры в пикселях. |
| [setID(short value)](#setID-short-) | Получает или задает уникальный идентификатор ресурса. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Получает или задает параметры JPEG. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Получает или задает информацию о слое и маске. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя ресурса. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | Получает или задает количество плоскостей. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Получает или задает состояние блока ресурса. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | Получает или задает данные миниатюры в формате 32-бит ARGB. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | Получает или задает данные миниатюры. |
| [setWidth(int value)](#setWidth-int-) | Получает или задает ширину миниатюры в пикселях. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Проверяет значения ресурса. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


Инициализирует новый экземпляр класса [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource).

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


Получает или задает количество битов на пиксель.

Значение: количество битов на пиксель миниатюры.

**Returns:**
short
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
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Получает или задает формат данных миниатюры.

Значение: формат данных миниатюры.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает или задает высоту миниатюры в пикселях.

Значение: высота миниатюры.

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
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Получает или задает параметры JPEG. Подходит, когда ресурс миниатюры сохраняется только в формате JPEG. Эта опция не оказывает влияния, когда определён формат RAW.

Значение: параметры JPEG.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Получает минимальную требуемую версию PSD.

Значение: минимальная версия psd.

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
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


Получает или задает количество плоскостей.

Значение: количество плоскостей миниатюры.

**Returns:**
short
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
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


Получает или задает размер после сжатия. Используется для проверки согласованности.

Значение: размер после сжатия.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


Получает или задает данные миниатюры в формате 32-бит ARGB.

Значение: данные миниатюры в формате 32-бит ARGB.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


Получает или задает данные миниатюры.

Значение: данные миниатюры.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


Получает общий размер данных.

Значение: Общий размер данных.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает или задает ширину миниатюры в пикселях.

Значение: Ширина миниатюры.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


Получает ширину строки в байтах.

Значение: Ширина строки в байтах.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Сохраняет блок ресурса в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Поток, в который сохраняется блок ресурса. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


Получает или задает количество битов на пиксель.

Значение: количество битов на пиксель миниатюры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Получает или задает формат данных миниатюры.

Значение: формат данных миниатюры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Получает или задает высоту миниатюры в пикселях.

Значение: высота миниатюры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Получает или задает параметры JPEG. Подходит, когда ресурс миниатюры сохраняется только в формате JPEG. Эта опция не оказывает влияния, когда определён формат RAW.

Значение: параметры JPEG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

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

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


Получает или задает количество плоскостей.

Значение: количество плоскостей миниатюры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


Получает или задает данные миниатюры в формате 32-бит ARGB.

Значение: данные миниатюры в формате 32-бит ARGB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


Получает или задает данные миниатюры.

Значение: данные миниатюры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Получает или задает ширину миниатюры в пикселях.

Значение: Ширина миниатюры.

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


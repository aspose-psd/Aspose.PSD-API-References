---
title: "PattResourceData"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс для хранения данных шаблона для ресурса."
type: docs
weight: 67
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

Класс для хранения данных шаблона для ресурса [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | Инициализирует новый экземпляр класса [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## Методы

| Метод | Описание |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | Возвращает код метода сжатия, полученный из каналов шаблона. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | Создает данные шаблона по умолчанию. |
| [getHeight()](#getHeight--) | Получает высоту. |
| [getImageMode()](#getImageMode--) | Получает режим изображения. |
| [getLength()](#getLength--) | Получает длину шаблона. |
| [getName()](#getName--) | Получает или задает имя. |
| [getPatternData()](#getPatternData--) | Получает данные шаблона. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | Список массивов памяти. |
| [getPatternId()](#getPatternId--) | Получает или задает идентификатор шаблона. |
| [getVersion()](#getVersion--) | Получает версию. |
| [getWidth()](#getWidth--) | Получает ширину. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Сохраняет данные шаблона. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | Получает высоту. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | Получает режим изображения. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | Получает или задает таблицу индексов цветов. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | Устанавливает буфер пикселей шаблона и целевой размер, обновляет Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), и сохраняет данные для сохранения, используя режим сжатия по умолчанию (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | Список массивов памяти. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Получает или задает идентификатор шаблона. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | Устанавливает буфер пикселей шаблона и целевой размер, обновляет Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), и сохраняет данные для сохранения, используя указанный режим сжатия. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Получает версию. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | Получает ширину. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


Инициализирует новый экземпляр класса [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


Возвращает код метода сжатия, полученный из каналов шаблона.

**Returns:**
byte - Код сжатия: 0 \\u2014 raw/uncompressed; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


Создает данные шаблона по умолчанию.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


Получает высоту.

Значение: Высота.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


Получает режим изображения.

Значение: режим изображения.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


Получает длину шаблона.

Значение: длина шаблона.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя.

Значение: имя.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Получает данные шаблона.

Значение: Данные шаблона.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


Список массивов памяти.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Получает или задает идентификатор шаблона.

Значение: Идентификатор шаблона.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает версию.

Значение: Версия.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


Получает ширину.

Значение: Ширина.

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Сохраняет данные шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока для сохранения. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


Получает высоту.

Значение: Высота.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


Получает режим изображения.

Значение: режим изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


Получает или задает таблицу индексов цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя.

Значение: имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


Устанавливает буфер пикселей шаблона и целевой размер, обновляет Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), и сохраняет данные для сохранения, используя режим сжатия по умолчанию (0).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | 32-битные пиксели в формате 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы пикселей шаблона. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


Список массивов памяти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Получает или задает идентификатор шаблона.

Значение: Идентификатор шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


Устанавливает буфер пикселей шаблона и целевой размер, обновляет Width ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / Height ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)), и сохраняет данные для сохранения, используя указанный режим сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| пиксели | int[] | 32-битные пиксели в формате 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы пикселей шаблона. |
| compressionMode | byte | Режим сжатия, используемый для определения сжатия данных шаблона при сохранении файла psd. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Получает версию.

Значение: Версия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


Получает ширину.

Значение: Ширина.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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


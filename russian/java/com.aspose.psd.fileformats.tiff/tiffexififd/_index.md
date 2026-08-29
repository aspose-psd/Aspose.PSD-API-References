---
title: "TiffExifIfd"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс каталога файлов изображений TIFF Exif."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

Класс каталога файлов изображений TIFF Exif.

Инкапсулирует указатель на Exif IFD. Interoperability, Exif IFD имеет ту же структуру, что и IFD, указанную в TIFF. Обычно, однако, он не содержит данных изображения, как в случае с TIFF. См. http://www.exiv2.org/tags.html и http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html для получения более подробной информации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Инициализирует новый экземпляр класса  TiffExifIfd . |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Инициализирует новый экземпляр класса  TiffExifIfd . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Получает или задает указатель на EXIF IFD. |
| [hasValue()](#hasValue--) | Получает значение, указывающее, имеет ли этот экземпляр значение. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Получает или задает указатель на EXIF IFD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Инициализирует новый экземпляр класса  TiffExifIfd .

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Инициализирует новый экземпляр класса  TiffExifIfd .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | ifdOffset | long | Указатель на Exif IFD. |

Interoperability, Exif IFD имеет ту же структуру, что и IFD, указанную в TIFF. Обычно, однако, он не содержит данных изображения, как в случае с TIFF. |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


Получает или задает указатель на EXIF IFD.

**Returns:**
long - Указатель на EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Получает значение, указывающее, имеет ли этот экземпляр значение.

**Returns:**
boolean -  true  если этот экземпляр имеет значение; иначе,  false .
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




### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Получает или задает указатель на EXIF IFD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Указатель на EXIF IFD. |

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


---
title: "StreamSource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет потоковый источник."
type: docs
weight: 13
url: /ru/java/com.aspose.psd.sources/streamsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public final class StreamSource extends Source
```

Представляет потоковый источник.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StreamSource()](#StreamSource--) | Инициализирует новый экземпляр класса  StreamSource  с Null потоком. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Инициализирует новый экземпляр класса [StreamSource](../../com.aspose.psd.sources/streamsource). |
| [StreamSource(OutputStream destStream)](#StreamSource-java.io.OutputStream-) | Инициализирует новый экземпляр класса [StreamSource](../../com.aspose.psd.sources/streamsource). |
| [StreamSource(OutputStream destStream, boolean disposeStream)](#StreamSource-java.io.OutputStream-boolean-) |  |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) |  |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса [StreamSource](../../com.aspose.psd.sources/streamsource). |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposeStream()](#getDisposeStream--) | Получает значение, указывающее, следует ли освобождать поток, когда контейнер освобождается. |
| [getStream()](#getStream--) |  |
| [getStreamContainer()](#getStreamContainer--) | Получает контейнер потока. |
| [getStream_internalized()](#getStream-internalized--) | Получает поток. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStream(InputStream value)](#setStream-java.io.InputStream-) |  |
| [setStream_internalized(System.IO.Stream value)](#setStream-internalized-com.aspose.ms.System.IO.Stream-) | Получает поток. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Инициализирует новый экземпляр класса  StreamSource  с Null потоком. Этот конструктор позволяет создавать новые изображения без входного потока, изображения хранятся только в памяти.

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Инициализирует новый экземпляр класса [StreamSource](../../com.aspose.psd.sources/streamsource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для открытия. |

### StreamSource(OutputStream destStream) {#StreamSource-java.io.OutputStream-}
```
public StreamSource(OutputStream destStream)
```


Инициализирует новый экземпляр класса [StreamSource](../../com.aspose.psd.sources/streamsource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | целевой поток (например, java.io.ByteArrayOutputStream) |

### StreamSource(OutputStream destStream, boolean disposeStream) {#StreamSource-java.io.OutputStream-boolean-}
```
public StreamSource(OutputStream destStream, boolean disposeStream)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream |  |
| disposeStream | boolean |  |

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса [StreamSource](../../com.aspose.psd.sources/streamsource).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для открытия. |
| disposeStream | boolean | если установить значение  true  поток будет освобожден. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static StreamSource create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### create_internalized(System.IO.Stream stream, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-boolean-}
```
public static StreamSource create_internalized(System.IO.Stream stream, boolean disposeStream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
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
### getDisposeStream() {#getDisposeStream--}
```
public final boolean getDisposeStream()
```


Получает значение, указывающее, следует ли освобождать поток, когда контейнер освобождается.

Значение:  true  если поток следует освободить; иначе  false .

**Returns:**
boolean
### getStream() {#getStream--}
```
public final System.IO.Stream getStream()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Получает контейнер потока.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

--------------------

Используйте с осторожностью. Вам потребуется освободить контейнер потока после получения.
### getStream_internalized() {#getStream-internalized--}
```
public final InputStream getStream_internalized()
```


Получает поток.

Значение: исходный поток.

**Returns:**
java.io.InputStream
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




### setStream(InputStream value) {#setStream-java.io.InputStream-}
```
public final void setStream(InputStream value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.io.InputStream |  |

### setStream_internalized(System.IO.Stream value) {#setStream-internalized-com.aspose.ms.System.IO.Stream-}
```
public final void setStream_internalized(System.IO.Stream value)
```


Получает поток.

Значение: исходный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.IO.Stream |  |

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


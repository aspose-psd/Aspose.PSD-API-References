---
title: "StreamSource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示一个流源。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.sources/streamsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public final class StreamSource extends Source
```

表示一个流源。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StreamSource()](#StreamSource--) | 使用 Null 流初始化 StreamSource 类的新实例。 |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | 初始化 [StreamSource](../../com.aspose.psd.sources/streamsource) 类的新实例。 |
| [StreamSource(OutputStream destStream)](#StreamSource-java.io.OutputStream-) | 初始化 [StreamSource](../../com.aspose.psd.sources/streamsource) 类的新实例。 |
| [StreamSource(OutputStream destStream, boolean disposeStream)](#StreamSource-java.io.OutputStream-boolean-) |  |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) |  |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | 初始化 [StreamSource](../../com.aspose.psd.sources/streamsource) 类的新实例。 |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposeStream()](#getDisposeStream--) | 获取一个值，指示是否在容器被释放时释放 stream。 |
| [getStream()](#getStream--) |  |
| [getStreamContainer()](#getStreamContainer--) | 获取 stream 容器。 |
| [getStream_internalized()](#getStream-internalized--) | 获取 stream。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStream(InputStream value)](#setStream-java.io.InputStream-) |  |
| [setStream_internalized(System.IO.Stream value)](#setStream-internalized-com.aspose.ms.System.IO.Stream-) | 获取 stream。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamSource() {#StreamSource--}
```
public StreamSource()
```


使用 Null 流初始化 StreamSource 类的新实例。此构造函数允许在没有输入 stream 的情况下创建新图像，图像仅存储在内存中。

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


初始化 [StreamSource](../../com.aspose.psd.sources/streamsource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要打开的 stream。 |

### StreamSource(OutputStream destStream) {#StreamSource-java.io.OutputStream-}
```
public StreamSource(OutputStream destStream)
```


初始化 [StreamSource](../../com.aspose.psd.sources/streamsource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 目标流（例如 java.io.ByteArrayOutputStream） |

### StreamSource(OutputStream destStream, boolean disposeStream) {#StreamSource-java.io.OutputStream-boolean-}
```
public StreamSource(OutputStream destStream, boolean disposeStream)
```


**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream |  |
| disposeStream | boolean |  |

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


初始化 [StreamSource](../../com.aspose.psd.sources/streamsource) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 要打开的 stream。 |
| disposeStream | boolean | 如果设置为  true  ，流将被释放。 |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static StreamSource create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### create_internalized(System.IO.Stream stream, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-boolean-}
```
public static StreamSource create_internalized(System.IO.Stream stream, boolean disposeStream)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
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


获取一个值，指示是否在容器被释放时释放 stream。

值：  true  如果应释放流；否则为  false 。

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


获取 stream 容器。

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

--------------------

请谨慎使用。检索后您需要释放流容器。
### getStream_internalized() {#getStream-internalized--}
```
public final InputStream getStream_internalized()
```


获取 stream。

值：源流。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.io.InputStream |  |

### setStream_internalized(System.IO.Stream value) {#setStream-internalized-com.aspose.ms.System.IO.Stream-}
```
public final void setStream_internalized(System.IO.Stream value)
```


获取 stream。

值：源流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.ms.System.IO.Stream |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


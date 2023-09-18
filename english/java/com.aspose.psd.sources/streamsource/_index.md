---
title: StreamSource
second_title: Aspose.PSD for Java API Reference
description: Represents a stream source.
type: docs
weight: 13
url: /java/com.aspose.psd.sources/streamsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public final class StreamSource extends Source
```

Represents a stream source.
## Constructors

| Constructor | Description |
| --- | --- |
| [StreamSource()](#StreamSource--) | Initializes a new instance of the  StreamSource  class with Null stream. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | Initializes a new instance of the [StreamSource](../../com.aspose.psd.sources/streamsource) class. |
| [StreamSource(OutputStream destStream)](#StreamSource-java.io.OutputStream-) | Initializes a new instance of the [StreamSource](../../com.aspose.psd.sources/streamsource) class. |
| [StreamSource(OutputStream destStream, boolean disposeStream)](#StreamSource-java.io.OutputStream-boolean-) |  |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) |  |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | Initializes a new instance of the [StreamSource](../../com.aspose.psd.sources/streamsource) class. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposeStream()](#getDisposeStream--) | Gets a value indicating whether stream should be disposed whenever container gets disposed. |
| [getStream()](#getStream--) |  |
| [getStreamContainer()](#getStreamContainer--) | Gets the stream container. |
| [getStream_internalized()](#getStream-internalized--) | Gets the stream. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStream(InputStream value)](#setStream-java.io.InputStream-) |  |
| [setStream_internalized(System.IO.Stream value)](#setStream-internalized-com.aspose.ms.System.IO.Stream-) | Gets the stream. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Initializes a new instance of the  StreamSource  class with Null stream. This constructor allows to create new images without input stream, images stored only in memory.

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


Initializes a new instance of the [StreamSource](../../com.aspose.psd.sources/streamsource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to open. |

### StreamSource(OutputStream destStream) {#StreamSource-java.io.OutputStream-}
```
public StreamSource(OutputStream destStream)
```


Initializes a new instance of the [StreamSource](../../com.aspose.psd.sources/streamsource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | a destination stream (e.g. java.io.ByteArrayOutputStream) |

### StreamSource(OutputStream destStream, boolean disposeStream) {#StreamSource-java.io.OutputStream-boolean-}
```
public StreamSource(OutputStream destStream, boolean disposeStream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream |  |
| disposeStream | boolean |  |

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


Initializes a new instance of the [StreamSource](../../com.aspose.psd.sources/streamsource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to open. |
| disposeStream | boolean | if set to  true  the stream will be disposed. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static StreamSource create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### create_internalized(System.IO.Stream stream, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-boolean-}
```
public static StreamSource create_internalized(System.IO.Stream stream, boolean disposeStream)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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


Gets a value indicating whether stream should be disposed whenever container gets disposed.

Value:  true  if stream should be disposed; otherwise,  false .

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


Gets the stream container.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

--------------------

Use with caution. You will need to dispose the stream container after retrieval.
### getStream_internalized() {#getStream-internalized--}
```
public final InputStream getStream_internalized()
```


Gets the stream.

Value: The source stream.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### setStream_internalized(System.IO.Stream value) {#setStream-internalized-com.aspose.ms.System.IO.Stream-}
```
public final void setStream_internalized(System.IO.Stream value)
```


Gets the stream.

Value: The source stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.IO.Stream |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


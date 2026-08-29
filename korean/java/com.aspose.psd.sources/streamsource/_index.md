---
title: "StreamSource"
second_title: "Java용 Aspose.PSD API 참조"
description: "스트림 소스를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.aspose.psd.sources/streamsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public final class StreamSource extends Source
```

스트림 소스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StreamSource()](#StreamSource--) | Null 스트림으로 StreamSource 클래스의 새 인스턴스를 초기화합니다. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | 새로운 [StreamSource](../../com.aspose.psd.sources/streamsource) 클래스 인스턴스를 초기화합니다. |
| [StreamSource(OutputStream destStream)](#StreamSource-java.io.OutputStream-) | 새로운 [StreamSource](../../com.aspose.psd.sources/streamsource) 클래스 인스턴스를 초기화합니다. |
| [StreamSource(OutputStream destStream, boolean disposeStream)](#StreamSource-java.io.OutputStream-boolean-) |  |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) |  |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | 새로운 [StreamSource](../../com.aspose.psd.sources/streamsource) 클래스 인스턴스를 초기화합니다. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposeStream()](#getDisposeStream--) | 컨테이너가 폐기될 때마다 스트림을 폐기해야 하는지 여부를 나타내는 값을 가져옵니다. |
| [getStream()](#getStream--) |  |
| [getStreamContainer()](#getStreamContainer--) | 스트림 컨테이너를 가져옵니다. |
| [getStream_internalized()](#getStream-internalized--) | 스트림을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStream(InputStream value)](#setStream-java.io.InputStream-) |  |
| [setStream_internalized(System.IO.Stream value)](#setStream-internalized-com.aspose.ms.System.IO.Stream-) | 스트림을 가져옵니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamSource() {#StreamSource--}
```
public StreamSource()
```


Null 스트림으로 StreamSource 클래스의 새 인스턴스를 초기화합니다. 이 생성자를 사용하면 입력 스트림 없이 새 이미지를 생성할 수 있으며, 이미지는 메모리 내에만 저장됩니다.

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


새로운 [StreamSource](../../com.aspose.psd.sources/streamsource) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 열 스트림. |

### StreamSource(OutputStream destStream) {#StreamSource-java.io.OutputStream-}
```
public StreamSource(OutputStream destStream)
```


새로운 [StreamSource](../../com.aspose.psd.sources/streamsource) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 대상 스트림 (예: java.io.ByteArrayOutputStream) |

### StreamSource(OutputStream destStream, boolean disposeStream) {#StreamSource-java.io.OutputStream-boolean-}
```
public StreamSource(OutputStream destStream, boolean disposeStream)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destStream | java.io.OutputStream |  |
| disposeStream | boolean |  |

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


새로운 [StreamSource](../../com.aspose.psd.sources/streamsource) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 열 스트림. |
| disposeStream | boolean | true 로 설정하면 스트림이 폐기됩니다. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static StreamSource create_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### create_internalized(System.IO.Stream stream, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-boolean-}
```
public static StreamSource create_internalized(System.IO.Stream stream, boolean disposeStream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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


컨테이너가 폐기될 때마다 스트림을 폐기해야 하는지 여부를 나타내는 값을 가져옵니다.

값: 스트림을 폐기해야 하면 true, 그렇지 않으면 false.

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


스트림 컨테이너를 가져옵니다.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

--------------------

주의해서 사용하십시오. 검색 후 스트림 컨테이너를 폐기해야 합니다.
### getStream_internalized() {#getStream-internalized--}
```
public final InputStream getStream_internalized()
```


스트림을 가져옵니다.

값: 원본 스트림.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.io.InputStream |  |

### setStream_internalized(System.IO.Stream value) {#setStream-internalized-com.aspose.ms.System.IO.Stream-}
```
public final void setStream_internalized(System.IO.Stream value)
```


스트림을 가져옵니다.

값: 원본 스트림.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.ms.System.IO.Stream |  |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


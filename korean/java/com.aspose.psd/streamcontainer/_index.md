---
title: "StreamContainer"
second_title: "Java용 Aspose.PSD API 참조"
description: "스트림을 포함하고 스트림 처리 루틴을 제공하는 스트림 컨테이너를 나타냅니다."
type: docs
weight: 103
url: /ko/java/com.aspose.psd/streamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

스트림을 포함하고 스트림 처리 루틴을 제공하는 스트림 컨테이너를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | 새로운  StreamContainer  클래스 인스턴스를 초기화합니다. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) |  |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | 새로운  StreamContainer  클래스 인스턴스를 초기화합니다. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | 순차적으로 읽을 때 읽기 및 쓰기 바이트 수를 지정합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [canRead()](#canRead--) | 스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| [canSeek()](#canSeek--) | 스트림이 탐색을 지원하는지 여부를 나타내는 값을 가져옵니다. |
| [canWrite()](#canWrite--) | 스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | 이 스트림의 모든 버퍼를 지우고 버퍼링된 데이터를 기본 장치에 기록하도록 합니다. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getLength()](#getLength--) | 스트림 길이를 바이트 단위로 가져오거나 설정합니다. |
| [getPosition()](#getPosition--) | 스트림 내 현재 위치를 가져오거나 설정합니다. |
| [getStream()](#getStream--) | 데이터 스트림을 가져옵니다. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | 동기화된 리소스에 대한 액세스를 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | 이 스트림이 닫힐 때 폐기되는지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | 지정된 바이트 버퍼를 채우기 위해 바이트를 읽습니다. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | 현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내 위치를 이동합니다. |
| [readByte()](#readByte--) | 스트림에서 한 바이트를 읽고 스트림 내 위치를 한 바이트만큼 이동하거나, 스트림 끝에 도달하면 -1을 반환합니다. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | 스트림의 모든 데이터를 지정된 스트림에 저장(복사)합니다. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| [save(String filePath)](#save-java.lang.String-) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| [seek(long offset, int origin)](#seek-long-int-) | 현재 스트림 내 위치를 설정합니다. |
| [seekBegin()](#seekBegin--) | 스트림 위치를 스트림 시작으로 설정합니다. |
| [setLength(long value)](#setLength-long-) | 스트림 길이를 바이트 단위로 가져오거나 설정합니다. |
| [setPosition(long value)](#setPosition-long-) | 스트림 내 현재 위치를 가져오거나 설정합니다. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | 스트림 데이터를 바이트 배열로 변환합니다. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | 스트림 데이터를 바이트 배열로 변환합니다. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | 명시적 변환을 수행합니다  com.aspose.imaging.StreamContainer  에서  System.IO.Stream  로. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | 지정된 모든 바이트를 스트림에 씁니다. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | 바이트 시퀀스를 현재 스트림에 쓰고, 쓰여진 바이트 수만큼 이 스트림 내 현재 위치를 이동합니다. |
| [writeByte(byte value)](#writeByte-byte-) | 스트림의 현재 위치에 한 바이트를 쓰고 스트림 내 위치를 한 바이트만큼 이동합니다. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | 포함된 데이터를 다른  StreamContainer  로 복사합니다. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | 포함된 데이터를 다른  StreamContainer  로 복사합니다. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


새로운  StreamContainer  클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 스트림. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


새로운  StreamContainer  클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 데이터 스트림. |
| disposeStream | boolean | true 로 설정하면 컨테이너가 해제될 때 스트림이 해제됩니다. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


순차적으로 읽을 때 읽기 및 쓰기 바이트 수를 지정합니다.

### canRead() {#canRead--}
```
public boolean canRead()
```


스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다.

값: 스트림이 읽기를 지원하면 true, 그렇지 않으면 false.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


스트림이 탐색을 지원하는지 여부를 나타내는 값을 가져옵니다.

값: 스트림이 탐색을 지원하면 true, 그렇지 않으면 false.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다.

값: 스트림이 쓰기를 지원하면 true, 그렇지 않으면 false.

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

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
### flush() {#flush--}
```
public void flush()
```


이 스트림의 모든 버퍼를 지우고 버퍼링된 데이터를 기본 장치에 기록하도록 합니다.

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getLength() {#getLength--}
```
public long getLength()
```


스트림 길이를 바이트 단위로 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치만큼 System.IO.Stream.Length 보다 작습니다.

값: 스트림 길이.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


스트림 내 현재 위치를 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다.

값: 현재 스트림 위치.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


데이터 스트림을 가져옵니다.

값: 데이터 스트림.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


동기화된 리소스에 대한 액세스를 동기화하는 데 사용할 수 있는 객체를 가져옵니다.

값: 동기화된 리소스에 대한 접근을 동기화하는 데 사용할 수 있는 객체.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


이 스트림이 닫힐 때 폐기되는지 여부를 나타내는 값을 가져옵니다.

값: 스트림이 닫을 때 해제되면 true, 그렇지 않으면 false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


지정된 바이트 버퍼를 채우기 위해 바이트를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 바이트 | byte[] | 채울 바이트. |

**Returns:**
int - 읽은 바이트 수. 스트림에 바이트가 충분하지 않으면 이 값은 버퍼의 바이트 수보다 작을 수 있습니다.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내 위치를 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 버퍼 | byte[] | 바이트 배열. 이 메서드가 반환될 때, 버퍼는 지정된 바이트 배열을 포함하며, offset과 (offset + count - 1) 사이의 값은 현재 소스에서 읽은 바이트로 교체됩니다. |
| 오프셋 | int | 현재 스트림에서 읽은 데이터를 저장하기 시작하는 buffer의 0 기반 바이트 오프셋. |
| count | int | 현재 스트림에서 읽을 최대 바이트 수. |

**Returns:**
int - 버퍼에 읽힌 총 바이트 수. 요청된 바이트 수보다 적을 수 있으며, 현재 사용할 수 있는 바이트가 부족하거나 스트림 끝에 도달하면 0(0)이 됩니다.
### readByte() {#readByte--}
```
public int readByte()
```


스트림에서 한 바이트를 읽고 스트림 내 위치를 한 바이트만큼 이동하거나, 스트림 끝에 도달하면 -1을 반환합니다.

**Returns:**
int - unsigned byte를 Int32로 변환한 값, 또는 스트림 끝에 도달하면 -1.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 ReadWriteBytesCount와 스트림 Length 값을 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 데이터를 저장할 스트림. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


지정된 스트림에 스트림의 모든 데이터를 저장(복사)합니다. 스트림  Length  값을 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 데이터를 저장할 스트림. |
| bufferSize | int | 버퍼입니다. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


스트림의 데이터를 지정된 스트림에 저장(복사)합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 데이터를 저장할 스트림. |
| bufferSize | int | 버퍼 크기입니다. 기본값으로  ReadWriteBytesCount  값을 사용합니다. |
| length | long | 복사할 스트림 데이터 길이입니다. 기본적으로 길이는  Length  값으로 설정됩니다. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 ReadWriteBytesCount와 스트림 Length 값을 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 스트림 데이터를 저장할 파일 경로입니다. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


지정된 스트림에 스트림 데이터를 저장(복사)합니다. 스트림  Length  값을 사용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 스트림 데이터를 저장할 파일 경로입니다. |
| bufferSize | int | 버퍼 크기입니다. 기본값으로  ReadWriteBytesCount  값을 사용합니다. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


스트림의 데이터를 지정된 스트림에 저장(복사)합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 스트림 데이터를 저장할 파일 경로입니다. |
| bufferSize | int | 버퍼 크기입니다. 기본값으로  ReadWriteBytesCount  값을 사용합니다. |
| length | long | 복사할 스트림 데이터 길이입니다. 기본적으로 길이는  Length  값으로 설정됩니다. |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


현재 스트림 내 위치를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 오프셋 | long | origin 매개변수에 상대적인 바이트 오프셋입니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| origin | int | 새 위치를 얻기 위해 사용되는 기준점을 나타내는  System.IO.SeekOrigin  유형의 값입니다. |

**Returns:**
long - 현재 스트림 내의 새로운 위치입니다.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


스트림 위치를 스트림의 시작으로 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


스트림 길이를 바이트 단위로 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치만큼 System.IO.Stream.Length 보다 작습니다.

값: 스트림 길이.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


스트림 내 현재 위치를 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다.

값: 현재 스트림 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


스트림 데이터를 바이트 배열로 변환합니다.

**Returns:**
byte[] - 스트림 데이터를  byte  배열로 변환한 것입니다.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


스트림 데이터를 바이트 배열로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 바이트를 읽기 시작할 위치입니다. |
| bytesCount | long | 읽을 바이트 수입니다. |

**Returns:**
byte[] - 스트림 데이터를  byte  배열로 변환한 것입니다.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


명시적 변환을 수행합니다  com.aspose.imaging.StreamContainer  에서  System.IO.Stream  로.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

**Returns:**
com.aspose.ms.System.IO.Stream - 변환 결과입니다.
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


지정된 모든 바이트를 스트림에 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 바이트 | byte[] | 쓸 바이트입니다. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


바이트 시퀀스를 현재 스트림에 쓰고, 쓰여진 바이트 수만큼 이 스트림 내 현재 위치를 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 버퍼 | byte[] | 바이트 배열입니다. 이 메서드는  count  바이트를  buffer  에서 현재 스트림으로 복사합니다. |
| 오프셋 | int | 현재 스트림으로 바이트를 복사하기 시작할  buffer  내의 0 기반 바이트 오프셋입니다. |
| count | int | 현재 스트림에 쓸 바이트 수입니다. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


스트림의 현재 위치에 한 바이트를 쓰고 스트림 내 위치를 한 바이트만큼 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte | 스트림에 쓸 바이트입니다. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


포함된 데이터를 다른  StreamContainer  로 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 복사할 스트림 컨테이너입니다. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


포함된 데이터를 다른  StreamContainer  로 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 복사할 스트림 컨테이너입니다. |
| length | long | 쓸 바이트 수입니다. |


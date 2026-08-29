---
title: "FileStreamContainer"
second_title: "Aspose.PSD 的 Java API 参考"
description: "文件流处理助手。"
type: docs
weight: 44
url: /zh/java/com.aspose.psd/filestreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

文件流处理助手。
## 字段

| 字段 | 描述 |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | 指定顺序读取时的读写字节计数。 |
## Methods

| Method | 描述 |
| --- | --- |
| [canRead()](#canRead--) | 获取一个值，指示流是否支持读取。 |
| [canSeek()](#canSeek--) | 获取一个值，指示流是否支持定位。 |
| [canWrite()](#canWrite--) | 获取一个值，指示流是否支持写入。 |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | 创建一个新的文件流。 |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | 清除此流的所有缓冲区，并导致任何缓冲的数据写入底层设备。 |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getFilePath()](#getFilePath--) | 获取文件路径。 |
| [getLength()](#getLength--) | 获取或设置流的字节长度。 |
| [getPosition()](#getPosition--) | 获取或设置流中的当前位置。 |
| [getStream()](#getStream--) | 获取数据流。 |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | 获取一个可用于同步对同步资源访问的对象。 |
| [hashCode()](#hashCode--) |  |
| [isCreated()](#isCreated--) | 获取指示流是否显式创建的值。 |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | 获取一个值，指示此流在关闭时是否被释放。 |
| [isTemporal()](#isTemporal--) | 获取或设置指示流是否为临时的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | 打开现有的文件流。 |
| [openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)](#openFileStream-internalized-java.lang.String-boolean-) | 打开现有的文件流。 |
| [read(byte[] bytes)](#read-byte---) | 读取字节以填充指定的字节缓冲区。 |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | 从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| [readByte()](#readByte--) | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾，则返回 -1。 |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | 将流的数据保存（复制）到指定的流。 |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | 将流的全部数据保存（复制）到指定的流。 |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | 将流的数据保存（复制）到指定的流。 |
| [save(String filePath)](#save-java.lang.String-) | 将流的数据保存（复制）到指定的流。 |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | 将流的数据保存（复制）到指定的流。 |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | 将流的数据保存（复制）到指定的流。 |
| [seek(long offset, int origin)](#seek-long-int-) | 设置当前流中的位置。 |
| [seekBegin()](#seekBegin--) | 将流位置设置为流的开头。 |
| [setLength(long value)](#setLength-long-) | 获取或设置流的字节长度。 |
| [setPosition(long value)](#setPosition-long-) | 获取或设置流中的当前位置。 |
| [setTemporal(boolean value)](#setTemporal-boolean-) | 获取或设置指示流是否为临时的值。 |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | 将流数据转换为字节数组。 |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | 将流数据转换为字节数组。 |
| [toString()](#toString--) |  |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.psd.FileStreamContainer-) | 执行从 [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) 到 FileInputStream 的显式转换。 |
| [to_FileStream_internalized(FileStreamContainer fileStreamContainer)](#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.psd.FileStreamContainer-) | 执行从 [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) 到 java.io.InputStream 的显式转换。 |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | 执行从 com.aspose.imaging.StreamContainer 到 System.IO.Stream 的显式转换。 |
| [to_Stream_internalized(FileStreamContainer fileStreamContainer)](#to-Stream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | 将所有指定的字节写入流。 |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | 将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。 |
| [writeByte(byte value)](#writeByte-byte-) | 在流的当前位置写入一个字节，并将流中的位置前移一个字节。 |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | 将包含的数据复制到另一个 StreamContainer。 |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | 将包含的数据复制到另一个 StreamContainer。 |
### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


指定顺序读取时的读写字节计数。

### canRead() {#canRead--}
```
public boolean canRead()
```


获取一个值，指示流是否支持读取。

值：true 表示流支持读取；否则为 false。

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


获取一个值，指示流是否支持定位。

值：true 表示流支持定位；否则为 false。

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


获取一个值，指示流是否支持写入。

值：true 表示流支持写入；否则为 false。

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


创建一个新的文件流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fileLocation | java.lang.String | 文件位置。 |
| isTemporal | boolean | 如果设置为 true，文件流容器是临时的。 |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parameter | Type | 描述 |
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


释放当前实例。

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
### flush() {#flush--}
```
public void flush()
```


清除此流的所有缓冲区，并导致任何缓冲的数据写入底层设备。

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


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


获取文件路径。

值：文件路径。

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public long getLength()
```


获取或设置流的字节长度。该值比 System.IO.Stream.Length 小，差值为在 StreamContainer 构造函数中传入的起始流位置。

值：流的长度。

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


获取或设置流中的当前位置。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。

值：当前流位置。

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


获取数据流。

值：数据流。

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


获取一个可用于同步对同步资源访问的对象。

值：可用于同步对已同步资源访问的对象。

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCreated() {#isCreated--}
```
public final boolean isCreated()
```


获取指示流是否显式创建的值。

值： true，如果流是显式创建的；否则， false。

**Returns:**
boolean
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


获取一个值，指示此流在关闭时是否被释放。

值： true 如果在关闭时释放流，则为 true；否则为 false。

**Returns:**
boolean
### isTemporal() {#isTemporal--}
```
public final boolean isTemporal()
```


获取或设置指示流是否为临时的值。

值： true，如果流是临时的；否则， false。

--------------------

临时流在释放时会自行移除。如果流是基于内存的，则此属性无效。流可以在显式创建的情况下标记为临时或持久，否则将抛出相应的异常。

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




### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


打开现有的文件流。如果文件流不存在，将抛出相应的异常。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fileLocation | java.lang.String | 文件位置。 |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams) {#openFileStream-internalized-java.lang.String-boolean-}
```
public static FileStreamContainer openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)
```


打开现有的文件流。如果文件流不存在，将抛出相应的异常。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fileLocation | java.lang.String | 文件位置。 |
| disposeDuplicatedStreams | boolean | 如果设置为 true，则释放重复的流。 |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


读取字节以填充指定的字节缓冲区。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 字节 | byte[] | 要填充的字节。 |

**Returns:**
int - 读取的字节数。如果流中的字节不足，此值可能小于缓冲区中的字节数。
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


从当前流读取一系列字节，并将流中的位置前移读取的字节数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| buffer | byte[] | 字节数组。当此方法返回时，缓冲区包含指定的字节数组，其中 offset 与 (offset + count - 1) 之间的值已被从当前源读取的字节替换。 |
| offset | int | 在 buffer 中的零基字节偏移量，指示从当前流读取的数据开始存储的位置。 |
| count | int | 从当前流读取的最大字节数。 |

**Returns:**
int - 读取到缓冲区的字节总数。如果当前可用的字节不足请求的数量，则可能小于请求的字节数；如果已到达流的末尾，则为零 (0)。
### readByte() {#readByte--}
```
public int readByte()
```


从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾，则返回 -1。

**Returns:**
int - 转换为 Int32 的无符号字节，或在流末尾时为 -1。
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


将流的数据保存（复制）到指定的流。使用默认缓冲区大小 ReadWriteBytesCount 和流 Length 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 要将数据保存到的流。 |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


将所有流的数据保存（复制）到指定的流。使用流 Length 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 要将数据保存到的流。 |
| bufferSize | int | 缓冲区。 |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


将流的数据保存（复制）到指定的流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | 要将数据保存到的流。 |
| bufferSize | int | 缓冲区大小。默认使用 ReadWriteBytesCount 的值。 |
| 长度 | long | 要复制的流数据长度。默认情况下，长度设置为 Length 的值。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


将流的数据保存（复制）到指定的流。使用默认缓冲区大小 ReadWriteBytesCount 和流 Length 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要将流数据保存到的文件路径。 |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


将流的数据保存（复制）到指定的流。使用流 Length 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要将流数据保存到的文件路径。 |
| bufferSize | int | 缓冲区大小。默认使用 ReadWriteBytesCount 的值。 |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


将流的数据保存（复制）到指定的流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 要将流数据保存到的文件路径。 |
| bufferSize | int | 缓冲区大小。默认使用 ReadWriteBytesCount 的值。 |
| 长度 | long | 要复制的流数据长度。默认情况下，长度设置为 Length 的值。 |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


设置当前流中的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| offset | long | 相对于 origin 参数的字节偏移量。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移。 |
| origin | int | 一个类型为 System.IO.SeekOrigin 的值，指示用于获取新位置的参考点。 |

**Returns:**
long - 当前流中的新位置。
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


将流位置设置为流的起始位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


获取或设置流的字节长度。该值比 System.IO.Stream.Length 小，差值为在 StreamContainer 构造函数中传入的起始流位置。

值：流的长度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


获取或设置流中的当前位置。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。

值：当前流位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setTemporal(boolean value) {#setTemporal-boolean-}
```
public final void setTemporal(boolean value)
```


获取或设置指示流是否为临时的值。

值： true，如果流是临时的；否则， false。

--------------------

临时流在释放时会自行移除。如果流是基于内存的，则此属性无效。流可以在显式创建的情况下标记为临时或持久，否则将抛出相应的异常。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


将流数据转换为字节数组。

**Returns:**
byte[] - 转换为字节数组的流数据。
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


将流数据转换为字节数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| position | long | 开始读取字节的位置。 |
| bytesCount | long | 要读取的字节数。 |

**Returns:**
byte[] - 转换为字节数组的流数据。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.psd.FileStreamContainer-}
```
public static FileInputStream to_FileStream(FileStreamContainer fileStreamContainer)
```


执行从 [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) 到 FileInputStream 的显式转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | 文件流容器。 |

**Returns:**
java.io.FileInputStream - 转换的结果。
### to_FileStream_internalized(FileStreamContainer fileStreamContainer) {#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.FileStream
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.psd.FileStreamContainer-}
```
public static InputStream to_Stream(FileStreamContainer fileStreamContainer)
```


执行从 [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) 到 java.io.InputStream 的显式转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | 文件流容器。 |

**Returns:**
java.io.InputStream - 转换的结果。
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


执行从 com.aspose.imaging.StreamContainer 到 System.IO.Stream 的显式转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |

**Returns:**
com.aspose.ms.System.IO.Stream - 转换的结果。
### to_Stream_internalized(FileStreamContainer fileStreamContainer) {#to-Stream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.Stream to_Stream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.Stream
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


将所有指定的字节写入流。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 字节 | byte[] | 要写入的字节。 |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| buffer | byte[] | 字节数组。此方法将 count 字节从 buffer 复制到当前流。 |
| offset | int | buffer 中的零基字节偏移量，指示从何处开始将字节复制到当前流。 |
| count | int | 写入当前流的字节数。 |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


在流的当前位置写入一个字节，并将流中的位置前移一个字节。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte | 写入流的字节。 |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


将包含的数据复制到另一个 StreamContainer。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要复制到的流容器。 |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


将包含的数据复制到另一个 StreamContainer。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要复制到的流容器。 |
| 长度 | long | 要写入的字节数。 |


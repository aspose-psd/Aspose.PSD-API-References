---
title: SplitStreamContainer
second_title: Aspose.PSD for Java API Reference
description: Represents split stream container which contains the stream and provides stream processing routines.
type: docs
weight: 102
url: /java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Represents split stream container which contains the stream and provides stream processing routines.
## Constructors

| Constructor | Description |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Initializes a new instance of the [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) class. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Initializes a new instance of the [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) class. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | Initializes a new instance of the [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) class. |
## Fields

| Field | Description |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Specifies read and write bytes count when reading sequentially. |
## Methods

| Method | Description |
| --- | --- |
| [canRead()](#canRead--) | Gets a value indicating whether stream supports reading. |
| [canSeek()](#canSeek--) | Gets a value indicating whether stream supports seeking. |
| [canWrite()](#canWrite--) | Gets a value indicating whether stream supports writing. |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getLength()](#getLength--) | Gets or sets the stream length in bytes. |
| [getPosition()](#getPosition--) | Gets or sets the current position within the stream. |
| [getStream()](#getStream--) | Gets the data stream. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the synchronized resource. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | Inserts the stream container into specified position. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Gets a value indicating whether this stream is disposed on close. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Reads bytes to fill the specified bytes buffer. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [readByte()](#readByte--) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Saves (copies) the stream's data to the specified stream. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Saves (copies) all the stream's data to the specified stream. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Saves (copies) the stream's data to the specified stream. |
| [save(String filePath)](#save-java.lang.String-) | Saves (copies) the stream's data to the specified stream. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Saves (copies) the stream's data to the specified stream. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Saves (copies) the stream's data to the specified stream. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | Sets the position within the current stream. |
| [seekBegin()](#seekBegin--) | Sets the stream position to the beginning of the stream. |
| [setLength(long value)](#setLength-long-) | Gets or sets the stream length in bytes. |
| [setPosition(long value)](#setPosition-long-) | Gets or sets the current position within the stream. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Converts the stream data to the  byte  array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Converts the stream data to the  byte  array. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Performs an explicit conversion from  com.aspose.imaging.StreamContainer  to  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Writes all of the specified bytes to the stream. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [writeByte(byte value)](#writeByte-byte-) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Copies the contained data to another  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Copies the contained data to another  StreamContainer . |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Initializes a new instance of the [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Initializes a new instance of the [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The data stream. |
| disposeStream | boolean | if set to  true  the stream will be disposed when container is disposed. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Initializes a new instance of the [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| disposeStream | boolean | if set to  true  disposes stream. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Specifies read and write bytes count when reading sequentially.

### canRead() {#canRead--}
```
public boolean canRead()
```


Gets a value indicating whether stream supports reading.

Value:  true  if stream supports reading; otherwise,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Gets a value indicating whether stream supports seeking.

Value:  true  if stream supports seeking; otherwise,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Gets a value indicating whether stream supports writing.

Value:  true  if stream supports writing; otherwise,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parameter | Type | Description |
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


Disposes the current instance.

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
### flush() {#flush--}
```
public void flush()
```


Clears all buffers for this stream and causes any buffered data to be written to the underlying device.

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


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getLength() {#getLength--}
```
public long getLength()
```


Gets or sets the stream length in bytes. This value is less than the  System.IO.Stream.Length  by the starting stream position passed in the StreamContainer constructor.

Value: The stream length.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

Value: The current stream position.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Gets the data stream.

Value: The data stream.

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
public final Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the synchronized resource.

Value: The object that can be used to synchronize access to the synchronized resource.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


Inserts the stream container into specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | The position to insert to. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to insert. |
| disposeStream | boolean | if set to  true  disposes stream. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Gets a value indicating whether this stream is disposed on close.

Value:  true  if stream is disposed on close; otherwise,  false .

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


Reads bytes to fill the specified bytes buffer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The bytes to fill. |

**Returns:**
int - The number of bytes read. This value can be less than the number of bytes in the buffer if there is not enough bytes in the stream.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | An array of bytes. When this method returns, the buffer contains the specified byte array with the values between  offset  and ( offset  +  count  - 1) replaced by the bytes read from the current source. |
| offset | int | The zero-based byte offset in  buffer  at which to begin storing the data read from the current stream. |
| count | int | The maximum number of bytes to be read from the current stream. |

**Returns:**
int - The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.
### readByte() {#readByte--}
```
public int readByte()
```


Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.

**Returns:**
int - The unsigned byte cast to an Int32, or -1 if at the end of the stream.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Saves (copies) the stream's data to the specified stream. Uses default buffer size  ReadWriteBytesCount  and stream  Length  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | The stream to save the data to. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Saves (copies) all the stream's data to the specified stream. Uses stream  Length  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | The stream to save the data to. |
| bufferSize | int | The buffer. |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


Saves (copies) the stream's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dstStream | java.io.OutputStream | The stream to save the data to. |
| bufferSize | int | The buffer size. By default [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT) value is used. |
| length | long | The stream data length to copy. By default the length is set to  Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)) value. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Saves (copies) the stream's data to the specified stream. Uses default buffer size  ReadWriteBytesCount  and stream  Length  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the stream data to. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Saves (copies) the stream's data to the specified stream. Uses stream  Length  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the stream data to. |
| bufferSize | int | The buffer size. By default  ReadWriteBytesCount  value is used. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Saves (copies) the stream's data to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the stream data to. |
| bufferSize | int | The buffer size. By default  ReadWriteBytesCount  value is used. |
| length | long | The stream data length to copy. By default the length is set to  Length  value. |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| length | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Sets the position within the current stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offset | long | A byte offset relative to the  origin  parameter. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| origin | int | A value of type [SeekOrigin](../../com.aspose.psd/seekorigin) indicating the reference point used to obtain the new position. |

**Returns:**
long - The new position within the current stream.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Gets or sets the stream length in bytes. This value is less than the  System.IO.Stream.Length  by the starting stream position passed in the StreamContainer constructor.

Value: The stream length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor.

Value: The current stream position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Converts the stream data to the  byte  array.

**Returns:**
byte[] - The stream data converted to the  byte  array.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Converts the stream data to the  byte  array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | long | The position to start reading bytes from. |
| bytesCount | long | The bytes count to read. |

**Returns:**
byte[] - The stream data converted to the  byte  array.
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


Performs an explicit conversion from  com.aspose.imaging.StreamContainer  to  System.IO.Stream .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |

**Returns:**
com.aspose.ms.System.IO.Stream - The result of the conversion.
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Writes all of the specified bytes to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] | The bytes to write. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | An array of bytes. This method copies  count  bytes from  buffer  to the current stream. |
| offset | int | The zero-based byte offset in  buffer  at which to begin copying bytes to the current stream. |
| count | int | The number of bytes to be written to the current stream. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Writes a byte to the current position in the stream and advances the position within the stream by one byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The byte to write to the stream. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copies the contained data to another  StreamContainer .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to copy to. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copies the contained data to another  StreamContainer .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to copy to. |
| length | long | The bytes count to write. |


---
title: StreamContainer
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5440
url: /net/aspose.psd/streamcontainer/
---
## StreamContainer class

Represents stream container which contains the stream and provides stream processing routines.

```csharp
public class StreamContainer : DisposableObject
```

## Constructors

| Name | Description |
| --- | --- |
| [StreamContainer](streamcontainer)(Stream) | Initializes a new instance of the [`StreamContainer`](../streamcontainer) class. |
| [StreamContainer](streamcontainer)(Stream, bool) | Initializes a new instance of the [`StreamContainer`](../streamcontainer) class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [CanRead](canread) { get; } | Gets a value indicating whether stream supports reading. |
| virtual [CanSeek](canseek) { get; } | Gets a value indicating whether stream supports seeking. |
| virtual [CanWrite](canwrite) { get; } | Gets a value indicating whether stream supports writing. |
| virtual [IsStreamDisposedOnClose](isstreamdisposedonclose) { get; } | Gets a value indicating whether this stream is disposed on close. |
| virtual [Length](length) { get; set; } | Gets or sets the stream length in bytes. This value is less than the Length by the starting stream position passed in the StreamContainer constructor. |
| virtual [Position](position) { get; set; } | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [Stream](stream) { get; } | Gets the data stream. |
| [SyncRoot](syncroot) { get; } | Gets an object that can be used to synchronize access to the synchronized resource. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Flush](flush)() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| virtual [Read](read)(byte[]) | Reads bytes to fill the specified bytes buffer. |
| virtual [Read](read)(byte[], int, int) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| virtual [ReadByte](readbyte)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| virtual [Save](save)(Stream) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](./readwritebytescount) and stream [`Length`](./length) value. |
| virtual [Save](save)(string) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](./readwritebytescount) and stream [`Length`](./length) value. |
| virtual [Save](save)(Stream, int) | Saves (copies) all the stream's data to the specified stream. Uses stream [`Length`](./length) value. |
| virtual [Save](save)(string, int) | Saves (copies) the stream's data to the specified stream. Uses stream [`Length`](./length) value. |
| virtual [Save](save)(Stream, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Save](save)(string, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Seek](seek)(long, SeekOrigin) | Sets the position within the current stream. |
| virtual [SeekBegin](seekbegin)() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [ToBytes](tobytes)() | Converts the stream data to the Byte array. |
| virtual [ToBytes](tobytes)(long, long) | Converts the stream data to the Byte array. |
| virtual [Write](write)(byte[]) | Writes all of the specified bytes to the stream. |
| virtual [Write](write)(byte[], int, int) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| virtual [WriteByte](writebyte)(byte) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| virtual [WriteTo](writeto)(StreamContainer) | Copies the contained data to another [`StreamContainer`](../streamcontainer). |
| virtual [WriteTo](writeto)(StreamContainer, long) | Copies the contained data to another [`StreamContainer`](../streamcontainer). |
| [explicit operator](op_explicit) | Performs an explicit conversion from [`StreamContainer`](../streamcontainer) to Stream. |

## Other Members

| Name | Description |
| --- | --- |
| const [ReadWriteBytesCount](readwritebytescount) | Specifies read and write bytes count when reading sequentially. |

### See Also

* class [DisposableObject](../disposableobject)
* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
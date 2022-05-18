---
title: StreamContainer
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5490
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
| virtual [CanRead](../../aspose.psd/streamcontainer/canread) { get; } | Gets a value indicating whether stream supports reading. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek) { get; } | Gets a value indicating whether stream supports seeking. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite) { get; } | Gets a value indicating whether stream supports writing. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Gets a value indicating whether this stream is disposed on close. |
| virtual [Length](../../aspose.psd/streamcontainer/length) { get; set; } | Gets or sets the stream length in bytes. This value is less than the Length by the starting stream position passed in the StreamContainer constructor. |
| virtual [Position](../../aspose.psd/streamcontainer/position) { get; set; } | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream) { get; } | Gets the data stream. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot) { get; } | Gets an object that can be used to synchronize access to the synchronized resource. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Disposes the current instance. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush)() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| virtual [Read](../../aspose.psd/streamcontainer/read)(byte[]) | Reads bytes to fill the specified bytes buffer. |
| virtual [Read](../../aspose.psd/streamcontainer/read)(byte[], int, int) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](./readwritebytescount) and stream [`Length`](./length) value. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](./readwritebytescount) and stream [`Length`](./length) value. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream, int) | Saves (copies) all the stream's data to the specified stream. Uses stream [`Length`](./length) value. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int) | Saves (copies) the stream's data to the specified stream. Uses stream [`Length`](./length) value. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek)(long, SeekOrigin) | Sets the position within the current stream. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin)() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes)() | Converts the stream data to the Byte array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes)(long, long) | Converts the stream data to the Byte array. |
| virtual [Write](../../aspose.psd/streamcontainer/write)(byte[]) | Writes all of the specified bytes to the stream. |
| virtual [Write](../../aspose.psd/streamcontainer/write)(byte[], int, int) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte)(byte) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer) | Copies the contained data to another [`StreamContainer`](../streamcontainer). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer, long) | Copies the contained data to another [`StreamContainer`](../streamcontainer). |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit) | Performs an explicit conversion from [`StreamContainer`](../streamcontainer) to Stream. |

## Other Members

| Name | Description |
| --- | --- |
| const [ReadWriteBytesCount](readwritebytescount) | Specifies read and write bytes count when reading sequentially. |

### See Also

* class [DisposableObject](../disposableobject)
* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

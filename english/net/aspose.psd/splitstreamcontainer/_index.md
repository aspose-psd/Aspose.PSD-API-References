---
title: Class SplitStreamContainer
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.SplitStreamContainer class. Represents split stream container which contains the stream and provides stream processing routines
type: docs
weight: 6000
url: /net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Represents split stream container which contains the stream and provides stream processing routines.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructors

| Name | Description |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Initializes a new instance of the `SplitStreamContainer` class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Initializes a new instance of the `SplitStreamContainer` class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Initializes a new instance of the `SplitStreamContainer` class. |

## Properties

| Name | Description |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Gets a value indicating whether stream supports reading. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Gets a value indicating whether stream supports seeking. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Gets a value indicating whether stream supports writing. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Gets a value indicating whether this stream is disposed on close. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Gets or sets the stream length in bytes. This value is less than the Length by the starting stream position passed in the StreamContainer constructor. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Gets the data stream. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Gets an object that can be used to synchronize access to the synchronized resource. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Inserts the stream container into specified position. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Reads bytes to fill the specified bytes buffer. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) and stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) and stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Saves (copies) all the stream's data to the specified stream. Uses stream [`Length`](../streamcontainer/length/) value. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Saves (copies) the stream's data to the specified stream. Uses stream [`Length`](../streamcontainer/length/) value. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Saves (copies) the stream's data to the specified stream. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Sets the position within the current stream. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Converts the stream data to the Byte array. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Converts the stream data to the Byte array. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Writes all of the specified bytes to the stream. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Copies the contained data to another [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Copies the contained data to another [`StreamContainer`](../streamcontainer/). |

### See Also

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



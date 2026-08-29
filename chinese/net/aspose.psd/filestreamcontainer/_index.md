---
title: "类 FileStreamContainer"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileStreamContainer 类。用于文件流处理的辅助工具。"
type: docs
weight: 4720
url: /zh/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

文件流处理助手。

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | 获取一个值，指示流是否支持读取。 |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | 获取一个值，指示流是否支持定位。 |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | 获取一个值，指示流是否支持写入。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | 获取文件路径。 |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | 获取指示流是否显式创建的值。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，指示此流在关闭时是否被释放。 |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | 获取或设置指示流是否为临时的值。 |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | 获取或设置流的字节长度。该值比在 StreamContainer 构造函数中传入的起始流位置的 Length 小。 |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | 获取或设置流内的当前位置。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | 获取可用于同步对同步资源访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | 创建一个新的文件流。 |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | 打开一个已存在的文件流。如果文件流不存在，将抛出相应的异常。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | 清除此流的所有缓冲区，并导致任何缓冲数据写入底层设备。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | 从当前流读取一系列字节，并将流内的位置前移读取的字节数。 |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | 从流中读取一个字节，并将流内的位置前移一个字节；如果已到流末尾则返回 -1。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | 将整个流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | 将流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | 设置当前流中的位置。 |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | 将流的位置设置为流的起始位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | 将流数据转换为 Byte 数组。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | 将流数据转换为 Byte 数组。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | 将所有指定的字节写入流。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | 将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。 |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | 在流的当前位写入一个字节，并将流中的位置前移一个字节。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | 执行从 `FileStreamContainer` 到 Stream 的显式转换。（2 个运算符） |

### 另请参阅

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



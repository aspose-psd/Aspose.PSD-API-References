---
title: Class FileStreamContainer
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileStreamContainer 班级. 文件流处理助手.
type: docs
weight: 4250
url: /zh/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

文件流处理助手.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | 获取stream是否支持读取的值。 |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | 获取一个值，表示stream是否支持seeking。 |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | 获取stream是否支持写入的值。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | 获取文件路径. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | 获取一个值，指示是否显式创建了流。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，该值指示此流是否在关闭时被释放。 |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | 获取或设置一个值，指示流是否是临时的。 |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | 获取或设置以字节为单位的流长度。该值小于Length通过在 StreamContainer 构造函数中传递的起始流位置。 |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | 获取或设置流中的当前位置。此值表示从 StreamContainer 构造函数中传递的起始流位置的偏移量。 |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | 获取可用于同步访问同步资源的对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | 创建一个新的文件流。 |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | 打开现有文件流。如果文件流不存在，则抛出相应的异常。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | 清除此流的所有缓冲区并导致将任何缓冲数据写入基础设备。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | 从当前流中读取字节序列，并将流中的位置按读取的字节数前进。 |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | 从流中读取一个字节并将流中的位置前进一个字节，如果在流的末尾则返回 -1。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/)和流[`Length`](../streamcontainer/length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/)和流[`Length`](../streamcontainer/length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | 将所有流的数据保存（复制）到指定的流。使用流[`Length`](../streamcontainer/length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | 将流的数据保存（复制）到指定的流。使用流[`Length`](../streamcontainer/length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | 将流的数据保存（复制）到指定的流中。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | 将流的数据保存（复制）到指定的流中。 |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | 设置当前流中的位置。 |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | 将流位置设置为流的开头。此值表示从 StreamContainer 构造函数中传递的起始流位置的偏移量。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | 将流数据转换为Byte数组. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | 将流数据转换为Byte数组. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | 将所有指定字节写入流。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | 将字节序列写入当前流，并将该流中的当前位置前进写入的字节数。 |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | 将一个字节写入流中的当前位置并将流中的位置前进一个字节。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 将包含的数据复制到另一个[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 将包含的数据复制到另一个[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | 执行显式转换`FileStreamContainer`到Stream . (2 operators) |

### 也可以看看

* class [StreamContainer](../streamcontainer/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)



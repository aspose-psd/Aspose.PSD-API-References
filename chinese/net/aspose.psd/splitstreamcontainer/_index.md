---
title: "类 SplitStreamContainer"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.SplitStreamContainer 类。表示包含流并提供流处理例程的分割流容器"
type: docs
weight: 6130
url: /zh/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

表示分割流容器，包含流并提供流处理例程。

```csharp
public class SplitStreamContainer : StreamContainer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | 初始化 `SplitStreamContainer` 类的新实例。 |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | 初始化 `SplitStreamContainer` 类的新实例。 |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | 初始化 `SplitStreamContainer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | 获取一个值，指示流是否支持读取。 |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | 获取一个值，指示流是否支持定位。 |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | 获取一个值，指示流是否支持写入。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，指示此流在关闭时是否被释放。 |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | 获取或设置流的字节长度。该值比在 StreamContainer 构造函数中传入的起始流位置的 Length 小。 |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | 获取或设置流内的当前位置。该值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | 获取可用于同步对同步资源访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | 清除此流的所有缓冲区，并导致任何缓冲数据写入底层设备。 |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | 将流容器插入指定位置。 |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | 从当前流读取一系列字节，并将流内的位置前移读取的字节数。 |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | 从流中读取一个字节，并将流内的位置前移一个字节；如果已到流末尾则返回 -1。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小 [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 和流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | 将整个流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | 将流的数据保存（复制）到指定的流。使用流的 [`Length`](../streamcontainer/length/) 值。 |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | 将流的数据保存（复制）到指定的流。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | 将流的数据保存（复制）到指定的流。 |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | 设置当前流中的位置。 |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | 将流的位置设置为流的起始位置。此值表示相对于在 StreamContainer 构造函数中传入的起始流位置的偏移量。 |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | 将流数据转换为 Byte 数组。 |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | 将流数据转换为 Byte 数组。 |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | 将所有指定的字节写入流。 |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | 将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。 |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | 在流的当前位写入一个字节，并将流中的位置前移一个字节。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 将包含的数据复制到另一个 [`StreamContainer`](../streamcontainer/)。 |

### 另请参阅

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: Class StreamContainer
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.StreamContainer 班级. 表示流容器其中包含流并提供流处理例程
type: docs
weight: 5640
url: /zh/net/aspose.psd/streamcontainer/
---
## StreamContainer class

表示流容器，其中包含流并提供流处理例程。

```csharp
public class StreamContainer : DisposableObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | 初始化一个新的实例`StreamContainer`类. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | 初始化一个新的实例`StreamContainer`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | 获取stream是否支持读取的值。 |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | 获取一个值，表示stream是否支持seeking。 |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | 获取stream是否支持写入的值。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | 获取一个值，该值指示此流是否在关闭时被释放。 |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | 获取或设置以字节为单位的流长度。该值小于Length通过在 StreamContainer 构造函数中传递的起始流位置。 |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | 获取或设置流中的当前位置。此值表示从 StreamContainer 构造函数中传递的起始流位置的偏移量。 |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | 获取数据流。 |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | 获取可用于同步访问同步资源的对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | 清除此流的所有缓冲区并导致将任何缓冲数据写入基础设备。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | 读取字节以填充指定的字节缓冲区。 |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | 从当前流中读取字节序列，并将流中的位置按读取的字节数前进。 |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | 从流中读取一个字节并将流中的位置前进一个字节，如果在流的末尾则返回 -1。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小[`ReadWriteBytesCount`](./readwritebytescount/)和流[`Length`](./length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | 将流的数据保存（复制）到指定的流。使用默认缓冲区大小[`ReadWriteBytesCount`](./readwritebytescount/)和流[`Length`](./length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | 将所有流的数据保存（复制）到指定的流。使用流[`Length`](./length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | 将流的数据保存（复制）到指定的流。使用流[`Length`](./length/)值. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | 将流的数据保存（复制）到指定的流中。 |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | 将流的数据保存（复制）到指定的流中。 |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | 设置当前流中的位置。 |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | 将流位置设置为流的开头。此值表示从 StreamContainer 构造函数中传递的起始流位置的偏移量。 |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | 将流数据转换为Byte数组. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | 将流数据转换为Byte数组. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | 将所有指定字节写入流。 |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | 将字节序列写入当前流，并将该流中的当前位置前进写入的字节数。 |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | 将一个字节写入流中的当前位置并将流中的位置前进一个字节。 |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | 将包含的数据复制到另一个`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | 将包含的数据复制到另一个`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | 执行显式转换`StreamContainer`到Stream . |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | 指定顺序读取时的读写字节数。 |

### 也可以看看

* class [DisposableObject](../disposableobject/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)



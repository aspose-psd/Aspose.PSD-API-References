---
title: Class DataStreamSupporter
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.DataStreamSupporter 班级. 数据流容器
type: docs
weight: 740
url: /zh/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

数据流容器。

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 获取对象数据当前是否缓存，不需要读取数据的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层执行额外的数据加载[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | 将对象的数据保存到当前`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | 将对象的数据保存到指定的流中。 |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | 将对象的数据保存到指定的文件位置。 |

### 也可以看看

* class [DisposableObject](../disposableobject/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)



---
title: "类 DataStreamSupporter"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.DataStreamSupporter 类。数据流容器"
type: docs
weight: 750
url: /zh/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

数据流容器。

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](./datastreamcontainer/) 加载额外数据。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | 将对象的数据保存到当前 `DataStreamSupporter`。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | 将对象的数据保存到指定的流。 |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | 将对象的数据保存到指定的文件位置。 |

### 另请参阅

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



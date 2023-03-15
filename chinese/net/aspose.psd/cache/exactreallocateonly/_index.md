---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD for .NET API 参考
description: Cache 财产. 获取或设置一个值该值指示重新分配是否应该精确如果重新分配不准确性能应该更高
type: docs
weight: 50
url: /zh/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

获取或设置一个值，该值指示重新分配是否应该精确。如果重新分配不准确，性能应该更高。

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### 适当的价值

`真的`如果重新分配是准确的；否则，`错误的` .

### 评论

精确重新分配将执行额外内存的重新分配，直到指定的上限。 在重新分配期间超过内存中的上限时，缓存数据将尽可能复制到磁盘。 在重新分配期间超过磁盘内存的上限时抛出适当的异常。 如果关闭此选项，性能应该更高，因为如果可能，将不会执行额外的复制， 但这也可能导致通过为内存或磁盘指定的上限。

### 也可以看看

* class [Cache](../)
* 命名空间 [Aspose.PSD](../../cache/)
* 部件 [Aspose.PSD](../../../)



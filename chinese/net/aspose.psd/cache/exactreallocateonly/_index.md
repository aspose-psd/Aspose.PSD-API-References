---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD for .NET API 参考"
description: "Cache 属性。获取或设置一个值，指示重新分配是否应精确。如果重新分配不是精确的，性能应更高"
type: docs
weight: 50
url: /zh/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` 表示重新分配是精确的；否则为 `false`。

## 备注

精确重新分配将仅在指定的上限范围内执行额外内存的重新分配。当在重新分配期间为内存传递上限时，缓存数据将在可能的情况下复制到磁盘。当为磁盘内存传递上限进行重新分配时，将抛出相应的异常。如果关闭此选项，由于不会进行额外的复制，性能应更高，但这也可能导致超过为内存或磁盘指定的上限。

### 另请参阅

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



---
title: "类 Cache"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Cache 类。包含缓存设置"
type: docs
weight: 240
url: /zh/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

包含缓存设置。

```csharp
public static class Cache
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | 获取已分配的磁盘字节数。 |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | 获取已分配的内存字节数。 |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | 获取或设置缓存文件夹。 |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | 获取或设置使用的缓存方案。 |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | 获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。 |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | 获取或设置缓存的最大可用磁盘空间。指定的值为兆字节数。 |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | 获取或设置缓存在内存中的最大可用内存。指定的值为兆字节数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | 将 `Cache` 设置恢复为默认值。 |

## 示例

此示例演示了 Aspose.PSD.Cache 的使用

```csharp
[C#]

// 默认情况下，缓存文件夹设置为用户的本地临时目录。
// 您也可以指定除默认之外的其他缓存文件夹，如下所示：
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// 自动模式灵活且高效
Cache.CacheType = CacheType.Auto;

// 默认值为 0，表示没有上限
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
Cache.ExactReallocateOnly = false;

// 您可以随时检查当前为内存或磁盘分配了多少字节 
// 通过检查以下属性来了解缓存
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// 如下进行图像处理
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// 分配属性可用于检查所有 Aspose.PSD 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



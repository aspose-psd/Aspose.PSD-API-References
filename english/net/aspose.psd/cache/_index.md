---
title: Class Cache
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Cache class. Contains cache settings
type: docs
weight: 240
url: /net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Contains cache settings.

```csharp
public static class Cache
```

## Properties

| Name | Description |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Gets the allocated disk bytes count. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Gets the allocated in-memory bytes count. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Gets or sets the cache folder. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Gets or sets the cache scheme used. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Gets or sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Gets or sets the maximum available disk space for cache. The value specified is megabytes count. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Gets or sets the maximum available memory for cache in memory. The value specified is megabytes count. |

## Methods

| Name | Description |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Sets the `Cache` settings to defaults. |

## Examples

This example demonstrates the use of Aspose.PSD.Cache

```csharp
[C#]

// By default the cache folder is set to user's local temp directory.
// You can also specify another cache folder than default like the following:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Auto mode is flexible and efficient
Cache.CacheType = CacheType.Auto;

// Default value is 0, which means there is no upper limit
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// It is not recommended to change the following property as it may greatly affect the performance
Cache.ExactReallocateOnly = false;

// At any time you may check how many bytes currently allocated for memory or disk 
// cache by examining the following properties
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Do some image processing as below
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // after executing the code above there will be allocated 40000 bytes in-memory.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// The allocation properties may be used to check whether all Aspose.PSD objects were properly disposed.
// In case you've forgot to call dispose on some object the cache values will be different than 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



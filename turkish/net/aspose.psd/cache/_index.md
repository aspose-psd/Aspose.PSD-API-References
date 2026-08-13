---
title: "Sınıf Cache"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Cache sınıfı. Önbellek ayarlarını içerir"
type: docs
weight: 240
url: /tr/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Önbellek ayarlarını içerir.

```csharp
public static class Cache
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Ayrılan disk bayt sayısını alır. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Ayrılan bellek içi bayt sayısını alır. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Önbellek klasörünü alır veya ayarlar. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Kullanılan önbellek şemasını alır veya ayarlar. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Yeniden tahsislemenin tam olup olmadığını belirten bir değeri alır veya ayarlar. Yeniden tahsisleme tam değilse performans daha yüksek olmalıdır. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Önbellek için kullanılabilir maksimum disk alanını alır veya ayarlar. Belirtilen değer megabayt sayısıdır. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Önbellek için kullanılabilir maksimum bellek miktarını alır veya ayarlar. Belirtilen değer megabayt sayısıdır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | `Cache` ayarlarını varsayılanlara ayarlar. |

## Örnekler

Bu örnek Aspose.PSD.Cache kullanımını gösterir

```csharp
[C#]

// Varsayılan olarak önbellek klasörü kullanıcının yerel geçici dizinine ayarlanır.
// Aşağıdaki gibi varsayılandan farklı bir önbellek klasörü de belirtebilirsiniz:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Otomatik mod esnek ve etkilidir
Cache.CacheType = CacheType.Auto;

// Varsayılan değer 0'dır, bu da üst sınır olmadığı anlamına gelir
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Aşağıdaki özelliği değiştirmek önerilmez, çünkü performansı büyük ölçüde etkileyebilir
Cache.ExactReallocateOnly = false;

// Herhangi bir zamanda bellekte veya diskte şu anda ayrılan bayt sayısını kontrol edebilirsiniz
// aşağıdaki özellikleri inceleyerek önbelleği
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Aşağıdaki gibi bazı görüntü işleme işlemleri yapın
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // Yukarıdaki kod çalıştırıldıktan sonra bellekte 40000 bayt ayrılacaktır.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Tahsis özellikleri, tüm Aspose.PSD nesnelerinin düzgün bir şekilde serbest bırakılıp bırakılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde dispose çağırmayı unuttuğunuz takdirde önbellek değerleri 0'dan farklı olacaktır.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



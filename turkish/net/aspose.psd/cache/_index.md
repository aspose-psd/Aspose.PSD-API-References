---
title: Class Cache
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Cache sınıf. Önbellek ayarlarını içerir.
type: docs
weight: 240
url: /tr/net/aspose.psd/cache/
---
## Cache class

Önbellek ayarlarını içerir.

```csharp
public static class Cache
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Ayrılan disk bayt sayısını alır. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Ayrılan bellek içi bayt sayısını alır. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Önbellek klasörünü alır veya ayarlar. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Kullanılan önbellek düzenini alır veya ayarlar. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Yeniden tahsisin kesin olup olmayacağını belirten bir değer alır veya ayarlar. Yeniden tahsis kesin değilse performans daha yüksek olmalıdır. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Önbellek için kullanılabilir maksimum disk alanını alır veya ayarlar. Belirtilen değer megabayt sayısıdır. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Bellekteki önbellek için kullanılabilir maksimum belleği alır veya ayarlar. Belirtilen değer megabayt sayısıdır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | ayarlar`Cache` ayarları varsayılanlara. |

### Örnekler

Bu örnek, Aspose.PSD.Cache kullanımını göstermektedir.

```csharp
[C#]

// Önbellek klasörü varsayılan olarak kullanıcının yerel geçici dizinine ayarlanmıştır.
// Aşağıdaki gibi varsayılandan başka bir önbellek klasörü de belirleyebilirsiniz:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Otomatik mod esnek ve etkilidir
Cache.CacheType = CacheType.Auto;

// Varsayılan değer 0'dır, yani üst sınır yoktur
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabayt
Cache.MaxMemoryForCache = 1073741824; // 1 gigabayt

// Performansı büyük ölçüde etkileyebileceği için aşağıdaki özelliğin değiştirilmesi önerilmez.
Cache.ExactReallocateOnly = false;

// İstediğiniz zaman bellek veya disk için kaç bayt tahsis edildiğini kontrol edebilirsiniz. 
// aşağıdaki özellikleri inceleyerek önbelleğe alın
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Aşağıdaki gibi bazı görüntü işlemeleri yapın
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // yukarıdaki kodu çalıştırdıktan sonra bellekte 40000 bayt ayrılacak.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Tahsisat özellikleri, tüm Aspose.PSD nesnelerinin uygun şekilde atılıp atılmadığını kontrol etmek için kullanılabilir.
// Bazı nesnelerde Dispose'u çağırmayı unuttuysanız, önbellek değerleri 0'dan farklı olacaktır.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)



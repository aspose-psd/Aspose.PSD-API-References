---
title: "Kelas Cache"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Cache. Berisi pengaturan cache"
type: docs
weight: 240
url: /id/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Berisi pengaturan cache.

```csharp
public static class Cache
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Mendapatkan jumlah byte disk yang dialokasikan. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Mendapatkan jumlah byte memori yang dialokasikan. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Mendapatkan atau mengatur folder cache. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Mendapatkan atau mengatur skema cache yang digunakan. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah alokasi ulang harus tepat atau tidak. Jika alokasi ulang tidak tepat, kinerja seharusnya lebih tinggi. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Mendapatkan atau mengatur ruang disk maksimum yang tersedia untuk cache. Nilai yang ditentukan adalah jumlah megabyte. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Mendapatkan atau mengatur memori maksimum yang tersedia untuk cache di memori. Nilai yang ditentukan adalah jumlah megabyte. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Mengatur pengaturan `Cache` ke nilai default. |

## Contoh

Contoh ini menunjukkan penggunaan Aspose.PSD.Cache

```csharp
[C#]

// Secara default folder cache diatur ke direktori temp lokal pengguna.
// Anda juga dapat menentukan folder cache lain selain default seperti berikut:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Mode otomatis fleksibel dan efisien
Cache.CacheType = CacheType.Auto;

// Nilai default adalah 0, yang berarti tidak ada batas atas
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Tidak disarankan mengubah properti berikut karena dapat sangat memengaruhi kinerja
Cache.ExactReallocateOnly = false;

// Kapan saja Anda dapat memeriksa berapa byte yang saat ini dialokasikan untuk memori atau disk
// cache dengan memeriksa properti berikut
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Lakukan beberapa pemrosesan gambar seperti di bawah ini
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // setelah mengeksekusi kode di atas akan dialokasikan 40000 byte di memori.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Properti alokasi dapat digunakan untuk memeriksa apakah semua objek Aspose.PSD telah dibuang dengan benar.
// Jika Anda lupa memanggil dispose pada suatu objek, nilai cache akan berbeda dari 0.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: Class Cache
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Cache kelas. Berisi pengaturan cache.
type: docs
weight: 240
url: /id/net/aspose.psd/cache/
---
## Cache class

Berisi pengaturan cache.

```csharp
public static class Cache
```

## Properti

| Nama | Keterangan |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Mendapat jumlah byte disk yang dialokasikan. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Mendapat jumlah byte dalam memori yang dialokasikan. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Mendapat atau menyetel folder cache. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Mendapat atau menyetel skema cache yang digunakan. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah realokasi harus tepat atau tidak. Jika realokasi tidak tepat, kinerjanya harus lebih tinggi. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Mendapat atau menyetel ruang disk maksimum yang tersedia untuk cache. Nilai yang ditentukan adalah hitungan megabita. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Mendapat atau mengatur memori maksimum yang tersedia untuk cache di memori. Nilai yang ditentukan adalah hitungan megabita. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Mengatur`Cache` pengaturan ke default. |

### Contoh

Contoh ini menunjukkan penggunaan Aspose.PSD.Cache

```csharp
[C#]

// Secara default folder cache diatur ke direktori temp lokal pengguna.
// Anda juga dapat menentukan folder cache lain selain default seperti berikut:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Mode otomatis fleksibel dan efisien
Cache.CacheType = CacheType.Auto;

// Nilai default adalah 0, artinya tidak ada batas atas
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabita
Cache.MaxMemoryForCache = 1073741824; // 1 gigabita

// Tidak disarankan untuk mengubah properti berikut karena dapat sangat memengaruhi kinerja
Cache.ExactReallocateOnly = false;

// Setiap saat Anda dapat memeriksa berapa banyak byte yang saat ini dialokasikan untuk memori atau disk 
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

    // setelah mengeksekusi kode di atas akan dialokasikan 40000 byte dalam memori.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Properti alokasi dapat digunakan untuk memeriksa apakah semua objek Aspose.PSD telah dibuang dengan benar.
// Jika Anda lupa memanggil buang pada beberapa objek, nilai cache akan berbeda dari 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)



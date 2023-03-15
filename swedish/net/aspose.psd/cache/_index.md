---
title: Class Cache
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Cache klass. Innehåller cacheinställningar.
type: docs
weight: 240
url: /sv/net/aspose.psd/cache/
---
## Cache class

Innehåller cacheinställningar.

```csharp
public static class Cache
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Hämtar antalet tilldelade diskbytes. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Hämtar antalet tilldelade byte i minnet. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Hämtar eller ställer in cachemappen. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Hämtar eller ställer in cacheschemat som används. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Hämtar eller sätter ett värde som indikerar om omfördelningen ska vara exakt eller inte. Om omfördelningen inte är exakt bör prestandan vara högre. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Hämtar eller ställer in maximalt tillgängligt diskutrymme för cache. Det angivna värdet är megabyte count. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Hämtar eller ställer in maximalt tillgängligt minne för cache i minnet. Det angivna värdet är megabyte count. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Ställer in`Cache` inställningar till standardvärden. |

### Exempel

Detta exempel visar användningen av Aspose.PSD.Cache

```csharp
[C#]

// Som standard är cachemappen inställd på användarens lokala temporära katalog.
// Du kan också ange en annan cachemapp än standard som följande:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Autoläget är flexibelt och effektivt
Cache.CacheType = CacheType.Auto;

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom det i hög grad kan påverka prestandan
Cache.ExactReallocateOnly = false;

// Du kan när som helst kontrollera hur många byte som för närvarande är allokerade för minne eller disk 
// cache genom att undersöka följande egenskaper
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Gör lite bildbearbetning enligt nedan
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // efter exekvering av koden ovan kommer det att tilldelas 40000 byte i minnet.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Allokeringsegenskaperna kan användas för att kontrollera om alla Aspose.PSD-objekt var korrekt bortskaffade.
// Om du har glömt att anropa dispose på något objekt kommer cachevärdena att vara annorlunda än 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)



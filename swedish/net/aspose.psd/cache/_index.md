---
title: "Klass Cache"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Cache klass. Innehåller cacheinställningar."
type: docs
weight: 240
url: /sv/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Innehåller cacheinställningar.

```csharp
public static class Cache
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Hämtar antalet allokerade diskbyte. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Hämtar antalet allokerade minnesbyte. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Hämtar eller anger cache‑mappen. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Hämtar eller anger det använda cache‑schemat. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Hämtar eller anger ett värde som indikerar om omallokering ska vara exakt eller inte. Om omallokering inte är exakt bör prestandan vara högre. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Hämtar eller anger det maximala tillgängliga diskutrymmet för cache. Det angivna värdet är antalet megabyte. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Hämtar eller anger det maximala tillgängliga minnet för cache i minnet. Det angivna värdet är antalet megabyte. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Anger `Cache`‑inställningarna till standardvärden. |

## Exempel

Detta exempel demonstrerar användningen av Aspose.PSD.Cache

```csharp
[C#]

// Som standard är cache‑mappen inställd på användarens lokala temp‑katalog.
// Du kan också ange en annan cache‑mapp än standard, som följer:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Auto‑läget är flexibelt och effektivt
Cache.CacheType = CacheType.Auto;

// Standardvärdet är 0, vilket betyder att det inte finns någon övre gräns
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Det rekommenderas inte att ändra följande egenskap eftersom det kan påverka prestandan avsevärt
Cache.ExactReallocateOnly = false;

// När som helst kan du kontrollera hur många byte som för närvarande är allokerade för minne eller disk
// cachen genom att undersöka följande egenskaper
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Utför lite bildbehandling enligt nedan
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // Efter att ha kört koden ovan kommer 40000 byte att allokeras i minnet.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Allokerings‑egenskaperna kan användas för att kontrollera om alla Aspose.PSD‑objekt har frigjorts korrekt.
// Om du har glömt att anropa dispose på något objekt kommer cache‑värdena att vara olika från 0.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: Class Cache
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Cache klas. Bevat cacheinstellingen.
type: docs
weight: 240
url: /nl/net/aspose.psd/cache/
---
## Cache class

Bevat cache-instellingen.

```csharp
public static class Cache
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Haalt het aantal toegewezen schijfbytes op. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Haalt het toegewezen aantal bytes in het geheugen op. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Haalt de cachemap op of stelt deze in. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Haalt of stelt het gebruikte cacheschema in. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Haalt of stelt een waarde in die aangeeft of hertoewijzing exact moet zijn of niet. Als hertoewijzing niet exact is, zouden de prestaties hoger moeten zijn. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Haalt de maximaal beschikbare schijfruimte voor cache op of stelt deze in. De opgegeven waarde is het aantal megabytes. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Haalt of stelt het maximaal beschikbare geheugen voor cache in het geheugen in. De opgegeven waarde is het aantal megabytes. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Stelt de`Cache` instellingen naar standaardwaarden. |

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van Aspose.PSD.Cache

```csharp
[C#]

// Standaard is de cachemap ingesteld op de lokale tijdelijke map van de gebruiker.
// U kunt ook een andere cachemap opgeven dan standaard, zoals het volgende:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// De automatische modus is flexibel en efficiënt
Cache.CacheType = CacheType.Auto;

// De standaardwaarde is 0, wat betekent dat er geen bovengrens is
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Het wordt niet aanbevolen om de volgende eigenschap te wijzigen, omdat dit de prestaties sterk kan beïnvloeden
Cache.ExactReallocateOnly = false;

// U kunt op elk moment controleren hoeveel bytes momenteel zijn toegewezen voor geheugen of schijf 
// cache door de volgende eigenschappen te onderzoeken
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Voer wat beeldverwerking uit zoals hieronder
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // na het uitvoeren van de bovenstaande code wordt er 40.000 bytes in het geheugen toegewezen.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// De toewijzingseigenschappen kunnen worden gebruikt om te controleren of alle Aspose.PSD-objecten correct zijn verwijderd.
// In het geval dat u bent vergeten om een object te bellen, zullen de cachewaarden anders zijn dan 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)



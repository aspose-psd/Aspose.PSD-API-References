---
title: Class Cache
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Cache classe. Contiene le impostazioni della cache.
type: docs
weight: 240
url: /it/net/aspose.psd/cache/
---
## Cache class

Contiene le impostazioni della cache.

```csharp
public static class Cache
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Ottiene il conteggio dei byte del disco allocati. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Ottiene il conteggio dei byte in memoria allocati. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Ottiene o imposta la cartella della cache. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Ottiene o imposta lo schema di cache utilizzato. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Ottiene o imposta un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta, le prestazioni dovrebbero essere superiori. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Ottiene o imposta lo spazio su disco massimo disponibile per la cache. Il valore specificato è conteggio megabyte. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Ottiene o imposta la memoria massima disponibile per la cache in memoria. Il valore specificato è conteggio megabyte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Imposta il`Cache` impostazioni predefinite. |

### Esempi

Questo esempio dimostra l'utilizzo di Aspose.PSD.Cache

```csharp
[C#]

// Per impostazione predefinita, la cartella della cache è impostata sulla directory temporanea locale dell'utente.
// Puoi anche specificare un'altra cartella della cache rispetto a quella predefinita come la seguente:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// La modalità automatica è flessibile ed efficiente
Cache.CacheType = CacheType.Auto;

// Il valore predefinito è 0, il che significa che non esiste un limite massimo
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Non è consigliabile modificare la seguente proprietà in quanto potrebbe influire notevolmente sulle prestazioni
Cache.ExactReallocateOnly = false;

// In qualsiasi momento puoi controllare quanti byte sono attualmente allocati per la memoria o il disco 
// cache esaminando le seguenti proprietà
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Esegui l'elaborazione delle immagini come di seguito
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // dopo aver eseguito il codice sopra, verranno allocati 40000 byte in memoria.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Le proprietà di allocazione possono essere utilizzate per controllare se tutti gli oggetti Aspose.PSD sono stati disposti correttamente.
// Nel caso in cui ti sei dimenticato di chiamare dispose su qualche oggetto, i valori della cache saranno diversi da 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)



---
title: Class Cache
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Cache klas. Enthält CacheEinstellungen.
type: docs
weight: 240
url: /de/net/aspose.psd/cache/
---
## Cache class

Enthält Cache-Einstellungen.

```csharp
public static class Cache
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Ruft die Anzahl der zugewiesenen Festplattenbytes ab. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Ruft die Anzahl der zugewiesenen In-Memory-Bytes ab. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Ruft den Cache-Ordner ab oder legt ihn fest. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Ruft das verwendete Cache-Schema ab oder legt es fest. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Neuzuweisung genau sein soll oder nicht. Wenn die Neuzuweisung nicht exakt ist, sollte die Leistung höher sein. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Ruft den maximal verfügbaren Speicherplatz für den Cache ab oder legt ihn fest. Der angegebene Wert ist Megabyte count. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Ruft den maximal verfügbaren Speicher für den Cache im Speicher ab oder legt ihn fest. Der angegebene Wert ist Megabyte count. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Legt die fest`Cache` Einstellungen auf Standardwerte zurücksetzen. |

### Beispiele

Dieses Beispiel demonstriert die Verwendung von Aspose.PSD.Cache

```csharp
[C#]

// Standardmäßig ist der Cache-Ordner auf das lokale temporäre Verzeichnis des Benutzers eingestellt.
// Sie können auch einen anderen Cache-Ordner als den Standard wie folgt angeben:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Der Auto-Modus ist flexibel und effizient
Cache.CacheType = CacheType.Auto;

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt
Cache.MaxDiskSpaceForCache = 1073741824; // 1 Gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 Gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da dies die Leistung stark beeinträchtigen kann
Cache.ExactReallocateOnly = false;

// Sie können jederzeit überprüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind 
// zwischenspeichern, indem Sie die folgenden Eigenschaften untersuchen
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Führen Sie eine Bildverarbeitung wie unten durch
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // Nach Ausführung des obigen Codes werden 40000 Bytes im Speicher zugewiesen.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Die Zuordnungseigenschaften können verwendet werden, um zu prüfen, ob alle Aspose.PSD-Objekte ordnungsgemäß verworfen wurden.
// Falls Sie vergessen haben, dispose für ein Objekt aufzurufen, werden die Cache-Werte von 0 abweichen.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)



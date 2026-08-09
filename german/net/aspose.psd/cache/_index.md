---
title: "Class Cache"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Cache class. Enthält Cache-Einstellungen."
type: docs
weight: 240
url: /de/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Enthält Cache‑Einstellungen.

```csharp
public static class Cache
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Gibt die Anzahl der zugewiesenen Festplattenbytes zurück. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Gibt die Anzahl der zugewiesenen In-Memory-Bytes zurück. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Liest oder setzt den Cache-Ordner. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Liest oder setzt das verwendete Cache-Schema. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. Wenn die Neuallokation nicht exakt ist, sollte die Leistung höher sein. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Liest oder setzt den maximal verfügbaren Festplattenspeicher für den Cache. Der angegebene Wert ist die Megabyte-Anzahl. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Liest oder setzt den maximal verfügbaren Speicher für den Cache im Arbeitsspeicher. Der angegebene Wert ist die Megabyte‑Anzahl. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Setzt die `Cache`‑Einstellungen auf die Standardwerte. |

## Beispiele

Dieses Beispiel demonstriert die Verwendung von Aspose.PSD.Cache

```csharp
[C#]

// Standardmäßig ist der Cache‑Ordner auf das lokale Temp‑Verzeichnis des Benutzers gesetzt.
// Sie können auch einen anderen Cache‑Ordner als den Standard angeben, wie im Folgenden:
// Cache.CacheFolder = @\"D:\\\\MyTemp\";

string path = "C:\\temp\\image.psd";

// Der Auto‑Modus ist flexibel und effizient
Cache.CacheType = CacheType.Auto;

// Der Standardwert ist 0, was bedeutet, dass es keine Obergrenze gibt
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Es wird nicht empfohlen, die folgende Eigenschaft zu ändern, da sie die Leistung stark beeinflussen kann
Cache.ExactReallocateOnly = false;

// Sie können jederzeit prüfen, wie viele Bytes derzeit für Speicher oder Festplatte zugewiesen sind
// Cache, indem Sie die folgenden Eigenschaften untersuchen.
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Führen Sie die nachstehende Bildverarbeitung aus
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // Nach der Ausführung des obigen Codes werden 40000 Bytes im Arbeitsspeicher zugewiesen.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Die Zuweisungseigenschaften können verwendet werden, um zu prüfen, ob alle Aspose.PSD‑Objekte ordnungsgemäß freigegeben wurden.
// Falls Sie vergessen haben, bei einem Objekt dispose aufzurufen, werden die Cache‑Werte von 0 abweichen.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



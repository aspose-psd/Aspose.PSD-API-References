---
title: Enum CompressionMethod
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.CompressionMethod opsomming. Definiert die für Bilddaten verwendete Komprimierungsmethode.
type: docs
weight: 1620
url: /de/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Definiert die für Bilddaten verwendete Komprimierungsmethode.

```csharp
public enum CompressionMethod : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Raw | `0` | Keine Komprimierung. Die Bilddaten werden als Rohbytes in planarer RGBA-Reihenfolge gespeichert. Das bedeutet, dass zuerst alle R-Daten geschrieben werden, dann alle G-Daten geschrieben werden, dann alle B- und schließlich alle A-Daten geschrieben werden. |
| RLE | `1` | RLE-komprimiert beginnen die Bilddaten mit den Byte-Zählungen für alle Abtastzeilen (Zeilen * Kanäle), wobei jede -Zählung als Zwei-Byte-Wert gespeichert wird. Die RLE-komprimierten Daten folgen, wobei jede Abtastzeile separat komprimiert wird. Die RLE-Komprimierung ist derselbe Komprimierungsalgorithmus, der von der Macintosh-ROM-Routine PackBits und dem TIFF-Standard verwendet wird. |
| ZipWithoutPrediction | `2` | PLZ ohne Vorhersage. |
| ZipWithPrediction | `3` | PLZ mit Vorhersage. |

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Montage [Aspose.PSD](../../)



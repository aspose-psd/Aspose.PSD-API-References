---
title: "Enum CompressionMethod"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod Enum. Definiert die Komprimierungsmethode, die für Bilddaten verwendet wird."
type: docs
weight: 1630
url: /de/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Definiert die Komprimierungsmethode, die für Bilddaten verwendet wird.

```csharp
public enum CompressionMethod : short
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Raw | `0` | Keine Kompression. Die Bilddaten werden als Rohbytes in RGBA-Planarreihenfolge gespeichert. Das bedeutet, dass zuerst alle R‑Daten geschrieben werden, dann alle G‑Daten, anschließend alle B‑Daten und schließlich alle A‑Daten. |
| RLE | `1` | RLE‑komprimierte Bilddaten beginnen mit den Byte‑Zählungen für alle Scan‑Zeilen (Zeilen * Kanäle), wobei jede Zählung als Zweibyte‑Wert gespeichert wird. Es folgen die RLE‑komprimierten Daten, wobei jede Scan‑Zeile separat komprimiert wird. Die RLE‑Kompression ist derselbe Kompressionsalgorithmus, der von der Macintosh‑ROM‑Routine PackBits und dem TIFF‑Standard verwendet wird. |
| ZipWithoutPrediction | `2` | ZIP ohne Vorhersage. |
| ZipWithPrediction | `3` | ZIP mit Vorhersage. |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)



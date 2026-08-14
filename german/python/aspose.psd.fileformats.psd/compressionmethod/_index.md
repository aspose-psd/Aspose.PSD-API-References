---
title: "CompressionMethod Aufzählung"
type: docs
weight: 2410
url: /de/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Definiert die Komprimierungsmethode, die für Bilddaten verwendet wird.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Membername** | **Beschreibung** |
| :- | :- |
| RAW | Keine Kompression. Die Bilddaten werden als Rohbytes in RGBA‑planarer Reihenfolge gespeichert.<br/>            Das bedeutet, dass zuerst alle R‑Daten geschrieben werden, dann alle G‑Daten, anschließend alle B‑Daten und schließlich alle A‑Daten. |
| RLE | RLE komprimierte Bilddaten beginnen mit den Byte‑Zählungen für alle Scan‑Zeilen (Zeilen * Kanäle), wobei jede<br/>            Zählung als Zweibyte‑Wert gespeichert wird. Die RLE‑komprimierten Daten folgen, wobei jede Scan‑Zeile separat komprimiert wird.<br/>            Die RLE‑Kompression ist derselbe Kompressionsalgorithmus, der von der Macintosh‑ROM‑Routine PackBits und dem TIFF‑Standard verwendet wird. |
| ZIP_WITHOUT_PREDICTION | ZIP ohne Vorhersage. |
| ZIP_WITH_PREDICTION | ZIP mit Vorhersage. |

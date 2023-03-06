---
title: Enum CompressionMethod
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.CompressionMethod uppräkning. Definierar komprimeringsmetoden som används för bilddata.
type: docs
weight: 1620
url: /sv/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Definierar komprimeringsmetoden som används för bilddata.

```csharp
public enum CompressionMethod : short
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Raw | `0` | Ingen komprimering. Bilddata som lagras som råbyte i RGBA plan ordning. Det betyder att först skrivs all R-data, sedan skrivs all G, sedan skrivs all B och slutligen all A-data. |
| RLE | `1` | RLE komprimerat bilddatan börjar med byte-antalet för alla skanningslinjer (rader * kanaler), med varje -antal lagrat som ett två-byte-värde. RLE-komprimerade data följer, med varje skanningslinje komprimerad separat. RLE-komprimeringen är samma komprimeringsalgoritm som används av Macintosh ROM-rutinen PackBits och TIFF-standarden. |
| ZipWithoutPrediction | `2` | ZIP utan förutsägelse. |
| ZipWithPrediction | `3` | ZIP med förutsägelse. |

### Se även

* namnutrymme [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* hopsättning [Aspose.PSD](../../)



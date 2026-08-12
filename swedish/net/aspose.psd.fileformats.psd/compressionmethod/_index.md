---
title: "Enum CompressionMethod"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod enum. Definierar komprimeringsmetoden som används för bilddata"
type: docs
weight: 1630
url: /sv/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Definierar komprimeringsmetoden som används för bilddata.

```csharp
public enum CompressionMethod : short
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Raw | `0` | Ingen komprimering. Bilddata lagras som råa byte i RGBA-planarordning. Det betyder att först all R-data skrivs, sedan all G-data, sedan all B och slutligen all A-data skrivs. |
| RLE | `1` | RLE-komprimerad bilddata börjar med byteantalet för alla skanningslinjer (rader * kanaler), där varje antal lagras som ett tvåbytevärde. Den RLE-komprimerade datan följer, där varje skanningslinje komprimeras separat. RLE-komprimeringen är samma komprimeringsalgoritm som används av Macintosh ROM‑rutinen PackBits och TIFF‑standarden. |
| ZipWithoutPrediction | `2` | ZIP utan prediktion. |
| ZipWithPrediction | `3` | ZIP med prediktion. |

### Se även

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)



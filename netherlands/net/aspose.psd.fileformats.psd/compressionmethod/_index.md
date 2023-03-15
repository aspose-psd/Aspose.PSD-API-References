---
title: Enum CompressionMethod
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.CompressionMethod opsomming. Definieert de compressiemethode die wordt gebruikt voor afbeeldingsgegevens.
type: docs
weight: 1620
url: /nl/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Definieert de compressiemethode die wordt gebruikt voor afbeeldingsgegevens.

```csharp
public enum CompressionMethod : short
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Raw | `0` | Geen compressie. De afbeeldingsgegevens worden opgeslagen als onbewerkte bytes in RGBA-planaire volgorde. Dat betekent dat eerst alle R-gegevens worden geschreven, vervolgens alle G-gegevens, vervolgens alle B-gegevens en ten slotte alle A-gegevens. |
| RLE | `1` | RLE gecomprimeerd de beeldgegevens beginnen met de bytetellingen voor alle scanlijnen (rijen * kanalen), waarbij elke telling wordt opgeslagen als een waarde van twee bytes. De RLE-gecomprimeerde gegevens volgen, waarbij elke scanregel afzonderlijk wordt gecomprimeerd. De RLE-compressie is hetzelfde compressie-algoritme dat wordt gebruikt door de Macintosh ROM-routine PackBits en de TIFF-standaard. |
| ZipWithoutPrediction | `2` | ZIP zonder voorspelling. |
| ZipWithPrediction | `3` | ZIP met voorspelling. |

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* montage [Aspose.PSD](../../)



---
title: "CompressionMethod Enumeratie"
type: docs
weight: 2410
url: /nl/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Definieert de compressiemethode die wordt gebruikt voor afbeeldingsgegevens.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Lidnaam** | **Beschrijving** |
| :- | :- |
| RAW | Geen compressie. De afbeeldingsgegevens worden opgeslagen als ruwe bytes in RGBA-planairorde.<br/>            Dat betekent dat eerst alle R-gegevens worden geschreven, daarna alle G-gegevens, vervolgens alle B en tenslotte alle A-gegevens. |
| RLE | RLE-gecomprimeerde afbeeldingsgegevens beginnen met de byte-aantallen voor alle scanlijnen (rijen * kanalen), waarbij elke<br/>            telling wordt opgeslagen als een twee-byte waarde. De RLE-gecomprimeerde gegevens volgen, waarbij elke scanlijn afzonderlijk wordt gecomprimeerd.<br/>            De RLE-compressie is hetzelfde compressie-algoritme dat wordt gebruikt door de Macintosh ROM-routine PackBits en de TIFF-standaard. |
| ZIP_WITHOUT_PREDICTION | ZIP zonder voorspelling. |
| ZIP_WITH_PREDICTION | ZIP met voorspelling. |

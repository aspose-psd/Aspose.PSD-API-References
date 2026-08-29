---
title: "CompressionMethod uppräkning"
type: docs
weight: 2410
url: /sv/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Definierar komprimeringsmetoden som används för bilddata.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Medlemsnamn** | **Beskrivning** |
| :- | :- |
| RAW | Ingen komprimering. Bilddata lagras som råa byte i RGBA‑planarordning.<br/>            Det betyder att först all R‑data skrivs, sedan all G‑data, därefter all B‑data och slutligen all A‑data skrivs. |
| RLE | RLE‑komprimerad bilddata börjar med byteantalet för alla skanningslinjer (rader * kanaler), där varje<br/>            antal lagras som ett tvåbytevärde. De RLE‑komprimerade data följer, där varje skanningslinje komprimeras separat.<br/>            RLE‑komprimeringen är samma komprimeringsalgoritm som används av Macintosh ROM‑rutinen PackBits och TIFF‑standarden. |
| ZIP_WITHOUT_PREDICTION | ZIP utan prediktion. |
| ZIP_WITH_PREDICTION | ZIP med prediktion. |

---
title: "SampleRoundingMode enumeration"
type: docs
weight: 70
url: /sv/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Definierar ett sätt på vilket ett n-bitars värde konverteras till ett 8-bitars värde.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Medlemsnamn** | **Beskrivning** |
| :- | :- |
| EXTRAPOLATE | Extrapolera ett 8-bitars värde för att passa det i n bitar, där 1 < n < 8.<br/>            Antalet möjliga 8-bitars värden är 1 << 8 = 256, från 0 till 255.<br/>            Antalet möjliga n-bitars värden är 1 << n, från 0 till (1 << n) - 1.<br/>            Det mest rimliga n-bitars värdet Vn som motsvarar ett 8-bitars värde V8 är lika med Vn = V8 >> (8 - n). |
| TRUNCATE | Trunkera ett 8-bitars värde för att passa det i n bitar, där 1 < n < 8.<br/>            Antalet möjliga n-bitars värden är 1 << n, från 0 till (1 << n) - 1.<br/>            Det mest rimliga n-bitars värdet Vn som motsvarar ett 8-bitars värde V8 är lika med Vn = V8 & ((1 << n) - 1). |

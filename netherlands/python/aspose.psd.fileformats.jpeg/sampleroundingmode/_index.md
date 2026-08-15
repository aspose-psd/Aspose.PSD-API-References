---
title: "SampleRoundingMode-enumeratie"
type: docs
weight: 70
url: /nl/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Definieert een manier waarop een n-bit waarde wordt omgezet naar een 8-bit waarde.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Lidnaam** | **Beschrijving** |
| :- | :- |
| EXTRAPOLATE | Extrapoleer een 8‑bitwaarde zodat deze past in n bits, waarbij 1 &lt; n &lt; 8.<br/>            Het aantal mogelijke 8‑bitwaarden is 1 &lt;&lt; 8 = 256, van 0 tot 255.<br/>            Het aantal mogelijke n‑bitwaarden is 1 &lt;&lt; n, van 0 tot (1 &lt;&lt; n) - 1.<br/>            De meest redelijke n‑bitwaarde Vn die overeenkomt met een 8‑bitwaarde V8 is gelijk aan Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Afkappen van een 8‑bitwaarde zodat deze past in n bits, waarbij 1 &lt; n &lt; 8.<br/>            Het aantal mogelijke n‑bitwaarden is 1 &lt;&lt; n, van 0 tot (1 &lt;&lt; n) - 1.<br/>            De meest redelijke n‑bitwaarde Vn die overeenkomt met een 8‑bitwaarde V8 is gelijk aan Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

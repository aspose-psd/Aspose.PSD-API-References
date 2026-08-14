---
title: "Enumerazione SampleRoundingMode"
type: docs
weight: 70
url: /it/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Definisce un modo in cui un valore n-bit viene convertito in un valore a 8-bit.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nome membro** | **Description** |
| :- | :- |
| EXTRAPOLATE | Estrapola un valore a 8 bit per adattarlo a n bit, dove 1 &lt; n &lt; 8.<br/>            Il numero di tutti i possibili valori a 8 bit è 1 &lt;&lt; 8 = 256, da 0 a 255.<br/>            Il numero di tutti i possibili valori a n bit è 1 &lt;&lt; n, da 0 a (1 &lt;&lt; n) - 1.<br/>            Il valore a n bit più ragionevole Vn corrispondente a un valore a 8 bit V8 è uguale a Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Tronca un valore a 8 bit per adattarlo a n bit, dove 1 &lt; n &lt; 8.<br/>            Il numero di tutti i possibili valori a n bit è 1 &lt;&lt; n, da 0 a (1 &lt;&lt; n) - 1.<br/>            Il valore a n bit più ragionevole Vn corrispondente a un valore a 8 bit V8 è uguale a Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

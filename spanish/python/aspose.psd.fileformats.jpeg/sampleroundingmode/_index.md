---
title: "Enumeración SampleRoundingMode"
type: docs
weight: 70
url: /es/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Define una forma en que un valor de n bits se convierte a un valor de 8 bits.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Descripción** |
| :- | :- |
| EXTRAPOLATE | Extrapola un valor de 8 bits para ajustarlo a n bits, donde 1 &lt; n &lt; 8.<br/>            El número de todos los valores posibles de 8 bits es 1 &lt;&lt; 8 = 256, de 0 a 255.<br/>            El número de todos los valores posibles de n bits es 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1.<br/>            El valor de n bits más razonable Vn que corresponde a un valor de 8 bits V8 es igual a Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Trunca un valor de 8 bits para ajustarlo a n bits, donde 1 &lt; n &lt; 8.<br/>            El número de todos los valores posibles de n bits es 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1.<br/>            El valor de n bits más razonable Vn que corresponde a un valor de 8 bits V8 es igual a Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

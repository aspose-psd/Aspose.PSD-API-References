---
title: SampleRoundingMode Enumeration
type: docs
weight: 70
url: /python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Defines a way in which an n-bit value is converted to an 8-bit value.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.6.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EXTRAPOLATE | Extrapolate an 8-bit value to fit it into n bits, where 1 &lt; n &lt; 8.<br/>            The number of all possible 8-bit values is 1 &lt;&lt; 8 = 256, from 0 to 255.<br/>            The number of all possible n-bit values is 1 &lt;&lt; n, from 0 to (1 &lt;&lt; n) - 1.<br/>            The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Truncate an 8-bit value to fit it into n bits, where 1 &lt; n &lt; 8.<br/>            The number of all possible n-bit values is 1 &lt;&lt; n, from 0 to (1 &lt;&lt; n) - 1.<br/>            The most reasonable n-bit value Vn corresponding to some 8-bit value V8 is equal to Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

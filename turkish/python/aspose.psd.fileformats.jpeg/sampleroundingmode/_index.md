---
title: "SampleRoundingMode Enümerasyonu"
type: docs
weight: 70
url: /tr/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

n-bit değerinin 8-bit değere dönüştürülme şeklini tanımlar.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| EXTRAPOLATE | 8-bit bir değeri n bitine sığacak şekilde ekstrapole eder, burada 1 &lt; n &lt; 8.<br/>            Tüm olası 8-bit değerlerin sayısı 1 &lt;&lt; 8 = 256'dır, 0'dan 255'e.<br/>            Tüm olası n-bit değerlerin sayısı 1 &lt;&lt; n'dir, 0'dan (1 &lt;&lt; n) - 1'e.<br/>            Bazı 8-bit değer V8'e karşılık gelen en mantıklı n-bit değer Vn, Vn = V8 &gt;&gt; (8 - n) eşittir. |
| TRUNCATE | 8-bit bir değeri n bitine sığacak şekilde kırpar, burada 1 &lt; n &lt; 8.<br/>            Tüm olası n-bit değerlerin sayısı 1 &lt;&lt; n'dir, 0'dan (1 &lt;&lt; n) - 1'e.<br/>            Bazı 8-bit değer V8'e karşılık gelen en mantıklı n-bit değer Vn, Vn = V8 &amp; ((1 &lt;&lt; n) - 1) eşittir. |

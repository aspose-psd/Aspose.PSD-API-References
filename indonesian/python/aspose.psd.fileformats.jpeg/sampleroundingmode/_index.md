---
title: "Enumerasi SampleRoundingMode"
type: docs
weight: 70
url: /id/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Mendefinisikan cara di mana nilai n-bit dikonversi menjadi nilai 8-bit.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nama anggota** | **Deskripsi** |
| :- | :- |
| EXTRAPOLATE | Ekstrapolasi nilai 8-bit agar cocok ke dalam n bit, di mana 1 &lt; n &lt; 8.<br/>            Jumlah semua nilai 8-bit yang mungkin adalah 1 &lt;&lt; 8 = 256, dari 0 hingga 255.<br/>            Jumlah semua nilai n-bit yang mungkin adalah 1 &lt;&lt; n, dari 0 hingga (1 &lt;&lt; n) - 1.<br/>            Nilai n-bit yang paling masuk akal Vn yang sesuai dengan nilai 8-bit V8 adalah Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Pangkas nilai 8-bit agar cocok ke dalam n bit, di mana 1 &lt; n &lt; 8.<br/>            Jumlah semua nilai n-bit yang mungkin adalah 1 &lt;&lt; n, dari 0 hingga (1 &lt;&lt; n) - 1.<br/>            Nilai n-bit yang paling masuk akal Vn yang sesuai dengan nilai 8-bit V8 adalah Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

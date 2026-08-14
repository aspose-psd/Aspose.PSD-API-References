---
title: "SampleRoundingMode 列挙体"
type: docs
weight: 70
url: /ja/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

nビット値を8ビット値に変換する方法を定義します。

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **メンバー名** | **説明** |
| :- | :- |
| EXTRAPOLATE | 8ビット値を n ビットに合わせて外挿します（1 &lt; n &lt; 8）。<br/>            すべての可能な 8 ビット値の数は 1 &lt;&lt; 8 = 256 で、0 から 255 です。<br/>            すべての可能な n ビット値の数は 1 &lt;&lt; n で、0 から (1 &lt;&lt; n) - 1 です。<br/>            ある 8 ビット値 V8 に対応する最も妥当な n ビット値 Vn は Vn = V8 &gt;&gt; (8 - n) と等しくなります。 |
| TRUNCATE | 8ビット値を n ビットに合わせて切り捨てます（1 &lt; n &lt; 8）。<br/>            すべての可能な n ビット値の数は 1 &lt;&lt; n で、0 から (1 &lt;&lt; n) - 1 です。<br/>            ある 8 ビット値 V8 に対応する最も妥当な n ビット値 Vn は Vn = V8 &amp; ((1 &lt;&lt; n) - 1) と等しくなります。 |

---
title: "Перечисление SampleRoundingMode"
type: docs
weight: 70
url: /ru/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Определяет способ, которым n‑битовое значение преобразуется в 8‑битовое значение.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Имя члена** | **Описание** |
| :- | :- |
| EXTRAPOLATE | Экстраполировать 8-битное значение, чтобы разместить его в n битах, где 1 &lt; n &lt; 8.<br/>            Количество всех возможных 8-битных значений равно 1 &lt;&lt; 8 = 256, от 0 до 255.<br/>            Количество всех возможных n-битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1.<br/>            Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Обрезать 8-битное значение, чтобы разместить его в n битах, где 1 &lt; n &lt; 8.<br/>            Количество всех возможных n-битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1.<br/>            Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

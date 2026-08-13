---
title: "تعداد SampleRoundingMode"
type: docs
weight: 70
url: /ar/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

يحدد طريقة تحويل قيمة n-بت إلى قيمة 8-بت.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **اسم العضو** | **الوصف** |
| :- | :- |
| EXTRAPOLATE | استخرج قيمة 8-بت لتناسبها في n بت، حيث 1 &lt; n &lt; 8.<br/>            عدد جميع القيم الممكنة للـ 8-بت هو 1 &lt;&lt; 8 = 256، من 0 إلى 255.<br/>            عدد جميع القيم الممكنة للـ n-بت هو 1 &lt;&lt; n، من 0 إلى (1 &lt;&lt; n) - 1.<br/>            أكثر قيمة n-بت منطقية Vn المقابلة لبعض قيمة 8-بت V8 تساوي Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | اقتصر قيمة 8-بت لتناسبها في n بت، حيث 1 &lt; n &lt; 8.<br/>            عدد جميع القيم الممكنة للـ n-بت هو 1 &lt;&lt; n، من 0 إلى (1 &lt;&lt; n) - 1.<br/>            أكثر قيمة n-بت منطقية Vn المقابلة لبعض قيمة 8-بت V8 تساوي Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

---
title: "SampleRoundingMode Απαρίθμηση"
type: docs
weight: 70
url: /el/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Ορίζει έναν τρόπο με τον οποίο μια τιμή n-bit μετατρέπεται σε τιμή 8-bit.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Όνομα μέλους** | **Περιγραφή** |
| :- | :- |
| EXTRAPOLATE | Εκτείνει μια 8-bit τιμή ώστε να ταιριάζει σε n bits, όπου 1 &lt; n &lt; 8.<br/>            Ο αριθμός όλων των πιθανών 8-bit τιμών είναι 1 &lt;&lt; 8 = 256, από 0 έως 255.<br/>            Ο αριθμός όλων των πιθανών n-bit τιμών είναι 1 &lt;&lt; n, από 0 έως (1 &lt;&lt; n) - 1.<br/>            Η πιο λογική n-bit τιμή Vn που αντιστοιχεί σε κάποια 8-bit τιμή V8 είναι ίση με Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Κόβει μια 8-bit τιμή ώστε να ταιριάζει σε n bits, όπου 1 &lt; n &lt; 8.<br/>            Ο αριθμός όλων των πιθανών n-bit τιμών είναι 1 &lt;&lt; n, από 0 έως (1 &lt;&lt; n) - 1.<br/>            Η πιο λογική n-bit τιμή Vn που αντιστοιχεί σε κάποια 8-bit τιμή V8 είναι ίση με Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

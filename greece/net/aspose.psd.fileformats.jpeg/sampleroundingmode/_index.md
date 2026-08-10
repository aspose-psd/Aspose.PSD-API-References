---
title: "Απαρίθμηση SampleRoundingMode"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Απαρίθμηση Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode. Ορίζει έναν τρόπο με τον οποίο μια τιμή nbit μετατρέπεται σε τιμή 8bit."
type: docs
weight: 1540
url: /el/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

Ορίζει έναν τρόπο με τον οποίο μια τιμή n-bit μετατρέπεται σε τιμή 8-bit.

```csharp
public enum SampleRoundingMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Extrapolate | `0` | Εκτείνεται εξώθηση μιας 8-bit τιμής ώστε να ταιριάζει σε n bits, όπου 1 &lt; n &lt; 8. Ο αριθμός όλων των δυνατών 8-bit τιμών είναι 1 &lt;&lt; 8 = 256, από 0 έως 255. Ο αριθμός όλων των δυνατών n-bit τιμών είναι 1 &lt;&lt; n, από 0 έως (1 &lt;&lt; n) - 1. Η πιο λογική n-bit τιμή Vn που αντιστοιχεί σε κάποια 8-bit τιμή V8 είναι ίση με Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Κόβει μια 8-bit τιμή ώστε να ταιριάζει σε n bits, όπου 1 &lt; n &lt; 8. Ο αριθμός όλων των δυνατών n-bit τιμών είναι 1 &lt;&lt; n, από 0 έως (1 &lt;&lt; n) - 1. Η πιο λογική n-bit τιμή Vn που αντιστοιχεί σε κάποια 8-bit τιμή V8 είναι ίση με Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)



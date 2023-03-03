---
title: Enum SampleRoundingMode
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode αρίθμηση. Καθορίζει έναν τρόπο με τον οποίο μια τιμή nbit μετατρέπεται σε μια τιμή 8bit.
type: docs
weight: 1530
url: /el/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Καθορίζει έναν τρόπο με τον οποίο μια τιμή n-bit μετατρέπεται σε μια τιμή 8-bit.

```csharp
public enum SampleRoundingMode
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Extrapolate | `0` | Προεκτείνετε μια τιμή 8 bit για να την χωρέσετε σε n bit, όπου 1 &lt; n &lt; 8. Ο αριθμός όλων των πιθανών τιμών 8 bit είναι 1 &lt;&lt; 8 = 256, από 0 έως 255. Ο αριθμός όλων των δυνατών Οι τιμές n-bit είναι 1 &lt;&lt; n, από 0 έως (1 &lt;&lt; n) - 1. Η πιο λογική τιμή n-bit Vn που αντιστοιχεί σε κάποια τιμή 8-bit V8 είναι ίση με Vn = V8 &gt;&gt; (8 - ιδ). |
| Truncate | `1` | Περικόψτε μια τιμή 8-bit για να την χωρέσετε σε n bit, όπου 1 &lt; n &lt; 8. Ο αριθμός όλων των πιθανών τιμών n-bit είναι 1 &lt;&lt; n, από 0 έως (1 &lt;&lt; n) - 1. Η πιο λογική τιμή n-bit Vn που αντιστοιχεί σε κάποια τιμή 8-bit V8 είναι ίση με Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* συνέλευση [Aspose.PSD](../../)



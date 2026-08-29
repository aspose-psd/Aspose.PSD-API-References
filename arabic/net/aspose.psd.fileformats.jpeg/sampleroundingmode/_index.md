---
title: "التعداد SampleRoundingMode"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode. يحدد طريقة تحويل قيمة nbit إلى قيمة 8bit."
type: docs
weight: 1540
url: /ar/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

يحدد طريقة يتم فيها تحويل قيمة n-بت إلى قيمة 8-بت.

```csharp
public enum SampleRoundingMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Extrapolate | `0` | استنتاج قيمة 8-بت لتناسب n بت، حيث 1 &lt; n &lt; 8. عدد جميع القيم الممكنة للـ 8-بت هو 1 &lt;&lt; 8 = 256، من 0 إلى 255. عدد جميع القيم الممكنة للـ n-بت هو 1 &lt;&lt; n، من 0 إلى (1 &lt;&lt; n) - 1. أكثر قيمة n-بت منطقية تتطابق مع قيمة 8-بت V8 هي Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | اقتطاع قيمة 8-بت لتناسب n بت، حيث 1 &lt; n &lt; 8. عدد جميع القيم الممكنة للـ n-بت هو 1 &lt;&lt; n، من 0 إلى (1 &lt;&lt; n) - 1. أكثر قيمة n-بت منطقية تتطابق مع قيمة 8-بت V8 هي Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)



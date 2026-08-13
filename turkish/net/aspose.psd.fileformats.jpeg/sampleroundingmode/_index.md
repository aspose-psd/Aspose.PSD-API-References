---
title: "Enum SampleRoundingMode"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode enum. nbit değerinin 8bit değere dönüştürülme yolunu tanımlar"
type: docs
weight: 1540
url: /tr/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

n-bit bir değerin 8-bit bir değere dönüştürülme şeklini tanımlar.

```csharp
public enum SampleRoundingMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Extrapolate | `0` | 8-bit bir değeri n bitine sığdırmak için dışarı çıkarır, burada 1 &lt; n &lt; 8. Tüm olası 8-bit değerlerin sayısı 1 &lt;&lt; 8 = 256'dır, 0'dan 255'e. Tüm olası n-bit değerlerin sayısı 1 &lt;&lt; n'dir, 0'dan (1 &lt;&lt; n) - 1'e. Bazı 8-bit değer V8'e karşılık gelen en makul n-bit değer Vn, Vn = V8 &gt;&gt; (8 - n) eşitliğine eşittir. |
| Truncate | `1` | 8-bit bir değeri n bitine sığdırmak için kırpar, burada 1 &lt; n &lt; 8. Tüm olası n-bit değerlerin sayısı 1 &lt;&lt; n'dir, 0'dan (1 &lt;&lt; n) - 1'e. Bazı 8-bit değer V8'e karşılık gelen en makul n-bit değer Vn, Vn = V8 &amp; ((1 &lt;&lt; n) - 1) eşitliğine eşittir. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)



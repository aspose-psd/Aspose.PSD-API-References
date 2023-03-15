---
title: Enum SampleRoundingMode
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode Sıralama. n bitlik bir değerin 8 bitlik bir değere dönüştürüldüğü bir yol tanımlar.
type: docs
weight: 1530
url: /tr/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

n bitlik bir değerin 8 bitlik bir değere dönüştürüldüğü bir yol tanımlar.

```csharp
public enum SampleRoundingMode
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Extrapolate | `0` | 8 bitlik bir değeri n bite sığdırmak için tahmin edin, burada 1 &lt; n &lt; 8. Tüm olası 8 bitlik değerlerin sayısı 1'dir &lt;&lt; 8 = 256, 0'dan 255'e kadar. Tüm olası değerlerin sayısı n-bit değerleri 1 &lt;&lt; n, 0'dan (1 &lt;&lt; n) - 1. En makul n-bit değeri Vn, bazı 8-bitlik değerlere karşılık gelir V8 eşittir Vn = V8 &gt;&gt; (8 - N). |
| Truncate | `1` | 8 bitlik bir değeri n bite sığdırmak için kesin, burada 1 &lt; n &lt; 8. Tüm olası n bitlik değerlerin sayısı 1 &lt;&lt; n'dir, 0'dan (1 &lt;&lt; n) - 1. 8 bitlik bir V8 değerine karşılık gelen en makul n-bitlik değer Vn, Vn = V8 &amp; ((1 &lt;&lt; n) - 1). 'ye eşittir. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* toplantı [Aspose.PSD](../../)



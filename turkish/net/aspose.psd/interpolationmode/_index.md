---
title: Enum InterpolationMode
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.InterpolationMode Sıralama. InterpolationMode numaralandırma görüntüler ölçeklendiğinde veya döndürüldüğünde kullanılan algoritmayı belirtir.
type: docs
weight: 5030
url: /tr/net/aspose.psd/interpolationmode/
---
## InterpolationMode enumeration

`InterpolationMode` numaralandırma, görüntüler ölçeklendiğinde veya döndürüldüğünde kullanılan algoritmayı belirtir.

```csharp
public enum InterpolationMode
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Invalid | `-1` | Geçersiz enterpolasyon modu. |
| Default | `0` | Varsayılan modu belirtir. |
| Low | `1` | Düşük kaliteli enterpolasyonu belirtir. |
| High | `2` | Yüksek kaliteli enterpolasyonu belirtir. |
| Bilinear | `3` | Çift doğrusal enterpolasyonu belirtir. Ön filtreleme yapılmaz. Bu mod, bir görüntüyü orijinal boyutunun yüzde 50'sinin altına küçültmek için uygun değildir. |
| Bicubic | `4` | Çift kübik interpolasyonu belirtir. Ön filtreleme yapılmaz. Bu mod, bir görüntüyü orijinal boyutunun yüzde 25'inin altına küçültmek için uygun değildir. |
| NearestNeighbor | `5` | En yakın komşu enterpolasyonunu belirtir. |
| HighQualityBilinear | `6` | Yüksek kaliteli, çift doğrusal enterpolasyonu belirtir. Yüksek kaliteli küçülmeyi sağlamak için ön filtreleme gerçekleştirilir. |
| HighQualityBicubic | `7` | Yüksek kaliteli, çift kübik enterpolasyonu belirtir. Yüksek kalitede küçültme sağlamak için ön filtreleme yapılır. Bu mod, en yüksek kalitede dönüştürülmüş görüntüleri üretir. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)



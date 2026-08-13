---
title: "Enum InterpolationMode"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.InterpolationMode enum. InterpolationMode enumerasyonu, görüntüler ölçeklendirildiğinde veya döndürüldüğünde kullanılan algoritmayı belirtir."
type: docs
weight: 5550
url: /tr/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

`InterpolationMode` enumerasyonu, görüntüler ölçeklendirildiğinde veya döndürüldüğünde kullanılan algoritmayı belirtir.

```csharp
public enum InterpolationMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Invalid | `-1` | Geçersiz interpolasyon modu. |
| Default | `0` | Varsayılan modu belirtir. |
| Low | `1` | Düşük kalite interpolasyonunu belirtir. |
| High | `2` | Yüksek kalite interpolasyonunu belirtir. |
| Bilinear | `3` | Bilinear interpolasyonu belirtir. Ön filtreleme yapılmaz. Bu mod, bir görüntünün orijinal boyutunun %50'sinden daha küçük bir boyuta küçültülmesi için uygun değildir. |
| Bicubic | `4` | Bikübik interpolasyonu belirtir. Ön filtreleme yapılmaz. Bu mod, bir görüntünün orijinal boyutunun %25'inden daha küçük bir boyuta küçültülmesi için uygun değildir. |
| NearestNeighbor | `5` | En yakın komşu interpolasyonunu belirtir. |
| HighQualityBilinear | `6` | Yüksek kaliteli, bilinear interpolasyonu belirtir. Yüksek kaliteli küçültmeyi sağlamak için ön filtreleme uygulanır. |
| HighQualityBicubic | `7` | Yüksek kaliteli, bikübik interpolasyonu belirtir. Yüksek kaliteli küçültmeyi sağlamak için ön filtreleme uygulanır. Bu mod, en yüksek kaliteye sahip dönüştürülmüş görüntüler üretir. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



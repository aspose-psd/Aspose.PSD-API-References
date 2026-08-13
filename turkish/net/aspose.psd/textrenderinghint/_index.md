---
title: "Enum TextRenderingHint"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.TextRenderingHint enum. Metin renderleme kalitesini belirtir"
type: docs
weight: 6230
url: /tr/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

Metin renderleme kalitesini belirtir.

```csharp
public enum TextRenderingHint
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| SystemDefault | `0` | Her karakter, sistemin varsayılan renderleme ipucu ile glif bitmap'i kullanılarak çizilir. Metin, kullanıcının sistem için seçtiği font yumuşatma ayarlarıyla çizilecektir. |
| SingleBitPerPixelGridFit | `1` | Her karakter, glif bitmap'i kullanılarak çizilir. Hinting, karakterin gövde ve eğrilik üzerindeki görünümünü iyileştirmek için kullanılır. |
| SingleBitPerPixel | `2` | Her karakter, glif bitmap'i kullanılarak çizilir. Hinting kullanılmaz. |
| AntiAliasGridFit | `3` | Her karakter, hinting ile antialias'li glif bitmap'i kullanılarak çizilir. Antialias sayesinde çok daha iyi kalite sağlar, ancak daha yüksek performans maliyeti vardır. |
| AntiAlias | `4` | Her karakter, hinting olmadan antialias'li glif bitmap'i kullanılarak çizilir. Antialias sayesinde daha iyi kalite elde edilir. Hinting kapalı olduğundan gövde genişliği farkları fark edilebilir. |
| ClearTypeGridFit | `5` | Her karakter, hinting ile glif ClearType bitmap'i kullanılarak çizilir. En yüksek kalite ayarı. ClearType font özelliklerinden yararlanmak için kullanılır. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD for .NET API Referansı"
description: "GifOptions özelliği. GIF piksel en‑boy oranını alır veya ayarlar"
type: docs
weight: 90
url: /tr/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

GIF piksel en‑boy oranını alır veya ayarlar.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

GIF piksel en‑boy oranı.

## Açıklamalar

Pixel Aspect Ratio - Orijinal görüntüdeki pikselin en‑boy oranının bir yaklaşık değerini hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en‑boy oranı yaklaşık değeri aşağıdaki formüle göre hesaplanır: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Pixel Aspect Ratio, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, en geniş piksel 4:1'den en yüksek piksel 1:4'e kadar 1/64 artışlarla belirtmeye olanak tanır. Değerler: 0 - En‑boy oranı bilgisi verilmez. 1..255 - Hesaplamada kullanılan değer.

### Ayrıca Bakınız

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)



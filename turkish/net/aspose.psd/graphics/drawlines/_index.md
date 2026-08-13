---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Bir dizi Point yapısını bağlayan bir dizi çizgi segmenti çizer"
type: docs
weight: 270
url: /tr/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Bir dizi [`Point`](../../point/) yapısını bağlayan bir dizi çizgi segmenti çizer.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) çizgi segmentlerinin renk, genişlik ve stilini belirler. |
| points | Point[] | Bağlanacak noktaları temsil eden bir dizi [`Point`](../../point/) yapısı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |
| ArgumentException | *points* dizisi 2'den az nokta içeriyor. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Bir dizi [`PointF`](../../pointf/) yapısını bağlayan bir dizi çizgi segmenti çizer.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) çizgi segmentlerinin renk, genişlik ve stilini belirler. |
| points | PointF[] | Bağlanacak noktaları temsil eden bir dizi [`PointF`](../../pointf/) yapısı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |
| ArgumentException | *points* dizisi 2'den az nokta içeriyor. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



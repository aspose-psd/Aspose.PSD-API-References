---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Noktaları temsil eden dört sıralı koordinat çiftiyle tanımlanan bir Bézier eğrisi çizer"
type: docs
weight: 180
url: /tr/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Nokta temsil eden dört sıralı koordinat çiftine göre tanımlanan bir Bézier eğrisi çizer.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin renk, genişlik ve stilini belirler. |
| x1 | Single | Eğrinin başlangıç noktasının x koordinatı. |
| y1 | Single | Eğrinin başlangıç noktasının y koordinatı. |
| x2 | Single | Eğrinin birinci kontrol noktasının x koordinatı. |
| y2 | Single | Eğrinin birinci kontrol noktasının y koordinatı. |
| x3 | Single | Eğrinin ikinci kontrol noktasının x koordinatı. |
| y3 | Single | Eğrinin ikinci kontrol noktasının y koordinatı. |
| x4 | Single | Eğrinin bitiş noktasının x koordinatı. |
| y4 | Single | Eğrinin bitiş noktasının y koordinatı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Dört [`PointF`](../../pointf/) yapısı tarafından tanımlanan bir Bézier spline çizer.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin renk, genişlik ve stilini belirler. |
| pt1 | PointF | [`PointF`](../../pointf/) yapısı, eğrinin başlangıç noktasını temsil eder. |
| pt2 | PointF | [`PointF`](../../pointf/) yapısı, eğri için birinci kontrol noktasını temsil eder. |
| pt3 | PointF | [`PointF`](../../pointf/) yapısı, eğri için ikinci kontrol noktasını temsil eder. |
| pt4 | PointF | [`PointF`](../../pointf/) yapısı, eğrinin bitiş noktasını temsil eder. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Dört [`Point`](../../point/) yapısı tarafından tanımlanan bir Bézier spline çizer.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yapısı, eğrinin renk, genişlik ve stilini belirler. |
| pt1 | Point | [`Point`](../../point/) yapısı, eğrinin başlangıç noktasını temsil eder. |
| pt2 | Point | [`Point`](../../point/) yapısı, eğrinin ilk kontrol noktasını temsil eder. |
| pt3 | Point | [`Point`](../../point/) yapısı, eğrinin ikinci kontrol noktasını temsil eder. |
| pt4 | Point | [`Point`](../../point/) yapısı, eğrinin bitiş noktasını temsil eder. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



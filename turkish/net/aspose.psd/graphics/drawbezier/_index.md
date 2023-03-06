---
title: Graphics.DrawBezier
second_title: Aspose.PSD for .NET API Referansı
description: Graphics yöntem. Noktaları temsil eden sıralı dört koordinat çifti tarafından tanımlanan bir Bézier spline çizer.
type: docs
weight: 170
url: /tr/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Noktaları temsil eden sıralı dört koordinat çifti tarafından tanımlanan bir Bézier spline çizer.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve stilini belirler. |
| x1 | Single | Eğrinin başlangıç noktasının x koordinatı. |
| y1 | Single | Eğrinin başlangıç noktasının y koordinatı. |
| x2 | Single | Eğrinin ilk kontrol noktasının x koordinatı. |
| y2 | Single | Eğrinin ilk kontrol noktasının y koordinatı. |
| x3 | Single | Eğrinin ikinci kontrol noktasının x koordinatı. |
| y3 | Single | Eğrinin ikinci kontrol noktasının y koordinatı. |
| x4 | Single | Eğrinin bitiş noktasının x koordinatı. |
| y4 | Single | Eğrinin bitiş noktasının y koordinatı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Dört ile tanımlanan bir Bézier spline çizer[`PointF`](../../pointf/) yapılar.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve stilini belirler. |
| pt1 | PointF | [`PointF`](../../pointf/) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | PointF | [`PointF`](../../pointf/) eğri için ilk kontrol noktasını temsil eden yapı. |
| pt3 | PointF | [`PointF`](../../pointf/) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | PointF | [`PointF`](../../pointf/) eğrinin bitiş noktasını temsil eden yapı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Dört ile tanımlanan bir Bézier spline çizer[`Point`](../../point/) yapılar.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve stilini belirleyen yapı. |
| pt1 | Point | [`Point`](../../point/) eğrinin başlangıç noktasını temsil eden yapı. |
| pt2 | Point | [`Point`](../../point/) eğri için ilk kontrol noktasını temsil eden yapı. |
| pt3 | Point | [`Point`](../../point/) eğri için ikinci kontrol noktasını temsil eden yapı. |
| pt4 | Point | [`Point`](../../point/) eğrinin bitiş noktasını temsil eden yapı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)



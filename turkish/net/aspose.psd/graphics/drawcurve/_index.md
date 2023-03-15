---
title: Graphics.DrawCurve
second_title: Aspose.PSD for .NET API Referansı
description: Graphics yöntem. Belirli bir dizi boyunca bir kardinal spline çizer.PointF yapılar. Bu yöntem 0.5. varsayılan gerginliğini kullanır.
type: docs
weight: 200
url: /tr/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../../pointf/) yapılar. Bu yöntem, 0.5. varsayılan gerginliğini kullanır.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf/) Spline'ı tanımlayan yapılar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../../pointf/) belirli bir gerilimi kullanan yapılar.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf/) eğriyi tanımlayan noktaları temsil eden yapılar. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'den büyük veya eşit değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../../pointf/) yapılar. Çizim, dizinin başından ofset olarak başlar. Bu yöntem, 0.5. varsayılan gerginliğini kullanır.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf/) Spline'ı tanımlayan yapılar. |
| offset | Int32 | dizisindeki ilk öğeden ofset*points* eğrideki başlangıç noktasına parametre. |
| numberOfSegments | Int32 | Eğriye dahil edilecek başlangıç noktasından sonraki segment sayısı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Belirli bir dizi boyunca bir kardinal spline çizer.[`PointF`](../../pointf/) belirli bir gerilim kullanan yapılar. Çizim, dizinin başından itibaren kaydırılarak başlar.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | PointF[] | dizisi[`PointF`](../../pointf/) Spline'ı tanımlayan yapılar. |
| offset | Int32 | dizisindeki ilk öğeden ofset*points* eğrideki başlangıç noktasına parametre. |
| numberOfSegments | Int32 | Eğriye dahil edilecek başlangıç noktasından sonraki segment sayısı. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'den büyük veya eşit değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Belirli bir dizi boyunca bir kardinal spline çizer.[`Point`](../../point/) yapılar.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | Point[] | dizisi[`Point`](../../point/) Spline'ı tanımlayan yapılar. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Belirli bir dizi boyunca bir kardinal spline çizer.[`Point`](../../point/) belirli bir gerilimi kullanan yapılar.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | Point[] | dizisi[`Point`](../../point/) Spline'ı tanımlayan yapılar. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'den büyük veya eşit değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Belirli bir dizi boyunca bir kardinal spline çizer.[`Point`](../../point/) belirli bir gerilimi kullanan yapılar.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirler. |
| points | Point[] | dizisi[`Point`](../../point/) Spline'ı tanımlayan yapılar. |
| offset | Int32 | dizisindeki ilk öğeden ofset*points* eğrideki başlangıç noktasına parametre. |
| numberOfSegments | Int32 | Eğriye dahil edilecek başlangıç noktasından sonraki segment sayısı. |
| tension | Single | Eğrinin gerilimini belirten 0.0F'den büyük veya eşit değer. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* boş. |

### Ayrıca bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* ad alanı [Aspose.PSD](../../graphics/)
* toplantı [Aspose.PSD](../../../)



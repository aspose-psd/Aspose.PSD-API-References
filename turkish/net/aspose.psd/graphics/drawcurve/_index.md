---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Belirtilen bir PointF yapısı dizisi üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilme değerini kullanır."
type: docs
weight: 210
url: /tr/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

Belirtilen bir [`PointF`](../../pointf/) yapısı dizisi üzerinden bir kardinal spline çizer. Bu yöntem varsayılan 0.5 gerilme değerini kullanır.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirleyen. |
| points | PointF[] | Spline'ı tanımlayan [`PointF`](../../pointf/) yapılarının dizisi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Belirtilen bir gerilme değeri kullanarak, belirtilen bir [`PointF`](../../pointf/) yapısı dizisi üzerinden bir kardinal spline çizer.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirleyen. |
| points | PointF[] | Eğriyi tanımlayan noktaları temsil eden [`PointF`](../../pointf/) yapılarının dizisi. |
| gerilim | Single | Eğrinin gerilmesini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Belirtilen bir [`PointF`](../../pointf/) yapısı dizisi üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar. Bu yöntem varsayılan 0.5 gerilme değerini kullanır.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirleyen. |
| points | PointF[] | Spline'ı tanımlayan [`PointF`](../../pointf/) yapılarının dizisi. |
| offset | Int32 | *points* parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına kadar olan offset. |
| numberOfSegments | Int32 | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Belirtilen bir gerilme değeri kullanarak, belirtilen bir [`PointF`](../../pointf/) yapısı dizisi üzerinden bir kardinal spline çizer. Çizim, dizinin başlangıcından bir offset ile başlar.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirleyen. |
| points | PointF[] | Spline'ı tanımlayan [`PointF`](../../pointf/) yapılarının dizisi. |
| offset | Int32 | *points* parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına kadar olan offset. |
| numberOfSegments | Int32 | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | Single | Eğrinin gerilmesini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Belirtilen bir [`Point`](../../point/) yapısı dizisi üzerinden bir kardinal spline çizer.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirleyen. |
| points | Point[] | Spline'ı tanımlayan [`Point`](../../point/) yapılarının dizisi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Belirtilen bir gerilme değeri kullanarak, belirtilen bir [`Point`](../../point/) yapısı dizisi üzerinden bir kardinal spline çizer.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirleyen. |
| points | Point[] | Spline'ı tanımlayan [`Point`](../../point/) yapılarının dizisi. |
| gerilim | Single | Eğrinin gerilmesini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Belirtilen bir gerilme değeri kullanarak, belirtilen bir [`Point`](../../point/) yapısı dizisi üzerinden bir kardinal spline çizer.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) eğrinin rengini, genişliğini ve yüksekliğini belirleyen. |
| points | Point[] | Spline'ı tanımlayan [`Point`](../../point/) yapılarının dizisi. |
| offset | Int32 | *points* parametresinin dizi içindeki ilk elemanından eğrinin başlangıç noktasına kadar olan offset. |
| numberOfSegments | Int32 | Eğriye dahil edilecek, başlangıç noktasından sonraki segment sayısı. |
| gerilim | Single | Eğrinin gerilmesini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pen* null. -veya- *points* null. |

### Ayrıca Bakınız

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



---
title: "Graphics.FillClosedCurve"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Bir dizi PointF yapısı tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilme ve Alternate doldurma modunu kullanır."
type: docs
weight: 350
url: /tr/net/aspose.psd/graphics/fillclosedcurve/
---
{{< psd/tize >}}
## FillClosedCurve(Brush, PointF[]) {#fillclosedcurve}

Bir dizi [`PointF`](../../pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilme ve Alternate doldurma modunu kullanır.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| points | PointF[] | Spline'ı tanımlayan [`PointF`](../../pointf/) yapılarının dizisi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *points* null'dur. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode) {#fillclosedcurve_1}

Belirtilen doldurma modu kullanılarak, bir dizi [`PointF`](../../pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilme kullanır.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| points | PointF[] | Spline'ı tanımlayan [`PointF`](../../pointf/) yapılarının dizisi. |
| fillmode | FillMode | `[`FillMode`](../../fillmode/)` enumerasyonunun, eğrinin nasıl doldurulacağını belirleyen üyesi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *points* null'dur. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, PointF[], FillMode, float) {#fillclosedcurve_2}

Belirtilen doldurma modu ve gerilme kullanılarak, bir dizi [`PointF`](../../pointf/) yapısı tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.

```csharp
public void FillClosedCurve(Brush brush, PointF[] points, FillMode fillmode, float tension)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | Doldurmanın özelliklerini belirleyen bir [`Brush`](../../brush/). |
| points | PointF[] | Spline'ı tanımlayan [`PointF`](../../pointf/) yapılarının dizisi. |
| fillmode | FillMode | `[`FillMode`](../../fillmode/)` enumerasyonunun, eğrinin nasıl doldurulacağını belirleyen üyesi. |
| gerilim | Single | Eğrinin gerilmesini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *points* null'dur. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[]) {#fillclosedcurve_3}

Bir dizi [`Point`](../../point/) yapısı tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilme ve Alternate doldurma modunu kullanır.

```csharp
public void FillClosedCurve(Brush brush, Point[] points)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| points | Point[] | Spline'ı tanımlayan [`Point`](../../point/) yapılarının dizisi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *points* null'dur. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode) {#fillclosedcurve_4}

Belirtilen doldurma modu kullanılarak, bir dizi [`Point`](../../point/) yapısı tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur. Bu yöntem varsayılan 0,5 gerilme kullanır.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| points | Point[] | Spline'ı tanımlayan [`Point`](../../point/) yapılarının dizisi. |
| fillmode | FillMode | `[`FillMode`](../../fillmode/)` enumerasyonunun, eğrinin nasıl doldurulacağını belirleyen üyesi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *points* null'dur. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillClosedCurve(Brush, Point[], FillMode, float) {#fillclosedcurve_5}

Belirtilen doldurma modu ve gerilme kullanılarak, bir dizi [`Point`](../../point/) yapısı tarafından tanımlanan kapalı bir kardinal spline eğrisinin içini doldurur.

```csharp
public void FillClosedCurve(Brush brush, Point[] points, FillMode fillmode, float tension)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) doldurmanın özelliklerini belirler. |
| points | Point[] | Spline'ı tanımlayan [`Point`](../../point/) yapılarının dizisi. |
| fillmode | FillMode | `[`FillMode`](../../fillmode/)` enumerasyonunun, eğrinin nasıl doldurulacağını belirleyen üyesi. |
| gerilim | Single | Eğrinin gerilmesini belirten, 0.0F'ye eşit veya daha büyük bir değer. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *brush* null'dur. -or- *points* null'dur. |

### Ayrıca Bakınız

* class [Brush](../../brush/)
* struct [Point](../../point/)
* enum [FillMode](../../fillmode/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



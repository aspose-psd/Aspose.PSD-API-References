---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل PointF. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5."
type: docs
weight: 210
url: /ar/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تحدد المنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/) باستخدام توتر محدد.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تمثل النقاط التي تحدد المنحنى. |
| الشد | Single | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/). يبدأ الرسم بإزاحة من بداية المصفوفة. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تحدد المنحنى. |
| offset | Int32 | إزاحة من العنصر الأول في مصفوفة المعامل *points* إلى نقطة البدء في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/) باستخدام توتر محدد. يبدأ الرسم بإزاحة من بداية المصفوفة.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تحدد المنحنى. |
| offset | Int32 | إزاحة من العنصر الأول في مصفوفة المعامل *points* إلى نقطة البدء في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |
| الشد | Single | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../../point/).

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والارتفاع للمنحنى. |
| points | Point[] | مصفوفة من هياكل [`Point`](../../point/) التي تحدد المنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../../point/) باستخدام توتر محدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والارتفاع للمنحنى. |
| points | Point[] | مصفوفة من هياكل [`Point`](../../point/) التي تحدد المنحنى. |
| الشد | Single | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`Point`](../../point/) باستخدام توتر محدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والارتفاع للمنحنى. |
| points | Point[] | مصفوفة من هياكل [`Point`](../../point/) التي تحدد المنحنى. |
| offset | Int32 | إزاحة من العنصر الأول في مصفوفة المعامل *points* إلى نقطة البدء في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |
| الشد | Single | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



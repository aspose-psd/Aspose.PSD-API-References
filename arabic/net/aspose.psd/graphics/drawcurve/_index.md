---
title: Graphics.DrawCurve
second_title: Aspose.PSD لمرجع .NET API
description: Graphics طريقة. يرسم العمود الفقري الأساسي من خلال مصفوفة محددة منPointF الهياكل. تستخدم هذه الطريقة توتر افتراضي 0.5 .
type: docs
weight: 200
url: /ar/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf/) الهياكل. تستخدم هذه الطريقة توتر افتراضي 0.5 .

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf/) الهياكل التي تحدد الشريحة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf/) الهياكل باستخدام التوتر المحدد.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf/) الهياكل التي تمثل النقاط التي تحدد المنحنى. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf/) الهياكل. يبدأ الرسم في الإزاحة من بداية المصفوفة . تستخدم هذه الطريقة شد افتراضي 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf/) الهياكل التي تحدد الشريحة. |
| offset | Int32 | الإزاحة من العنصر الأول في مصفوفة*points* معلمة إلى نقطة البداية في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البداية لتضمينها في المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf/) الهياكل التي تستخدم توترًا محددًا. يبدأ الرسم في الإزاحة من بداية المصفوفة.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf/) الهياكل التي تحدد الشريحة. |
| offset | Int32 | الإزاحة من العنصر الأول في مصفوفة*points* معلمة إلى نقطة البداية في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البداية لتضمينها في المنحنى. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../../point/) الهياكل .

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | Point[] | مصفوفة من[`Point`](../../point/) الهياكل التي تحدد الشريحة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../../point/) الهياكل باستخدام التوتر المحدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | Point[] | مصفوفة من[`Point`](../../point/) الهياكل التي تحدد الشريحة. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../../point/) الهياكل باستخدام التوتر المحدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | Point[] | مصفوفة من[`Point`](../../point/) الهياكل التي تحدد الشريحة. |
| offset | Int32 | الإزاحة من العنصر الأول في مصفوفة*points* معلمة إلى نقطة البداية في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البداية لتضمينها في المنحنى. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)



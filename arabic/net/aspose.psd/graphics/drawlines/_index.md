---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. ترسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل Point"
type: docs
weight: 270
url: /ar/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [`Point`](../../point/).

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لمقاطع الخط. |
| points | Point[] | مصفوفة من هياكل [`Point`](../../point/) التي تمثل النقاط المراد ربطها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |
| ArgumentException | مصفوفة *points* تحتوي على أقل من نقطتين. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

يرسم سلسلة من مقاطع الخط التي تربط مصفوفة من هياكل [`PointF`](../../pointf/).

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لمقاطع الخط. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تمثل النقاط المراد ربطها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |
| ArgumentException | مصفوفة *points* تحتوي على أقل من نقطتين. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



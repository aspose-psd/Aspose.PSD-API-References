---
title: "Graphics.DrawBezier"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. ترسم منحنى بيزيه محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا."
type: docs
weight: 180
url: /ar/net/aspose.psd/graphics/drawbezier/
---
{{< psd/tize >}}
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

يرسم منحنى بيزييه محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| x1 | Single | الإحداثي x للنقطة البداية للمنحنى. |
| y1 | Single | الإحداثي y للنقطة البداية للمنحنى. |
| x2 | Single | الإحداثي x لنقطة التحكم الأولى للمنحنى. |
| y2 | Single | الإحداثي y لنقطة التحكم الأولى للمنحنى. |
| x3 | Single | الإحداثي x لنقطة التحكم الثانية للمنحنى. |
| y3 | Single | الإحداثي y لنقطة التحكم الثانية للمنحنى. |
| x4 | Single | الإحداثي x للنقطة النهاية للمنحنى. |
| y4 | Single | الإحداثي y للنقطة النهاية للمنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

ترسم منحنى بيزيه محدد بأربع هياكل [`PointF`](../../pointf/).

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | PointF | [`PointF`](../../pointf/) بنية تمثل نقطة البداية للمنحنى. |
| pt2 | PointF | `[`PointF`](../../pointf/) بنية تمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | PointF | `[`PointF`](../../pointf/) بنية تمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | PointF | `[`PointF`](../../pointf/) بنية تمثل نقطة النهاية للمنحنى. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

`يرسم منحنى بيزيه معرف بأربع بنى [`Point`](../../point/).`

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/) بنية تحدد اللون والعرض والنمط للمنحنى.` |
| pt1 | Point | `[`Point`](../../point/) بنية تمثل نقطة البداية للمنحنى.` |
| pt2 | Point | `[`Point`](../../point/) بنية تمثل نقطة التحكم الأولى للمنحنى.` |
| pt3 | Point | `[`Point`](../../point/) بنية تمثل نقطة التحكم الثانية للمنحنى.` |
| pt4 | Point | `[`Point`](../../point/) بنية تمثل نقطة النهاية للمنحنى.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



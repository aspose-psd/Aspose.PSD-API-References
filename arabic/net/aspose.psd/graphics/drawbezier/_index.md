---
title: Graphics.DrawBezier
second_title: Aspose.PSD لمرجع .NET API
description: Graphics طريقة. يرسم شريحة بيزير محددة بأربعة أزواج مرتبة من الإحداثيات التي تمثل النقاط.
type: docs
weight: 170
url: /ar/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

يرسم شريحة بيزير محددة بأربعة أزواج مرتبة من الإحداثيات التي تمثل النقاط.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وأسلوب المنحنى. |
| x1 | Single | إحداثي x لنقطة بداية المنحنى. |
| y1 | Single | إحداثي y لنقطة بداية المنحنى. |
| x2 | Single | إحداثي x لنقطة التحكم الأولى في المنحنى. |
| y2 | Single | إحداثي y لنقطة التحكم الأولى في المنحنى. |
| x3 | Single | الإحداثي x لنقطة التحكم الثانية للمنحنى. |
| y3 | Single | الإحداثي y لنقطة التحكم الثانية للمنحنى. |
| x4 | Single | إحداثي x لنقطة نهاية المنحنى. |
| y4 | Single | إحداثي y لنقطة نهاية المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

يرسم شريحة بيزير محددة بأربعة[`PointF`](../../pointf/) الهياكل .

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض وأسلوب المنحنى. |
| pt1 | PointF | [`PointF`](../../pointf/) الهيكل الذي يمثل نقطة البداية للمنحنى. |
| pt2 | PointF | [`PointF`](../../pointf/) الهيكل الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | PointF | [`PointF`](../../pointf/) الهيكل الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | PointF | [`PointF`](../../pointf/) الهيكل الذي يمثل نقطة نهاية المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

يرسم شريحة بيزير محددة بأربعة[`Point`](../../point/) الهياكل .

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الهيكل الذي يحدد لون وعرض وأسلوب المنحنى. |
| pt1 | Point | [`Point`](../../point/) الهيكل الذي يمثل نقطة البداية للمنحنى. |
| pt2 | Point | [`Point`](../../point/) الهيكل الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | Point | [`Point`](../../point/) الهيكل الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | Point | [`Point`](../../point/) الهيكل الذي يمثل نقطة نهاية المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)



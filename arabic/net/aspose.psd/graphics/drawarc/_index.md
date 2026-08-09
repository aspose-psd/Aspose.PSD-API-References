---
title: "Graphics.DrawArc"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. ترسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات والعرض والارتفاع."
type: docs
weight: 170
url: /ar/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض ونمط القوس. |
| x | Single | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| y | Single | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| العرض | Single | عرض المستطيل الذي يحدد القطع الناقص. |
| الارتفاع | Single | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| startAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى نقطة بدء القوس. |
| sweepAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى نقطة انتهاء القوس. |

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

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية [`RectangleF`](../../rectanglef/).

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض ونمط القوس. |
| rect | RectangleF | بنية [`RectangleF`](../../rectanglef/) التي تحدد حدود الإهليلج. |
| startAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى نقطة بدء القوس. |
| sweepAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى نقطة انتهاء القوس. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

يرسم قوسًا يمثل جزءًا من إهليلج محدد بواسطة زوج من الإحداثيات، وعرض، وارتفاع.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض ونمط القوس. |
| x | Int32 | الإحداثي السيني للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| y | Int32 | الإحداثي الصادي للزاوية العلوية اليسرى للمستطيل الذي يحدد القطع الناقص. |
| العرض | Int32 | عرض المستطيل الذي يحدد القطع الناقص. |
| الارتفاع | Int32 | ارتفاع المستطيل الذي يحدد القطع الناقص. |
| startAngle | Int32 | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى نقطة بدء القوس. |
| sweepAngle | Int32 | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى نقطة انتهاء القوس. |

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

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

يرسم قوسًا يمثل جزءًا من قطع ناقص محدد بواسطة بنية [`Rectangle`](../../rectangle/).

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض ونمط القوس. |
| rect | Rectangle | بنية [`RectangleF`](../../rectanglef/) التي تحدد حدود الإهليلج. |
| startAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى نقطة بدء القوس. |
| sweepAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى نقطة انتهاء القوس. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



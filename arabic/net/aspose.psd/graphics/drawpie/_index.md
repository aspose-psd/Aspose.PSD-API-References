---
title: "Graphics.DrawPie"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. ترسم شكل فطيرة معرفًا بواسطة إهليلج محدد بهيكل RectangleF وخطين شعاعيين"
type: docs
weight: 290
url: /ar/net/aspose.psd/graphics/drawpie/
---
{{< psd/tize >}}
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

ترسم شكل فطيرة معرفًا بواسطة إهليلج محدد بهيكل [`RectangleF`](../../rectanglef/) وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)` الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | RectangleF | هيكل [`RectangleF`](../../rectanglef/) الذي يمثل المستطيل الحدودي الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| startAngle | Single | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweepAngle | Single | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من شكل الفطيرة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

يرسم شكل فطيرة يُعرّف بواسطة إهليلج محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)` الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | Single | الإحداثي x للزاوية العلوية اليسرى للمستطيل الحدودي الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| y | Single | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| العرض | Single | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| الارتفاع | Single | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| startAngle | Single | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweepAngle | Single | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من شكل الفطيرة. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

يرسم شكل فطيرة معرف بقطع ناقص محدد بواسطة بنية [`Rectangle`](../../rectangle/) وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)` الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) التي تمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| startAngle | Single | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweepAngle | Single | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من شكل الفطيرة. |

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

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

يرسم شكل فطيرة يُعرّف بواسطة إهليلج محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | `[`Pen`](../../pen/)` الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | Int32 | الإحداثي x للزاوية العلوية اليسرى للمستطيل الحدودي الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| y | Int32 | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| العرض | Int32 | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| الارتفاع | Int32 | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه شكل الفطيرة. |
| startAngle | Int32 | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من محور x إلى الجانب الأول من شكل الفطيرة. |
| sweepAngle | Int32 | الزاوية مقاسة بالدرجات باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من شكل الفطيرة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



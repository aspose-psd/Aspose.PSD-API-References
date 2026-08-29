---
title: "Graphics.FillPie"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. تملأ داخل قطاع فطيرة معرف بواسطة إهليلج محدد بواسطة بنية RectangleF وخطين شعاعيين."
type: docs
weight: 380
url: /ar/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

تملأ داخل قطاع فطيرة معرف بواسطة إهليلج محدد بواسطة بنية [`RectangleF`](../../rectanglef/) وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) التي تمثل المستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه قطاع الفطيرة. |
| startAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

تملأ داخل قطاع فطيرة معرف بواسطة إهليلج محدد بواسطة بنية [`RectangleF`](../../rectanglef/) وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| rect | RectangleF | الهيكل [`RectangleF`](../../rectanglef/) الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| x | Single | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | Single | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| العرض | Single | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | Single | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | Single | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

يملأ داخل قطاع فطيرة محدد بواسطة إهليلج محدد بواسطة زوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| x | Int32 | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | Int32 | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| العرض | Int32 | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | Int32 | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | Int32 | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المحور السيني إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | Int32 | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



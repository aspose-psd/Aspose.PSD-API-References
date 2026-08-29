---
title: "Graphics.DrawString"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "`طريقة Graphics. ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات Brush و Font المحددة`"
type: docs
weight: 330
url: /ar/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

`ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) المحددة.`

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | `السلسلة المراد رسمها.` |
| font | Font | `[`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة.` |
| brush | Brush | `[`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم.` |
| x | Single | `الإحداثي x للزاوية العليا اليسرى للنص المرسوم.` |
| y | Single | `الإحداثي y للزاوية العليا اليسرى للنص المرسوم.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*brush* فارغ. -أو- *s* فارغ.` |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

`ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) المحددة.`

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | `السلسلة المراد رسمها.` |
| font | Font | `[`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة.` |
| brush | Brush | `[`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم.` |
| point | PointF | `[`PointF`](../../pointf/) بنية تحدد الزاوية العليا اليسرى للنص المرسوم.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*brush* فارغ. -أو- *s* فارغ.` |

## أمثلة

يوضح هذا المثال استخدام فئة Font وفئة SolidBrush لرسم سلاسل نصية على سطح Image. ينشئ المثال صورة جديدة ويرسم أشكالاً باستخدام Figures و GraphicsPath.

```csharp
[C#]

//ينشئ مثيلاً من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //ينشئ ويُهيئ مثيلاً من الفئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //يمسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //ينشئ مثيلاً من Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //أنشئ مثيلاً من SolidBrush بلون أحمر
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //ارسم سلسلة نصية
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // إنشاء خيارات التصدير.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // احفظ جميع التغييرات
    image.Save("C:\\temp\\output.gif", options);
}
```

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

`ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) مع خصائص التنسيق المحددة في [`StringFormat`](../../stringformat/).`

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | `السلسلة المراد رسمها.` |
| font | Font | `[`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة.` |
| brush | Brush | `[`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم.` |
| x | Single | `الإحداثي x للزاوية العليا اليسرى للنص المرسوم.` |
| y | Single | `الإحداثي y للزاوية العليا اليسرى للنص المرسوم.` |
| format | StringFormat | `[`StringFormat`](../../stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*brush* فارغ. -أو- *s* فارغ.` |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

`ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) مع خصائص التنسيق المحددة في [`StringFormat`](../../stringformat/).`

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | `السلسلة المراد رسمها.` |
| font | Font | `[`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة.` |
| brush | Brush | `[`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم.` |
| point | PointF | `[`PointF`](../../pointf/) بنية تحدد الزاوية العليا اليسرى للنص المرسوم.` |
| format | StringFormat | `[`StringFormat`](../../stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*brush* فارغ. -أو- *s* فارغ.` |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

`ترسم سلسلة النص المحددة داخل المستطيل المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/).`

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | `السلسلة المراد رسمها.` |
| font | Font | `[`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة.` |
| brush | Brush | `[`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم.` |
| layoutRectangle | RectangleF | `[`RectangleF`](../../rectanglef/) بنية تحدد موقع النص المرسوم.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*brush* فارغ. -أو- *s* فارغ.` |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

`ترسم سلسلة النص المحددة داخل المستطيل المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) مع خصائص التنسيق المحددة في [`StringFormat`](../../stringformat/).`

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | `السلسلة المراد رسمها.` |
| font | Font | `[`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة.` |
| brush | Brush | `[`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم.` |
| layoutRectangle | RectangleF | `[`RectangleF`](../../rectanglef/) بنية تحدد موقع النص المرسوم.` |
| format | StringFormat | `[`StringFormat`](../../stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*brush* فارغ. -أو- *s* فارغ. -أو- *brush* فارغ.` |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



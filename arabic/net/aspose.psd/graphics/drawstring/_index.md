---
title: Graphics.DrawString
second_title: Aspose.PSD لمرجع .NET API
description: Graphics طريقة. رسم السلسلة النصية المحددة بالموقع المحددBrush وFont الكائنات .
type: docs
weight: 320
url: /ar/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush/) و[`Font`](../../font/) الكائنات .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font/) التي تحدد تنسيق نص السلسلة. |
| brush | Brush | [`Brush`](../../brush/) التي تحدد لون وملمس النص المرسوم. |
| x | Single | إحداثي x للركن الأيسر العلوي للنص المرسوم. |
| y | Single | إحداثي ص للركن الأيسر العلوي للنص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush/) و[`Font`](../../font/) الكائنات .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font/) التي تحدد تنسيق نص السلسلة. |
| brush | Brush | [`Brush`](../../brush/) التي تحدد لون وملمس النص المرسوم. |
| point | PointF | [`PointF`](../../pointf/) هيكل يحدد الزاوية العلوية اليسرى للنص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أمثلة

يوضح هذا المثال استخدام فئة Font و SolidBrush لرسم سلاسل على سطح الصورة. يقوم المثال بإنشاء صورة جديدة ورسم الأشكال باستخدام Figures و GraphicsPath

```csharp
[C#]

// ينشئ مثيلاً للصورة
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // يقوم بإنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // ينشئ مثيلاً للخط
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    // أنشئ مثيلاً من SolidBrush باللون الأحمر
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // ارسم سلسلة
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // إنشاء خيارات التصدير.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // احفظ جميع التغييرات
    image.Save("C:\\temp\\output.gif", options);
}
```

### أنظر أيضا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush/) و[`Font`](../../font/) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font/) التي تحدد تنسيق نص السلسلة. |
| brush | Brush | [`Brush`](../../brush/) التي تحدد لون وملمس النص المرسوم. |
| x | Single | إحداثي x للركن الأيسر العلوي للنص المرسوم. |
| y | Single | إحداثي ص للركن الأيسر العلوي للنص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat/) يحدد سمات التنسيق ، مثل تباعد الأسطر والمحاذاة ، التي يتم تطبيقها على النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush/) و[`Font`](../../font/) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font/) التي تحدد تنسيق نص السلسلة. |
| brush | Brush | [`Brush`](../../brush/) التي تحدد لون وملمس النص المرسوم. |
| point | PointF | [`PointF`](../../pointf/) هيكل يحدد الزاوية العلوية اليسرى للنص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat/) يحدد سمات التنسيق ، مثل تباعد الأسطر والمحاذاة ، التي يتم تطبيقها على النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../../brush/) و[`Font`](../../font/) الكائنات .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font/) التي تحدد تنسيق نص السلسلة. |
| brush | Brush | [`Brush`](../../brush/) التي تحدد لون وملمس النص المرسوم. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) الهيكل الذي يحدد موقع النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../../brush/) و[`Font`](../../font/) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font/) التي تحدد تنسيق نص السلسلة. |
| brush | Brush | [`Brush`](../../brush/) التي تحدد لون وملمس النص المرسوم. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) الهيكل الذي يحدد موقع النص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat/) يحدد سمات التنسيق ، مثل تباعد الأسطر والمحاذاة ، التي يتم تطبيقها على النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* فارغ. -أو *brush* باطل. |

### أنظر أيضا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)



---
title: Graphics.DrawRectangles
second_title: Aspose.PSD لمرجع .NET API
description: Graphics طريقة. يرسم سلسلة من المستطيلات المحددة بواسطةRectangleF الهياكل .
type: docs
weight: 310
url: /ar/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

يرسم سلسلة من المستطيلات المحددة بواسطة[`RectangleF`](../../rectanglef/) الهياكل .

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض ونمط حدود المستطيلات. |
| rects | RectangleF[] | مصفوفة من[`RectangleF`](../../rectanglef/) الهياكل التي تمثل المستطيلات المراد رسمها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *rects* باطل. |

### أنظر أيضا

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

يرسم سلسلة من المستطيلات المحددة بواسطة[`Rectangle`](../../rectangle/) الهياكل .

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد لون وعرض ونمط حدود المستطيلات. |
| rects | Rectangle[] | مصفوفة من[`Rectangle`](../../rectangle/) الهياكل التي تمثل المستطيلات المراد رسمها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *rects* باطل. |

### أمثلة

يوضح هذا المثال إنشاء كائنات القلم واستخدامها. ينشئ المثال صورة جديدة ويرسم مستطيلات على سطح الصورة.

```csharp
[C#]

// إنشاء مثيل للصورة
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // إنشاء مثيل للرسومات وتهيئته باستخدام كائن صورة
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح واجهة الرسومات باللون الأبيض
    graphics.Clear(Aspose.PSD.Color.White);

    // قم بإنشاء مثيل من القلم باللون الأحمر والعرض 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    // قم بإنشاء مثيل لـ HatchBrush وعيّن خصائصه
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    // إنشاء مثيل من Pen
    // قم بتهيئته باستخدام كائن وعرض HatchBrush
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // إنشاء خيارات التصدير وتهيئتها.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // احفظ جميع التغييرات.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### أنظر أيضا

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* مساحة الاسم [Aspose.PSD](../../graphics/)
* المجسم [Aspose.PSD](../../../)



---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. ترسم سلسلة من المستطيلات المحددة بواسطة هياكل RectangleF"
type: docs
weight: 320
url: /ar/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

يرسم سلسلة من المستطيلات المحددة بواسطة هياكل [`RectangleF`](../../rectanglef/).

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | RectangleF[] | مصفوفة من هياكل [`RectangleF`](../../rectanglef/) التي تمثل المستطيلات المراد رسمها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو- *rects* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

يرسم سلسلة من المستطيلات المحددة بواسطة هياكل [`Rectangle`](../../rectangle/).

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لحدود المستطيلات. |
| rects | Rectangle[] | مصفوفة من هياكل [`Rectangle`](../../rectangle/) التي تمثل المستطيلات المراد رسمها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو- *rects* فارغ. |

## أمثلة

هذا المثال يوضح إنشاء واستخدام كائنات Pen. المثال ينشئ صورة جديدة ويرسم مستطيلات على سطح الصورة.

```csharp
[C#]

//إنشاء مثال من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء مثيل من Graphics وتهيئته باستخدام كائن Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics باللون الأبيض
    graphics.Clear(Aspose.PSD.Color.White);

    //إنشاء مثيل من Pen باللون الأحمر وعرض 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //إنشاء مثيل من HatchBrush وتعيين خصائصه
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //إنشاء مثيل من Pen
    //تهيئته باستخدام كائن HatchBrush والعرض
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //رسم مستطيلات عن طريق تحديد كائن Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //رسم مستطيلات عن طريق تحديد كائن Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // إنشاء خيارات التصدير وتهيئتها.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // احفظ جميع التغييرات.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



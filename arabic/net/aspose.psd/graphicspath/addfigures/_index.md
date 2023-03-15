---
title: GraphicsPath.AddFigures
second_title: Aspose.PSD لمرجع .NET API
description: GraphicsPath طريقة. إضافة أرقام جديدة .
type: docs
weight: 60
url: /ar/net/aspose.psd/graphicspath/addfigures/
---
## GraphicsPath.AddFigures method

إضافة أرقام جديدة .

```csharp
public void AddFigures(Figure[] figures)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| figures | Figure[] | الأرقام المراد إضافتها. |

### أمثلة

ينشئ هذا المثال صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures and GraphicsPath على سطح الصورة

```csharp
[C#]

// إنشاء مثيل للصورة
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // إنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // إنشاء مثيل لفئة GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    // إنشاء مثيل لفئة الشكل
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    // إضافة شكل إلى كائن الشكل
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    // إنشاء مثيل لفئة الشكل
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    // إضافة شكل إلى كائن الشكل
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    // إضافة كائن الشكل إلى GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    // رسم المسار باستخدام كائن القلم من اللون الأسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // إنشاء خيارات التصدير وتهيئتها.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // احفظ جميع التغييرات.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### أنظر أيضا

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* مساحة الاسم [Aspose.PSD](../../graphicspath/)
* المجسم [Aspose.PSD](../../../)



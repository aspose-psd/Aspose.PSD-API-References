---
title: GraphicsPath.AddFigure
second_title: Aspose.PSD لمرجع .NET API
description: GraphicsPath طريقة. يضيف رقمًا جديدًا .
type: docs
weight: 50
url: /ar/net/aspose.psd/graphicspath/addfigure/
---
## GraphicsPath.AddFigure method

يضيف رقمًا جديدًا .

```csharp
public void AddFigure(Figure figure)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| figure | Figure | الرقم المراد إضافته. |

### أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath و Graphics لإنشاء الأشكال ومعالجتها على سطح الصورة. مثال ينشئ صورة جديدة ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية ، يتم استدعاء طريقة DrawPath المعروضة بواسطة فئة الرسومات لعرض المسارات على السطح. أخيرًا يتم تصدير الصورة إلى تنسيق ملف Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // إضافة أشكال إلى كائن الشكل
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    // إضافة كائن الشكل إلى GraphicsPath
    graphicspath.AddFigure(figure);

    // رسم المسار باستخدام كائن القلم من اللون الأسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // قم بإنشاء مثيل لـ TiffOptions وعيّن خصائصه المتنوعة
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### أنظر أيضا

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* مساحة الاسم [Aspose.PSD](../../graphicspath/)
* المجسم [Aspose.PSD](../../../)



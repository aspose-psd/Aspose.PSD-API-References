---
title: Class PieShape
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Shapes.PieShape فصل. يمثل شكل دائري.
type: docs
weight: 5500
url: /ar/net/aspose.psd.shapes/pieshape/
---
## PieShape class

يمثل شكل دائري.

```csharp
public class PieShape : EllipseShape
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PieShape](pieshape/#constructor)() | يقوم بتهيئة مثيل جديد لملف`PieShape` فئة . |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | يقوم بتهيئة مثيل جديد لملف`PieShape` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | يحصل على حدود الكائن . |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | يحصل على مركز الشكل. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | الحصول على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | يحصل على نقطة المستطيل السفلي الأيسر . |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | يحصل على نقطة المستطيل العلوية اليسرى . |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | الحصول على ارتفاع المستطيل . |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | الحصول على عرض المستطيل . |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | يحصل على نقطة المستطيل السفلية اليمنى . |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | الحصول على نقطة المستطيل العلوية اليمنى . |
| override [Segments](../../aspose.psd.shapes/pieshape/segments/) { get; } | الحصول على شرائح الشكل . |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | الحصول على أو تحديد زاوية البداية . |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | الحصول على زاوية المسح أو تحديدها. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | يحصل على حدود الكائن . |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | يحصل على حدود الكائن . |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

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

* class [EllipseShape](../ellipseshape/)
* مساحة الاسم [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* المجسم [Aspose.PSD](../../)



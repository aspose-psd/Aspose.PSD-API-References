---
title: Class RectangleShape
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Shapes.RectangleShape فصل. يمثل شكل مستطيل.
type: docs
weight: 5530
url: /ar/net/aspose.psd.shapes/rectangleshape/
---
## RectangleShape class

يمثل شكل مستطيل.

```csharp
public class RectangleShape : RectangleProjectedShape
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | يقوم بتهيئة مثيل جديد لملف`RectangleShape` فئة . |
| [RectangleShape](rectangleshape/#constructor_1)(RectangleF) | يقوم بتهيئة مثيل جديد لملف`RectangleShape` فئة . |

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
| override [Segments](../../aspose.psd.shapes/rectangleshape/segments/) { get; } | الحصول على شرائح الشكل . |

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

* class [RectangleProjectedShape](../rectangleprojectedshape/)
* مساحة الاسم [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* المجسم [Aspose.PSD](../../)



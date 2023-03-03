---
title: Class PolygonShape
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Shapes.PolygonShape فصل. يمثل شكل مضلع.
type: docs
weight: 5510
url: /ar/net/aspose.psd.shapes/polygonshape/
---
## PolygonShape class

يمثل شكل مضلع.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | يقوم بتهيئة مثيل جديد لملف`PolygonShape` فئة . |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | يقوم بتهيئة مثيل جديد لملف`PolygonShape` فئة . |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | يقوم بتهيئة مثيل جديد لملف`PolygonShape` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | يحصل على حدود الكائن . |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | يحصل على مركز الشكل. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | الحصول على نقطة شكل النهاية . |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | الحصول على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | الحصول على نقاط المنحنى أو تعيينها . |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | الحصول على شرائح الشكل . |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | يحصل على نقطة شكل البداية . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن . |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن . |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | عكس ترتيب النقاط لهذا الشكل. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* مساحة الاسم [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* المجسم [Aspose.PSD](../../)



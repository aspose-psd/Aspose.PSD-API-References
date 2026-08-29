---
title: "الفئة PieShape"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Shapes.PieShape. تمثل شكل فطيرة"
type: docs
weight: 6000
url: /ar/net/aspose.psd.shapes/pieshape/
---
{{< psd/tize >}}
## PieShape class

يمثل شكل فطيرة.

```csharp
public class PieShape : EllipseShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PieShape](pieshape/#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة `PieShape`. |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | يقوم بتهيئة نسخة جديدة من الفئة `PieShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | يحصل على حدود الكائن. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | يحصل على مركز الشكل. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | يحصل على نقطة الزاوية اليسرى السفلية للمستطيل. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | يحصل على نقطة الزاوية اليسرى العليا للمستطيل. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | يحصل على ارتفاع المستطيل. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | يحصل على عرض المستطيل. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | يحصل على نقطة الزاوية اليمنى السفلية للمستطيل. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | يحصل على نقطة الزاوية اليمنى العليا للمستطيل. |
| override [Segments](../../aspose.psd.shapes/pieshape/segments/) { get; } | يحصل على مقاطع الشكل. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | يحصل أو يضبط زاوية البداية. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | يحصل أو يضبط زاوية القوس. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | يحصل على حدود الكائن. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

## أمثلة

هذا المثال ينشئ صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures و GraphicsPath على سطح الصورة

```csharp
[C#]

//إنشاء مثال من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء وتهيئة نسخة من فئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //إنشاء نسخة من فئة GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //إنشاء نسخة من فئة Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //إضافة Shape إلى كائن Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //إنشاء نسخة من فئة Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //إضافة Shape إلى كائن Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //رسم المسار باستخدام كائن Pen بلون أسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // إنشاء خيارات التصدير وتهيئتها.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // احفظ جميع التغييرات.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### انظر أيضًا

* class [EllipseShape](../ellipseshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



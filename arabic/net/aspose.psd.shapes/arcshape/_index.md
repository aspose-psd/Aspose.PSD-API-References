---
title: "الفئة ArcShape"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Shapes.ArcShape. تمثل شكل قوس"
type: docs
weight: 5960
url: /ar/net/aspose.psd.shapes/arcshape/
---
{{< psd/tize >}}
## ArcShape class

يمثل شكل قوس.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ArcShape](arcshape/#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة `ArcShape`. |
| [ArcShape](arcshape/#constructor_1)(RectangleF, float, float) | يقوم بتهيئة نسخة جديدة من الفئة `ArcShape`. |
| [ArcShape](arcshape/#constructor_2)(RectangleF, float, float, bool) | يقوم بتهيئة نسخة جديدة من الفئة `ArcShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | يحصل على حدود الكائن. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | يحصل على مركز الشكل. |
| [EndPoint](../../aspose.psd.shapes/arcshape/endpoint/) { get; } | يحصل على نقطة النهاية للشكل. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [IsClosed](../../aspose.psd.shapes/arcshape/isclosed/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة شكل مرتب مغلق لا يكون للنقطة البداية والنهاية أي معنى. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | يحصل على نقطة الزاوية اليسرى السفلية للمستطيل. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | يحصل على نقطة الزاوية اليسرى العليا للمستطيل. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | يحصل على ارتفاع المستطيل. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | يحصل على عرض المستطيل. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | يحصل على نقطة الزاوية اليمنى السفلية للمستطيل. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | يحصل على نقطة الزاوية اليمنى العليا للمستطيل. |
| override [Segments](../../aspose.psd.shapes/arcshape/segments/) { get; } | يحصل على مقاطع الشكل. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | يحصل أو يضبط زاوية البداية. |
| [StartPoint](../../aspose.psd.shapes/arcshape/startpoint/) { get; } | يحصل على نقطة بداية الشكل. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | يحصل أو يضبط زاوية القوس. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.psd.shapes/arcshape/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| [Reverse](../../aspose.psd.shapes/arcshape/reverse/)() | يعكس ترتيب النقاط لهذا الشكل. |
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

* class [PieShape](../pieshape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



---
title: "الفئة PolygonShape"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Shapes.PolygonShape. تمثل شكلاً متعدد الأضلاع"
type: docs
weight: 6010
url: /ar/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

يمثل شكل متعدد أضلاع.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | ينشئ مثيلاً جديداً من الفئة `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | ينشئ مثيلاً جديداً من الفئة `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | ينشئ مثيلاً جديداً من الفئة `PolygonShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | يحصل على حدود الكائن. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | يحصل على مركز الشكل. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | يحصل على نقطة النهاية للشكل. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقاً. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | يحصل أو يعيّن نقاط المنحنى. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | يحصل على مقاطع الشكل. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | يحصل على نقطة بداية الشكل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | يعكس ترتيب النقاط لهذا الشكل. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)



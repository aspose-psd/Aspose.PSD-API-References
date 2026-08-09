---
title: "الفئة Figure"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Figure. الشكل. حاوية للأشكال"
type: docs
weight: 1210
url: /ar/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

الشكل. حاوية للأشكال.

```csharp
public class Figure : ObjectWithBounds
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Figure](figure/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | يحصل أو يعيّن حدود الكائن. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. سيُحدث الشكل المغلق فرقًا فقط في الحالة التي تكون فيها أشكال الشكل الأول والأخير أشكالًا مستمرة. في هذه الحالة، سيتم ربط النقطة الأولى للشكل الأول بخط مستقيم من النقطة الأخيرة للشكل الأخير. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | يحصل على جميع مقاطع الشكل. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | يحصل على أشكال الشكل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | يضيف شكلاً إلى الشكل. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | يضيف مجموعة من الأشكال إلى الشكل. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | يزيل شكلاً من الشكل. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | يزيل مجموعة من الأشكال من الشكل. |
| [Reverse](../../aspose.psd/figure/reverse/)() | يعكس ترتيب الأشكال في هذا الشكل وترتيب نقاط الأشكال. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

## أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لرسم المسارات على السطح. أخيرًا يتم تصدير الصورة إلى تنسيق ملف Tiff.

```csharp
[C#]

//إنشاء نسخة من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء وتهيئة نسخة من فئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //إنشاء نسخة من فئة GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //إنشاء نسخة من فئة Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //إضافة أشكال إلى كائن Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.AddFigure(figure);

    //رسم المسار باستخدام كائن Pen بلون أسود
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //إنشاء نسخة من TiffOptions وضبط خصائصه المتنوعة
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### انظر أيضًا

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



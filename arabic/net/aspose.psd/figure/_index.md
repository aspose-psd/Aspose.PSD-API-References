---
title: Class Figure
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Figure فصل. الشكل. حاوية للأشكال .
type: docs
weight: 1200
url: /ar/net/aspose.psd/figure/
---
## Figure class

الشكل. حاوية للأشكال .

```csharp
public class Figure : ObjectWithBounds
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Figure](figure/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | الحصول على أو تعيين حدود الكائن. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | الحصول على أو تحديد قيمة تشير إلى ما إذا كان هذا الرقم مغلقًا. الشكل المغلق سيحدث فرقًا فقط في حالة الشكل الأول والأخير من الأشكال المستمرة. في مثل هذه الحالة ، ستكون النقطة الأولى من الشكل الأول متصلة بخط مستقيم من آخر نقطة في الشكل الأخير. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | يحصل على شرائح الشكل بالكامل. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | الحصول على أشكال الشكل. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | يضيف شكلاً إلى الشكل. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | يضيف نطاقًا من الأشكال إلى الشكل. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | يحصل على حدود الكائن . |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | يحصل على حدود الكائن . |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | يزيل شكل من الشكل. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | يزيل مجموعة من الأشكال من الشكل. |
| [Reverse](../../aspose.psd/figure/reverse/)() | عكس ترتيب أشكال الشكل وترتيب نقاط الأشكال. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | يطبق التحويل المحدد على الشكل. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)



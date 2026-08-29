---
title: "الفئة SolidBrush"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Brushes.SolidBrush. الفرشاة الصلبة مخصصة للرسم المستمر بلون محدد. لا يمكن وراثة هذه الفئة"
type: docs
weight: 200
url: /ar/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

الفرشاة الصلبة مخصصة للرسم باستمرار بلون محدد. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class SolidBrush : Brush
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | يُهيئ مثيلًا جديدًا من الفئة `SolidBrush`. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | يُهيئ مثيلًا جديدًا من الفئة `SolidBrush`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | يحصل أو يضبط لون الفرشاة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ نسخة عميقة جديدة من الـ[`Brush`](../../aspose.psd/brush/) الحالي. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |

## أمثلة

يستخدم هذا المثال الفئة Graphics لإنشاء أشكال بدائية على سطح الصورة. لتوضيح العملية، ينشئ المثال صورة جديدة بتنسيق PSD ويرسم أشكالًا بدائية على سطح الصورة باستخدام طرق Draw التي توفرها الفئة Graphics ثم يصدرها بتنسيق ملف PSD.

```csharp
[C#]

//إنشاء نسخة من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء وتهيئة نسخة من فئة Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics
    graphics.Clear(Color.Wheat);

    //ارسم قوسًا بتحديد كائن Pen ذو اللون الأسود، 
    //مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //ارسم منحنى بيزيير بتحديد كائن Pen ذو اللون الأزرق ونقاط الإحداثيات.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //ارسم منحنى بتحديد كائن Pen ذو اللون الأخضر ومصفوفة من النقاط
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //ارسم إهليلجًا باستخدام كائن Pen ومستطيل يحيطه
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //ارسم خطًا 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //ارسم قطعة فطيرة
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //ارسم مضلعًا بتحديد كائن Pen ذو اللون الأحمر ومصفوفة من النقاط
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //ارسم مستطيلًا
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //أنشئ كائن SolidBrush واضبط خصائصه المتنوعة
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //ارسم نصًا باستخدام كائن SolidBrush والخط، عند نقطة محددة
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //أنشئ نسخة من PngOptions واضبط خصائصه المتنوعة
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### انظر أيضًا

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



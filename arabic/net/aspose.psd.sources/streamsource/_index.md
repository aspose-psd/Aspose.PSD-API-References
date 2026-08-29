---
title: "الفئة StreamSource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Sources.StreamSource. تمثّل مصدر تدفق."
type: docs
weight: 6120
url: /ar/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

يمثّل مصدر تدفق.

```csharp
public sealed class StreamSource : Source
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | يُنشئ مثيلًا جديدًا من الفئة `StreamSource`. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | يُنشئ مثيلًا جديدًا من الفئة `StreamSource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | يحصل على قيمة تشير إلى ما إذا كان يجب التخلص من التدفق كلما تم التخلص من الحاوية. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | يحصل على التدفق. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | يحصل على حاوية الدفق. |

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

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)



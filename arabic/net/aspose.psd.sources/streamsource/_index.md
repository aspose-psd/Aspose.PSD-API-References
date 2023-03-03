---
title: Class StreamSource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Sources.StreamSource فصل. يمثل مصدر دفق .
type: docs
weight: 5620
url: /ar/net/aspose.psd.sources/streamsource/
---
## StreamSource class

يمثل مصدر دفق .

```csharp
public sealed class StreamSource : Source
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | يقوم بتهيئة مثيل جديد لملف`StreamSource` فئة . |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | يقوم بتهيئة مثيل جديد لملف`StreamSource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | يحصل على قيمة تشير إلى ما إذا كان يجب التخلص من التدفق عند التخلص من الحاوية. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | يحصل على الدفق . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | يحصل على حاوية التدفق . |

### أمثلة

يستخدم هذا المثال فئة الرسومات لإنشاء أشكال بدائية على سطح الصورة. لتوضيح العملية ، يقوم المثال بإنشاء صورة جديدة بتنسيق PSD ورسم أشكال بدائية على سطح الصورة باستخدام طرق الرسم التي تعرضها فئة الرسومات ثم تصديرها إلى تنسيق ملف PSD.

```csharp
[C#]

// إنشاء مثيل للصورة 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // إنشاء وتهيئة مثيل لفئة الرسومات
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح سطح الرسومات
    graphics.Clear(Color.Wheat);

    // ارسم قوسًا بتحديد كائن القلم ذي اللون الأسود ، 
    // أ مستطيل يحيط بالقوس وزاوية البدء وزاوية المسح
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // ارسم بيزير عن طريق تحديد كائن القلم ذي اللون الأزرق ونقاط التنسيق.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // ارسم منحنى عن طريق تحديد كائن القلم ذي اللون الأخضر ومجموعة من النقاط
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // ارسم شكلًا ناقصًا باستخدام كائن القلم والمستطيل المحيط
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //ارسم خطا 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // ارسم مقطع دائري
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // ارسم مضلعًا بتحديد كائن القلم ذي اللون الأحمر ومجموعة من النقاط
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // ارسم مستطيلاً
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    // إنشاء كائن SolidBrush وضبط خصائصه المختلفة
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // ارسم سلسلة باستخدام SolidBrush الكائن والخط ، في نقطة معينة
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    // قم بإنشاء مثيل لـ PngOptions وقم بتعيين خصائصه المختلفة
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // احفظ جميع التغييرات.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### أنظر أيضا

* class [Source](../../aspose.psd/source/)
* مساحة الاسم [Aspose.PSD.Sources](../../aspose.psd.sources/)
* المجسم [Aspose.PSD](../../)



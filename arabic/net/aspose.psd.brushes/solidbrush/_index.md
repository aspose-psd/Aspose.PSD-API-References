---
title: Class SolidBrush
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Brushes.SolidBrush فصل. الفرشاة المصمتة مخصصة للرسم المستمر بلون معين. لا يمكن توريث هذه الفئة.
type: docs
weight: 200
url: /ar/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

الفرشاة المصمتة مخصصة للرسم المستمر بلون معين. لا يمكن توريث هذه الفئة.

```csharp
public sealed class SolidBrush : Brush
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | يقوم بتهيئة مثيل جديد لملف`SolidBrush` فئة . |
| [SolidBrush](solidbrush/#constructor_1)(Color) | يقوم بتهيئة مثيل جديد لملف`SolidBrush` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | الحصول على لون الفرشاة أو تعيينه . |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ استنساخًا عميقًا جديدًا للتيار[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |

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

* class [Brush](../../aspose.psd/brush/)
* مساحة الاسم [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* المجسم [Aspose.PSD](../../)



---
title: Class HatchBrush
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Brushes.HatchBrush فصل. يحدد فرشاة مستطيلة بنمط فتحة ولون في المقدمة ولون للخلفية. لا يمكن توريث هذه الفئة.
type: docs
weight: 130
url: /ar/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

يحدد فرشاة مستطيلة بنمط فتحة ولون في المقدمة ولون للخلفية. لا يمكن توريث هذه الفئة.

```csharp
public sealed class HatchBrush : Brush
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | الحصول على أو تحديد لون المسافات بين خطوط التظليل . |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | الحصول على أو تحديد لون خطوط التظليل . |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | الحصول على أو تحديد نمط الفتحة لهذه الفرشاة. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | الحصول على عتامة الفرشاة أو ضبطها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الفرشاة مرئية بالكامل ، وتعني القيمة 1 أن الفرشاة غير شفافة تمامًا. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ استنساخًا عميقًا جديدًا للتيار[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |

### أمثلة

يوضح هذا المثال إنشاء كائنات القلم واستخدامها. ينشئ المثال صورة جديدة ويرسم مستطيلات على سطح الصورة.

```csharp
[C#]

// إنشاء مثيل للصورة
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // إنشاء مثيل للرسومات وتهيئته باستخدام كائن صورة
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // مسح واجهة الرسومات باللون الأبيض
    graphics.Clear(Aspose.PSD.Color.White);

    // قم بإنشاء مثيل من القلم باللون الأحمر والعرض 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    // قم بإنشاء مثيل لـ HatchBrush وعيّن خصائصه
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    // إنشاء مثيل من Pen
    // قم بتهيئته باستخدام كائن وعرض HatchBrush
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // رسم مستطيلات عن طريق تحديد كائن القلم
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // إنشاء خيارات التصدير وتهيئتها.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // احفظ جميع التغييرات.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### أنظر أيضا

* class [Brush](../../aspose.psd/brush/)
* مساحة الاسم [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* المجسم [Aspose.PSD](../../)



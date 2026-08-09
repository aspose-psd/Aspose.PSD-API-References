---
title: "الفئة HatchBrush"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Brushes.HatchBrush. تُعرّف فرشاة مستطيلة بنمط hatch style ولون أمامي ولون خلفي. لا يمكن وراثة هذه الفئة."
type: docs
weight: 130
url: /ar/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

يحدد فرشاة مستطيلة ذات نمط تظليل، ولون أمامي، ولون خلفية. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class HatchBrush : Brush
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HatchBrush](hatchbrush/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | يحصل أو يعيّن لون الفراغات بين خطوط hatch. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | يحصل أو يعيّن لون خطوط hatch. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | يحصل أو يعيّن نمط hatch لهذه الفرشاة. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | يحصل أو يضبط شفافية الفرشاة. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الفرشاة مرئية بالكامل، والقيمة 1 تعني أن الفرشاة معتمة بالكامل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | ينشئ نسخة عميقة جديدة من الـ[`Brush`](../../aspose.psd/brush/) الحالي. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |

## أمثلة

هذا المثال يوضح إنشاء واستخدام كائنات Pen. المثال ينشئ صورة جديدة ويرسم مستطيلات على سطح الصورة.

```csharp
[C#]

//إنشاء مثال من Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //إنشاء مثيل من Graphics وتهيئته باستخدام كائن Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //مسح سطح Graphics باللون الأبيض
    graphics.Clear(Aspose.PSD.Color.White);

    //إنشاء مثيل من Pen باللون الأحمر وعرض 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //إنشاء مثيل من HatchBrush وتعيين خصائصه
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //إنشاء مثيل من Pen
    //تهيئته باستخدام كائن HatchBrush والعرض
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //رسم مستطيلات عن طريق تحديد كائن Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //رسم مستطيلات عن طريق تحديد كائن Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // إنشاء خيارات التصدير وتهيئتها.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // احفظ جميع التغييرات.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### انظر أيضًا

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



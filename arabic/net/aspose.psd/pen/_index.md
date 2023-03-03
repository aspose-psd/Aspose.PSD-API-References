---
title: Class Pen
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.Pen فصل. يحدد كائنًا يستخدم لرسم الخطوط والمنحنيات والأشكال .
type: docs
weight: 5200
url: /ar/net/aspose.psd/pen/
---
## Pen class

يحدد كائنًا يستخدم لرسم الخطوط والمنحنيات والأشكال .

```csharp
public class Pen : TransparencySupporter
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | يقوم بتهيئة مثيل جديد لملف`Pen` فئة مع المحدد[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | يقوم بتهيئة مثيل جديد لملف`Pen` فئة باللون المحدد. |
| [Pen](pen/#constructor_1)(Brush, float) | يقوم بتهيئة مثيل جديد لملف`Pen` فئة مع المحدد[`Brush`](./brush/) و[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | يقوم بتهيئة مثيل جديد لملف`Pen` فئة مع المحدد[`Color`](./color/) و[`Width`](./width/) الخصائص . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | الحصول على أو تعيين المحاذاة لهذا الغرض`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | يحصل أو يحدد ملف[`Brush`](./brush/) التي تحدد سمات هذا`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | الحصول على اللون أو تحديده`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | الحصول على أو تعيين مصفوفة من القيم التي تحدد قلمًا مركبًا. قلم مركب يرسم خطًا مركبًا مكونًا من خطوط ومسافات متوازية. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | الحصول على أو تعيين حد أقصى مخصص لاستخدامه في نهاية السطور المرسومة بهذا`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | الحصول على غطاء مخصص أو تعيينه لاستخدامه في بداية السطور المرسومة بهذا`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | الحصول على أو تعيين نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | الحصول على المسافة من بداية السطر إلى بداية نمط الشرطة أو تحديدها . |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | الحصول على أو تعيين مصفوفة من الشرطات والمسافات المخصصة. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | الحصول على أو تحديد النمط المستخدم للخطوط المتقطعة المرسومة بهذا`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | الحصول على أو تحديد نمط الغطاء المستخدم في نهاية السطور المرسومة بهذا`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | الحصول على أو تحديد نمط الصلة لنهايات سطرين متتاليين مرسومين بهذا`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | الحصول على أو تعيين حد سماكة الوصلة في الزاوية الميتة . |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | الحصول على عتامة الكائن أو تعيينها. يجب أن تكون القيمة بين 0 و 1. تعني القيمة 0 أن الكائن مرئي بالكامل ، بينما تعني القيمة 1 أن الكائن معتم بالكامل. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | الحصول على نمط الخطوط المرسومة بهذا`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | الحصول على أو تحديد نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | الحصول على نسخة من التحويل الهندسي لهذا الغرض أو تعيينها`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | الحصول على أو تحديد عرض هذا`Pen` ، بوحدات كائن الرسومات المستخدمة للرسم . |

## طُرق

| اسم | وصف |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | تضرب مصفوفة التحويل لهذا الغرض`Pen` حسب المحدد[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | تضرب مصفوفة التحويل لهذا الغرض`Pen` حسب المحدد[`Matrix`](../matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | يعيد تعيين مصفوفة التحويل الهندسي لهذا الغرض`Pen` للهوية . |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | يدير التحويل الهندسي المحلي بالزاوية المحددة. تعمل هذه الطريقة على تمهيد الدوران للتحويل. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | يقوم بتدوير التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | مقياس التحويل الهندسي المحلي بالعوامل المحددة. تضيف هذه الطريقة مصفوفة القياس إلى التحويل. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | مقياس التحويل الهندسي المحلي بواسطة العوامل المحددة بالترتيب المحدد. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بواسطة هذا`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة. تضيف هذه الطريقة الترجمة إلى التحويل. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | يترجم التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

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

* class [TransparencySupporter](../transparencysupporter/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)



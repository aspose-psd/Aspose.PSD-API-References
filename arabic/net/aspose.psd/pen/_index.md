---
title: "الفئة Pen"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Pen. تُعرّف كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال."
type: docs
weight: 5690
url: /ar/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

يحدد كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال.

```csharp
public class Pen : TransparencySupporter
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | يُنشئ مثيلًا جديدًا من الفئة `Pen` باستخدام الـ[`Brush`](./brush/). |
| [Pen](pen/#constructor_2)(Color) | يُنشئ مثيلًا جديدًا من الفئة `Pen` باللون المحدد. |
| [Pen](pen/#constructor_1)(Brush, float) | يُنشئ مثيلًا جديدًا من الفئة `Pen` باستخدام الـ[`Brush`](./brush/) و[`Width`](./width/) المحددين. |
| [Pen](pen/#constructor_3)(Color, float) | يُنشئ مثيلًا جديدًا من الفئة `Pen` بالخصائص المحددة [`Color`](./color/) و[`Width`](./width/). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | يحصل أو يعيّن المحاذاة لهذا `Pen`. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | يحصل أو يعيّن الـ[`Brush`](./brush/) الذي يحدد سمات هذا `Pen`. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | يحصل أو يعيّن لون هذا `Pen`. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | يحصل أو يعيّن مصفوفة القيم التي تحدد قلمًا مركبًا. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية وفراغات. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | يحصل أو يعيّن غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا `Pen`. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | يحصل أو يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا `Pen`. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | يحصل أو يضبط المسافة من بداية الخط إلى بداية نمط الشرط. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | يحصل أو يضبط مصفوفة من الشرطات والمسافات المخصصة. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | يحصل أو يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | يحصل أو يضبط نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا `Pen`. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | يحصل أو يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | يحصل أو يضبط حد سمك الوصل عند زاوية ميتير. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | يحصل أو يضبط شفافية الكائن. يجب أن تكون القيمة بين 0 و 1. القيمة 0 تعني أن الكائن مرئي بالكامل، والقيمة 1 تعني أن الكائن غير شفاف تماماً. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | يحصل على نمط الخطوط المرسومة بهذا `Pen`. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | يحصل أو يضبط نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا `Pen`. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | يحصل أو يضبط نسخة من التحويل الهندسي لهذا `Pen`. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | يحصل أو يضبط عرض هذا `Pen`، بوحدات كائن Graphics المستخدم للرسم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | يضرب مصفوفة التحويل لهذا `Pen` بالمصفوفة المحددة [`Matrix`](../matrix/). |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | يضرب مصفوفة التحويل لهذا `Pen` بالمصفوفة المحددة [`Matrix`](../matrix/) بالترتيب المحدد. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | يعيد تعيين مصفوفة التحويل الهندسي لهذا `Pen` إلى هوية. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | يدور التحويل الهندسي المحلي بالزاوية المحددة. تُضيف هذه الطريقة الدوران إلى بداية التحويل. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة. تُضيف هذه الطريقة مصفوفة التكبير إلى بداية التحويل. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بهذا `Pen`. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. تُضيف هذه الطريقة الإزاحة إلى بداية التحويل. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |

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

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



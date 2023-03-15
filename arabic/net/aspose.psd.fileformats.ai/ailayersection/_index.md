---
title: Class AiLayerSection
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Ai.AiLayerSection فصل. قسم طبقة تنسيق Ai
type: docs
weight: 1270
url: /ar/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

قسم طبقة تنسيق Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | الحصول على أو تعيين مكون اللون الأزرق. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | الحصول على رقم اللون أو تحديده. -1 هي قيمة اللون المخصصة من خصائص الأحمر والأخضر والأزرق . يحدد إعداد لون الطبقة. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | الحصول على القيمة المعتمة أو تعيينها كنسبة مئوية . تقليل كثافة الصور المرتبطة والصور النقطية الموجودة في الطبقة إلى النسبة المئوية المحددة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | الحصول على أو تعيين مكون اللون الأخضر. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت هذه الطبقة باهتة. يقلل من شدة الصور المرتبطة والصور النقطية الموجودة في الطبقة. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت هذه الطبقة مؤمنة . يمنع التغييرات على العنصر. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت هذه الطبقة هي معاينة . يعرض العمل الفني الموجود في الطبقة بالألوان بدلاً من الخطوط العريضة . |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت هذه الطبقة قد تمت طباعتها. يجعل العمل الفني الموجود في الطبقة قابلاً للطباعة إذا كان صحيحًا. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | الحصول على قيمة أو تعيينها تشير إلى ما إذا كانت هذه الطبقة ستظهر أم لا. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت هذه الطبقة عبارة عن طبقة قالب. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | الحصول على اسم الطبقة أو تعيينه . يحدد اسم العنصر كما يظهر في لوحة الطبقات. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | الحصول على الصور النقطية . |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | الحصول على أو تعيين مكون اللون الأحمر. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | يضيف الصورة النقطية. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | يحصل على بيانات السلسلة . |

### أمثلة

يوضح الكود التالي كيفية تحميل إعدادات الصور النقطية في ملفات تنسيق AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### أنظر أيضا

* class [AiDataSection](../aidatasection/)
* مساحة الاسم [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* المجسم [Aspose.PSD](../../)



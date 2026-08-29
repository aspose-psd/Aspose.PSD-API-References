---
title: "الفئة AiLayerSection"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Ai.AiLayerSection. قسم طبقة تنسيق Ai"
type: docs
weight: 1280
url: /ar/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

قسم طبقة تنسيق Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | يحصل أو يعيّن مكوّن اللون الأزرق. |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | يحصل أو يعيّن فهرس اللون. يمكن أن يأخذ هذا المتغيّر قيمًا بين –1 و 26. كل عدد صحيح يمثل لونًا يمكن تعيينه للطبقة لأغراض تعريف المستخدم. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | يحصل أو يعيّن رقم اللون. القيمة -1 هي قيمة اللون المخصصة من خصائص الأحمر والأخضر والأزرق. يحدد إعداد لون الطبقة. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | يحصل أو يعيّن قيمة التعتيم كنسبة مئوية. يقلل شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة إلى النسبة المحددة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | يحصل أو يعيّن مكوّن اللون الأخضر. |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على أقنعة متعددة الطبقات. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مخفّضة. يقلل شدة الصور المرتبطة وصور البت ماب الموجودة في الطبقة. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مقفلة. يمنع التغييرات على العنصر. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة في وضع المعاينة. يعرض الأعمال الفنية الموجودة في الطبقة بالألوان بدلاً من الخطوط الخارجية. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة مطبوعة. يجعل الأعمال الفنية الموجودة في الطبقة قابلة للطباعة إذا كانت true. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة معروضة. يعرض جميع الأعمال الفنية الموجودة في الطبقة على لوحة الرسم إذا كانت true. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه الطبقة طبقة قالب. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | يحصل أو يعيّن اسم الطبقة. يحدد اسم العنصر كما يظهر في لوحة الطبقات. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | يحصل على الصور النقطية. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | يحصل أو يضبط مكوّن اللون الأحمر. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | يضيف الصورة النقطية. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | يحصل على بيانات السلسلة. |

## أمثلة

الكود التالي يوضح كيفية تحميل إعدادات الصور النقطية في ملفات تنسيق AI.

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

### انظر أيضًا

* class [AiDataSection](../aidatasection/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



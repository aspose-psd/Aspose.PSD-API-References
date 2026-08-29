---
title: "الفئة AiRasterImageSection"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Ai.AiRasterImageSection class. قسم صورة AI النقطية."
type: docs
weight: 1290
url: /ar/net/aspose.psd.fileformats.ai/airasterimagesection/
---
{{< psd/tize >}}
## AiRasterImageSection class

قسم صورة الراستر AI

```csharp
public sealed class AiRasterImageSection
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.ai/airasterimagesection/angle/) { get; } | يحصل على الزاوية. |
| [Height](../../aspose.psd.fileformats.ai/airasterimagesection/height/) { get; } | يحصل على الارتفاع. |
| [ImageRectangle](../../aspose.psd.fileformats.ai/airasterimagesection/imagerectangle/) { get; } | يحصل على مستطيل الصورة. |
| [LeftBottomShift](../../aspose.psd.fileformats.ai/airasterimagesection/leftbottomshift/) { get; } | يحصل على إزاحة اليسار السفلي. |
| [Name](../../aspose.psd.fileformats.ai/airasterimagesection/name/) { get; } | يحصل على اسم الصورة النقطية. |
| [OffsetX](../../aspose.psd.fileformats.ai/airasterimagesection/offsetx/) { get; } | يحصل على الإزاحة X. |
| [OffsetY](../../aspose.psd.fileformats.ai/airasterimagesection/offsety/) { get; } | يحصل على الإزاحة Y. |
| [Pixels](../../aspose.psd.fileformats.ai/airasterimagesection/pixels/) { get; } | يحصل على مصفوفة بكسلات اللون من نوع int. |
| [Width](../../aspose.psd.fileformats.ai/airasterimagesection/width/) { get; } | يحصل على العرض. |

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

* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)



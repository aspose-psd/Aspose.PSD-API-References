---
title: Class AiRasterImageSection
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Ai.AiRasterImageSection कक्ष. एआई रेखपुंज छव अनुभग
type: docs
weight: 1280
url: /hi/net/aspose.psd.fileformats.ai/airasterimagesection/
---
## AiRasterImageSection class

एआई रेखापुंज छवि अनुभाग

```csharp
public sealed class AiRasterImageSection
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.ai/airasterimagesection/angle/) { get; } | कोण मिलता है। |
| [Height](../../aspose.psd.fileformats.ai/airasterimagesection/height/) { get; } | ऊंचाई मिलती है। |
| [ImageRectangle](../../aspose.psd.fileformats.ai/airasterimagesection/imagerectangle/) { get; } | छवि आयत प्राप्त करता है। |
| [LeftBottomShift](../../aspose.psd.fileformats.ai/airasterimagesection/leftbottomshift/) { get; } | बाएँ नीचे की ओर शिफ्ट हो जाता है। |
| [Name](../../aspose.psd.fileformats.ai/airasterimagesection/name/) { get; } | रेखापुंज छवि का नाम प्राप्त करता है। |
| [OffsetX](../../aspose.psd.fileformats.ai/airasterimagesection/offsetx/) { get; } | ऑफसेट एक्स प्राप्त करता है। |
| [OffsetY](../../aspose.psd.fileformats.ai/airasterimagesection/offsety/) { get; } | ऑफ़सेट वाई प्राप्त करता है। |
| [Pixels](../../aspose.psd.fileformats.ai/airasterimagesection/pixels/) { get; } | इंट कलर पिक्सल की सरणी प्राप्त करता है। |
| [Width](../../aspose.psd.fileformats.ai/airasterimagesection/width/) { get; } | चौड़ाई मिलती है। |

### उदाहरण

निम्नलिखित कोड दर्शाता है कि एआई प्रारूप फाइलों में रेखापुंज छवियों की सेटिंग्स को कैसे लोड किया जाए।

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

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* सभा [Aspose.PSD](../../)



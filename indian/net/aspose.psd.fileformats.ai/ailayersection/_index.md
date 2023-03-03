---
title: Class AiLayerSection
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Ai.AiLayerSection कक्ष. एआई प्ररूप परत अनुभग
type: docs
weight: 1270
url: /hi/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

एआई प्रारूप परत अनुभाग

```csharp
public sealed class AiLayerSection : AiDataSection
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | नीले रंग के घटक को प्राप्त या सेट करता है। |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | रंग संख्या प्राप्त या सेट करता है। -1 लाल, हरे, नीले गुणों से कस्टम रंग मान है। परत की रंग सेटिंग निर्दिष्ट करता है। |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | मंद मान को प्रतिशत के रूप में प्राप्त या सेट करता है। परत में निहित लिंक की गई छवियों और बिटमैप छवियों की तीव्रता को निर्दिष्ट प्रतिशत तक कम कर देता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | हरे रंग के घटक को प्राप्त या सेट करता है। |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | यह इंगित करता है कि यह परत मंद है या नहीं, यह इंगित करता है या सेट करता है। परत में निहित लिंक की गई छवियों और बिटमैप छवियों की तीव्रता को कम करता है। |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | यह इंगित करता है कि यह परत लॉक है या नहीं, यह मान प्राप्त या सेट करता है। आइटम में परिवर्तन रोकता है। |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | एक मान प्राप्त या सेट करता है जो बताता है कि यह परत पूर्वावलोकन है या नहीं। परत में निहित कलाकृति को रूपरेखा के बजाय रंग में प्रदर्शित करता है। |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | यह इंगित करता है कि यह परत मुद्रित है या नहीं, यह इंगित करता है या सेट करता है। परत में निहित कलाकृति को सही होने पर प्रिंट करने योग्य बनाता है। |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह परत दिखाई गई है या नहीं। सही होने पर आर्टबोर्ड पर परत में निहित सभी कलाकृति प्रदर्शित करता है। |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि यह परत एक टेम्पलेट परत है या नहीं। |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | परत नाम प्राप्त या सेट करता है। आइटम का नाम निर्दिष्ट करता है जैसा कि परत पैनल में दिखाई देता है। |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | रेखापुंज चित्र प्राप्त करता है। |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | लाल रंग के घटक को प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | रेखापुंज छवि जोड़ता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | स्ट्रिंग डेटा प्राप्त करता है। |

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

* class [AiDataSection](../aidatasection/)
* नाम स्थान [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* सभा [Aspose.PSD](../../)



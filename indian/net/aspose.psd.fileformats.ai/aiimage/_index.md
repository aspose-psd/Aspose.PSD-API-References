---
title: Class AiImage
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Ai.AiImage कक्ष. एडब इलस्ट्रेटर एआई इमेज
type: docs
weight: 1260
url: /hi/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

एडोब इलस्ट्रेटर (एआई) इमेज

```csharp
public sealed class AiImage : Image
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [AiImage](aiimage/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि स्वचालित समायोजन पैलेट है या नहीं। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त या सेट करता है। |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | छवि बिट्स प्रति पिक्सेल संख्या प्राप्त करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि सीमा प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [Container](../../aspose.psd/image/container/) { get; } | हो जाता है[`Image`](../../aspose.psd/image/) कंटेनर. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | डेटा अनुभाग प्राप्त करता है। |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | फ़ाइल स्वरूप का मान प्राप्त करता है |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | फाइनलाइज सेक्शन प्राप्त करता है। |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | एक मान प्राप्त या सेट करता है जो बताता है कि छवि में पृष्ठभूमि का रंग है या नहीं। |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | हेडर प्राप्त करता है। |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | छवि ऊंचाई प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनीटर प्राप्त या सेट करता है। |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि वस्तु का डेटा वर्तमान में कैश किया गया है और कोई डेटा पढ़ने की आवश्यकता नहीं है। |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | परत अनुभाग प्राप्त करता है। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। रंग पैलेट का उपयोग तब नहीं किया जाता है जब पिक्सेल को सीधे प्रदर्शित किया जाता है. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | सेटअप अनुभाग प्राप्त करता है। |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Adobe Illustrator का संस्करण प्रारूप प्राप्त करता है |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | छवि चौड़ाई प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | एआई लेयर सेक्शन जोड़ता है। |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | डेटा को कैश करता है और यह सुनिश्चित करता है कि अंतर्निहित से कोई अतिरिक्त डेटा लोड नहीं किया जाएगा[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | यह निर्धारित करता है कि छवि को पास किए गए सहेजे गए विकल्पों द्वारा दर्शाए गए निर्दिष्ट फ़ाइल स्वरूप में सहेजा जा सकता है या नहीं। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह बिट-डेप्थ और मूल छवि के अन्य मापदंडों को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम एक काले-सफेद PNG छवि को 1 बिट प्रति पिक्सेल के साथ लोड करते हैं और फिर इसे का उपयोग करके सहेजें[`Save`](../../aspose.psd/datastreamsupporter/save/) विधि, 8-बिट प्रति पिक्सेल के साथ आउटपुट पीएनजी छवि का उत्पादन किया जाएगा।[`Save`](../../aspose.psd/image/save/)दूसरे पैरामीटर के रूप में विधि। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | छवि का आकार बदलता है। डिफ़ॉल्टLeftTopToLeftTopप्रयोग किया जाता है. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | छवि का आकार बदलता है। |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | छवि का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | छवि को घुमाता है, फ़्लिप करता है या घुमाता है और फ़्लिप करता है. |
| [Save](../../aspose.psd/image/save/)() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है. |

### उदाहरण

निम्न उदाहरण प्रदर्शित करता है कि कैसे आप Adobe Illustrator फ़ाइलों को Aspose.PSD में PDF स्वरूप में निर्यात कर सकते हैं

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

निम्न उदाहरण दर्शाता है कि कैसे आप AI फ़ाइल को Aspose.PSD में PSD और PNG प्रारूप में निर्यात कर सकते हैं

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

निम्न उदाहरण PSD, PNG, JPG, GIF और TIF स्वरूपों में निर्यात करने वाले AI प्रारूप के समर्थन को प्रदर्शित करता है।

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### यह सभी देखें

* class [Image](../../aspose.psd/image/)
* नाम स्थान [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* सभा [Aspose.PSD](../../)



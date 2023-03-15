---
title: Class VectorImage
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.VectorImage कक्ष. वेक्टर छव सभ प्रकर क वेक्टर छवयं के लए आधर वर्ग है
type: docs
weight: 5720
url: /hi/net/aspose.psd/vectorimage/
---
## VectorImage class

वेक्टर छवि सभी प्रकार की वेक्टर छवियों के लिए आधार वर्ग है।

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि स्वचालित समायोजन पैलेट है या नहीं। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त या सेट करता है। |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | छवि बिट्स प्रति पिक्सेल संख्या प्राप्त करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि सीमा प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [Container](../../aspose.psd/image/container/) { get; } | हो जाता है[`Image`](../image/) कंटेनर. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | फ़ाइल स्वरूप का मान प्राप्त करता है |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | एक मान प्राप्त या सेट करता है जो बताता है कि छवि में पृष्ठभूमि का रंग है या नहीं। |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | छवि ऊंचाई प्राप्त करता है। |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | वस्तु की ऊंचाई इंच में प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनीटर प्राप्त या सेट करता है। |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि वस्तु का डेटा वर्तमान में कैश किया गया है और कोई डेटा पढ़ने की आवश्यकता नहीं है। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। रंग पैलेट का उपयोग तब नहीं किया जाता है जब पिक्सेल को सीधे प्रदर्शित किया जाता है. |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | वस्तु का आकार, इंच में मिलता है। |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | छवि चौड़ाई प्राप्त करता है। |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | वस्तु की चौड़ाई इंच में प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | डेटा को कैश करता है और यह सुनिश्चित करता है कि अंतर्निहित से कोई अतिरिक्त डेटा लोड नहीं किया जाएगा[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | यह निर्धारित करता है कि छवि को पास किए गए सहेजे गए विकल्पों द्वारा दर्शाए गए निर्दिष्ट फ़ाइल स्वरूप में सहेजा जा सकता है या नहीं। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह बिट-डेप्थ और मूल छवि के अन्य मापदंडों को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम एक काले-सफेद PNG छवि को 1 बिट प्रति पिक्सेल के साथ लोड करते हैं और फिर इसे का उपयोग करके सहेजें[`Save`](../datastreamsupporter/save/) विधि, 8-बिट प्रति पिक्सेल के साथ आउटपुट पीएनजी छवि का उत्पादन किया जाएगा।[`Save`](../image/save/)दूसरे पैरामीटर के रूप में विधि। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | छवि का आकार बदलता है। डिफ़ॉल्टLeftTopToLeftTopप्रयोग किया जाता है. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | छवि का आकार बदलता है। |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | छवि का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | छवि को घुमाता है, फ़्लिप करता है या घुमाता है और फ़्लिप करता है. |
| [Save](../../aspose.psd/image/save/)() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है. |

### यह सभी देखें

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)



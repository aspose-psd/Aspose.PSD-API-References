---
title: "क्लास VectorImage"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.VectorImage क्लास। वेक्टर इमेज सभी प्रकार की वेक्टर छवियों के लिए आधार क्लास है।"
type: docs
weight: 6220
url: /hi/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

वेक्टर इमेज सभी प्रकार की वेक्टर इमेजों के लिए बेस क्लास है।

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | स्वचालित समायोजन पैलेट को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त करता है या सेट करता है। |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | छवि के बिट्स प्रति पिक्सेल की गिनती प्राप्त करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि की सीमाएँ प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../image/) कंटेनर प्राप्त करता है। |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | छवि की ऊँचाई प्राप्त करता है। |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | इंच में वस्तु की ऊँचाई प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनिटर को प्राप्त करता है या सेट करता है। |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ना आवश्यक नहीं है। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे प्रतिनिधित्व किए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता। |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | इंच में वस्तु का आकार प्राप्त करता है। |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | छवि पैलेट उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | छवि की चौड़ाई प्राप्त करता है। |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | इंच में वस्तु की चौड़ाई प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | डेटा को कैश करता है और सुनिश्चित करता है कि आधारभूत [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) से कोई अतिरिक्त डेटा लोडिंग न हो। |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | निर्धारित करता है कि क्या छवि को पास किए गए सहेजने विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह मूल इमेज की बिट-डेप्थ और अन्य पैरामीटर को अपरिवर्तित रखने में सहायक हो सकता है। उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल के साथ काली-सफ़ेद PNG इमेज लोड करते हैं और फिर [`Save`](../datastreamsupporter/save/) मेथड का उपयोग करके इसे सहेजते हैं, तो आउटपुट PNG इमेज 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी। इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG इमेज सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने विकल्प प्राप्त करें और उन्हें दूसरे पैरामीटर के रूप में [`Save`](../image/save/) मेथड को पास करें। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | इमेज का आकार बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | इमेज का आकार बदलता है। |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | इमेज का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | इमेज को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है। |
| [Save](../../aspose.psd/image/save/)() | इमेज डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है। |

### देखें भी

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



---
title: Class Image
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Image कक्ष. छव सभ प्रकर क छवयं के लए आधर वर्ग है
type: docs
weight: 4590
url: /hi/net/aspose.psd/image/
---
## Image class

छवि सभी प्रकार की छवियों के लिए आधार वर्ग है।

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि स्वचालित समायोजन पैलेट है या नहीं। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त या सेट करता है। |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | छवि बिट्स प्रति पिक्सेल संख्या प्राप्त करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि सीमा प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [Container](../../aspose.psd/image/container/) { get; } | हो जाता है`Image` कंटेनर. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | फ़ाइल स्वरूप का मान प्राप्त करता है |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | एक मान प्राप्त या सेट करता है जो बताता है कि छवि में पृष्ठभूमि का रंग है या नहीं। |
| abstract [Height](../../aspose.psd/image/height/) { get; } | छवि ऊंचाई प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनीटर प्राप्त या सेट करता है। |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि वस्तु का डेटा वर्तमान में कैश किया गया है और कोई डेटा पढ़ने की आवश्यकता नहीं है। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। रंग पैलेट का उपयोग तब नहीं किया जाता है जब पिक्सेल को सीधे प्रदर्शित किया जाता है. |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| abstract [Width](../../aspose.psd/image/width/) { get; } | छवि चौड़ाई प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | निर्दिष्ट निर्माण विकल्पों का उपयोग करके एक नई छवि बनाता है। |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | निर्दिष्ट स्ट्रीम से एक नई छवि लोड करता है। |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | निर्दिष्ट फ़ाइल से एक नई छवि लोड करता है। |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | निर्दिष्ट स्ट्रीम से एक नई छवि लोड करता है। |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | निर्दिष्ट फ़ाइल से एक नई छवि लोड करता है। |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | डेटा को कैश करता है और यह सुनिश्चित करता है कि अंतर्निहित से कोई अतिरिक्त डेटा लोड नहीं किया जाएगा[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | यह निर्धारित करता है कि छवि को पास किए गए सहेजे गए विकल्पों द्वारा दर्शाए गए निर्दिष्ट फ़ाइल स्वरूप में सहेजा जा सकता है या नहीं। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह बिट-डेप्थ और मूल छवि के अन्य मापदंडों को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम एक काले-सफेद PNG छवि को 1 बिट प्रति पिक्सेल के साथ लोड करते हैं और फिर इसे का उपयोग करके सहेजें[`Save`](../datastreamsupporter/save/) विधि, 8-बिट प्रति पिक्सेल के साथ आउटपुट पीएनजी छवि का उत्पादन किया जाएगा।[`Save`](./save/)दूसरे पैरामीटर के रूप में विधि। |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | छवि का आकार बदलता है। डिफ़ॉल्टLeftTopToLeftTopप्रयोग किया जाता है. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | छवि का आकार बदलता है। |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | छवि का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | छवि को घुमाता है, फ़्लिप करता है या घुमाता है और फ़्लिप करता है. |
| [Save](../../aspose.psd/image/save/#save)() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | निर्धारित करता है कि छवि को निर्दिष्ट स्ट्रीम से लोड किया जा सकता है या नहीं। |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | निर्धारित करता है कि छवि को निर्दिष्ट फ़ाइल पथ से लोड किया जा सकता है या नहीं। |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | निर्धारित करता है कि छवि को निर्दिष्ट स्ट्रीम से लोड किया जा सकता है और वैकल्पिक रूप से निर्दिष्ट का उपयोग कर*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | निर्धारित करता है कि छवि को निर्दिष्ट फ़ाइल पथ से और वैकल्पिक रूप से निर्दिष्ट खुले विकल्पों का उपयोग करके लोड किया जा सकता है या नहीं। |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | फ़ाइल स्वरूप प्राप्त करता है. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | फ़ाइल स्वरूप प्राप्त करता है. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | आयत प्राप्त करता है जो वर्तमान छवि में फिट बैठता है। |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | आयत प्राप्त करता है जो वर्तमान छवि में फिट बैठता है। |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | आनुपातिक ऊंचाई प्राप्त करता है। |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | आनुपातिक चौड़ाई प्राप्त करता है। |

### उदाहरण

यह उदाहरण PsdOptions उदाहरण के स्रोत गुण द्वारा निर्दिष्ट डिस्क स्थान पर एक नई छवि फ़ाइल बनाता है। वास्तविक छवि बनाने से पहले PsdOptions उदाहरण के लिए कई गुण सेट किए गए हैं। विशेष रूप से स्रोत संपत्ति, जो इस मामले में वास्तविक डिस्क स्थान को संदर्भित करती है।

```csharp
[C#]

// PsdOptions का एक उदाहरण बनाएं और इसके विभिन्न गुणों को सेट करें
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource का एक उदाहरण बनाएं और इसे PsdOptions के उदाहरण के लिए स्रोत के रूप में असाइन करें
// दूसरा बूलियन पैरामीटर निर्धारित करता है कि बनाई जाने वाली फ़ाइल टेम्पोरल है या नहीं
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// इमेज का एक उदाहरण बनाएं और क्रिएट मेथड को कॉल करके PsdOptions के उदाहरण के साथ इसे इनिशियलाइज़ करें
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // कुछ इमेज प्रोसेसिंग करें

    // सभी परिवर्तनों को सहेजें
    image.Save();
}
```

### यह सभी देखें

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)



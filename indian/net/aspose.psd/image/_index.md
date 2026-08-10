---
title: "Image वर्ग"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Image वर्ग। इमेज सभी प्रकार की इमेजों के लिए बेस वर्ग है।"
type: docs
weight: 5060
url: /hi/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

इमेज सभी प्रकार की छवियों के लिए बेस क्लास है।

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | स्वचालित समायोजन पैलेट को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त करता है या सेट करता है। |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | छवि के बिट्स प्रति पिक्सेल की गिनती प्राप्त करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि की सीमाएँ प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [Container](../../aspose.psd/image/container/) { get; } | `Image` कंटेनर को प्राप्त करता है। |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| abstract [Height](../../aspose.psd/image/height/) { get; } | छवि की ऊँचाई प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनिटर को प्राप्त करता है या सेट करता है। |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ना आवश्यक नहीं है। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे प्रतिनिधित्व किए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता। |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | छवि पैलेट उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| abstract [Width](../../aspose.psd/image/width/) { get; } | छवि की चौड़ाई प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | निर्दिष्ट निर्माण विकल्पों का उपयोग करके नई इमेज बनाता है। |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | निर्दिष्ट स्ट्रीम से नई इमेज लोड करता है। |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | निर्दिष्ट फ़ाइल से नई इमेज लोड करता है। |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | निर्दिष्ट स्ट्रीम से नई इमेज लोड करता है। |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | निर्दिष्ट फ़ाइल से नई इमेज लोड करता है। |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | डेटा को कैश करता है और सुनिश्चित करता है कि आधारभूत [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) से कोई अतिरिक्त डेटा लोडिंग न हो। |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | निर्धारित करता है कि क्या छवि को पास किए गए सहेजने विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह मूल इमेज की बिट-डेप्थ और अन्य पैरामीटर को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले ब्लैक-व्हाइट PNG इमेज को लोड करते हैं और फिर इसे [`Save`](../datastreamsupporter/save/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG इमेज 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी। इसे रोकने और 1-बिट प्रति पिक्सेल वाले PNG इमेज को सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें दूसरे पैरामीटर के रूप में [`Save`](./save/) मेथड को पास करें। |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | इमेज का आकार बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | इमेज का आकार बदलता है। |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | इमेज का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | इमेज को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है। |
| [Save](../../aspose.psd/image/save/#save)() | इमेज डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है। |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | निर्धारित करता है कि इमेज निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं। |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | निर्धारित करता है कि इमेज निर्दिष्ट फ़ाइल पाथ से लोड की जा सकती है या नहीं। |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | निर्धारित करता है कि इमेज निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट *loadOptions* का उपयोग करके। |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | निर्धारित करता है कि इमेज निर्दिष्ट फ़ाइल पाथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट ओपन विकल्पों का उपयोग करके। |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | वर्तमान छवि में फिट होने वाला आयत प्राप्त करता है। |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | वर्तमान छवि में फिट होने वाला आयत प्राप्त करता है। |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | एक अनुपातिक ऊँचाई प्राप्त करता है। |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | एक अनुपातिक चौड़ाई प्राप्त करता है। |

## उदाहरण

यह उदाहरण PsdOptions इंस्टेंस की Source प्रॉपर्टी द्वारा निर्दिष्ट डिस्क स्थान पर एक नई Image फ़ाइल बनाता है। वास्तविक इमेज बनाने से पहले PsdOptions इंस्टेंस की कई प्रॉपर्टी सेट की जाती हैं। विशेष रूप से Source प्रॉपर्टी, जो इस मामले में वास्तविक डिस्क स्थान को दर्शाती है।

```csharp
[C#]

//PsdOptions का एक इंस्टेंस बनाएँ और उसकी विभिन्न प्रॉपर्टी सेट करें।
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource का एक इंस्टेंस बनाएँ और उसे PsdOptions इंस्टेंस के लिए Source के रूप में असाइन करें।
//दूसरा Boolean पैरामीटर निर्धारित करता है कि बनाई जाने वाली फ़ाइल अस्थायी है या नहीं।
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image का एक इंस्टेंस बनाएँ और Create मेथड को कॉल करके उसे PsdOptions के इंस्टेंस से इनिशियलाइज़ करें।
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //कुछ छवि प्रसंस्करण करें।

    // सभी परिवर्तन सहेजें।
    image.Save();
}
```

### देखें भी

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



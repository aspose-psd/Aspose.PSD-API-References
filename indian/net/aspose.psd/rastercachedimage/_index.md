---
title: "क्लास RasterCachedImage"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.RasterCachedImage क्लास। रास्टर ग्राफ़िक्स ऑपरेशन्स का समर्थन करने वाली रास्टर इमेज का प्रतिनिधित्व करता है। आवश्यकता पड़ने पर यह इमेज पिक्सेल डेटा को कैश करता है।"
type: docs
weight: 5810
url: /hi/net/aspose.psd/rastercachedimage/
---
{{< psd/tize >}}
## RasterCachedImage class

रास्टर ग्राफ़िक्स ऑपरेशन्स को समर्थन देने वाली रास्टर इमेज का प्रतिनिधित्व करता है। आवश्यकता पड़ने पर यह इमेज पिक्सेल डेटा को कैश करती है।

```csharp
public abstract class RasterCachedImage : RasterImage
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
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस अल्फा रखता है या नहीं। |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | छवि में पारदर्शी रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| abstract [Height](../../aspose.psd/image/height/) { get; } | छवि की ऊँचाई प्राप्त करता है। |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | इस [`RasterImage`](../rasterimage/) की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | इस छवि की अपारदर्शिता प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनिटर को प्राप्त करता है या सेट करता है। |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान में छवि डेटा कैश किया गया है या नहीं। |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोडिंग उपलब्ध है या नहीं। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे प्रतिनिधित्व किए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता। |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि छवि घटकों को पूर्व-गुणा किया जाना चाहिए या नहीं। |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | कस्टम रंग कनवर्टर को प्राप्त करता है या सेट करता है। |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | कच्चा डेटा फ़ॉर्मेट प्राप्त करता है। |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। ध्यान दें कि इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग करने के लिए फॉलबैक इंडेक्स प्राप्त करता है या सेट करता है |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | इंडेक्स्ड कलर कनवर्टर प्राप्त करता है या सेट करता है |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | बाइट्स में कच्ची लाइन आकार प्राप्त करता है। |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | छवि का पारदर्शी रंग प्राप्त करता है। |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP मेटाडेटा को अपडेट करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | छवि पैलेट उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | जब कच्चा डेटा लोडिंग उपलब्ध हो, तो कच्चा डेटा लोडिंग उपयोग करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | इस [`RasterImage`](../rasterimage/) की लंबवत रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| abstract [Width](../../aspose.psd/image/width/) { get; } | छवि की चौड़ाई प्राप्त करता है। |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP मेटाडेटा प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | छवि की चमक को समायोजित करता है। |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | छवि कंट्रास्टिंग |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | छवि का गामा-करेक्शन। |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | छवि का गामा-करेक्शन। |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | पूर्वनिर्धारित थ्रेशोल्ड के साथ छवि का बाइनरीकरण |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | ओट्सु थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | डेटा को कैश करता है और सुनिश्चित करता है कि आधारभूत [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) से कोई अतिरिक्त डेटा लोडिंग न हो। |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | निर्धारित करता है कि क्या छवि को पास किए गए सहेजने विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है। |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | छवि को क्रॉप करना। |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | शिफ्ट के साथ छवि को क्रॉप करें। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | वर्तमान छवि पर डिथरिंग करता है। |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | वर्तमान छवि पर डिथरिंग करता है। |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | निर्दिष्ट आयत को फ़िल्टर करता है। |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | एक छवि का 32-बिट ARGB पिक्सेल प्राप्त करता है। |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | संसाधन छवि के अंतिम संशोधित होने की तिथि और समय प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह मूल इमेज की बिट-डेप्थ और अन्य पैरामीटर को अपरिवर्तित रखने में सहायक हो सकता है। उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल के साथ काली-सफ़ेद PNG इमेज लोड करते हैं और फिर [`Save`](../datastreamsupporter/save/) मेथड का उपयोग करके इसे सहेजते हैं, तो आउटपुट PNG इमेज 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी। इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG इमेज सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने विकल्प प्राप्त करें और उन्हें दूसरे पैरामीटर के रूप में [`Save`](../image/save/) मेथड को पास करें। |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | एक छवि पिक्सेल प्राप्त करता है। प्रदर्शन चेतावनी: सभी छवि पिक्सेल पर इटररेट करने के लिए इस मेथड का उपयोग करने से बचें क्योंकि इससे महत्वपूर्ण प्रदर्शन समस्याएँ हो सकती हैं। अधिक कुशल पिक्सेल हेरफेर के लिए, पूरे पिक्सेल एरे को एक साथ प्राप्त करने हेतु `LoadArgb32Pixels` मेथड का उपयोग करें। |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | स्क्यू कोण प्राप्त करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होता है, स्कैनिंग के दौरान स्क्यू कोण निर्धारित करने के लिए। |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | छवि को उसके ग्रेस्केल प्रतिनिधित्व में रूपांतरित करना |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-बिट ARGB पिक्सेल लोड करता है। |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-बिट ARGB पिक्सेल लोड करता है। |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [`LoadCmyk32Pixels`](../rasterimage/loadcmyk32pixels/) मेथड का उपयोग करें। |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | पैक्स द्वारा आंशिक रूप से 32-बिट ARGB पिक्सेल लोड करता है। |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है। |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | पिक्सेल लोड करता है। |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | कच्चा डेटा लोड करता है। |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | कच्चा डेटा लोड करता है। |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [`GetSkewAngle`](../rasterimage/getskewangle/) और [`Rotate`](../rasterimage/rotate/) मेथड्स का उपयोग करता है। |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [`GetSkewAngle`](../rasterimage/getskewangle/) और [`Rotate`](../rasterimage/rotate/) मेथड्स का उपयोग करता है। |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली इमेज पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली इमेज पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | इमेज का आकार बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | इमेज का आकार बदलता है। |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | इमेज का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | इमेज को केंद्र के चारों ओर घुमाता है। |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | इमेज को केंद्र के चारों ओर घुमाता है। |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | इमेज को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है। |
| [Save](../../aspose.psd/image/save/)() | इमेज डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32-बिट ARGB पिक्सेल को सहेजता है। |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | पिक्सेल को सहेजता है। |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | पिक्सेल को सहेजता है। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [`SaveCmyk32Pixels`](../rasterimage/savecmyk32pixels/) मेथड का उपयोग करें। |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | पिक्सेल को सहेजता है। |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | कच्चा डेटा सहेजता है। |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | निर्दिष्ट स्थिति के लिए इमेज का 32-बिट ARGB पिक्सेल सेट करता है। |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है। |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | निर्दिष्ट स्थिति के लिए इमेज पिक्सेल सेट करता है। |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | इस [`RasterImage`](../rasterimage/) की रेज़ोल्यूशन सेट करता है। |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | रास्टर इमेज को बिटमैप में बदलता है। |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |

## उदाहरण

निम्नलिखित कोड विशिष्ट आयत द्वारा छवि को क्रॉप करने की क्षमता दर्शाता है।

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // psd सहेजें
    image.Save(exportPath, new PsdOptions());

    // png सहेजें
    image.Save(exportPathPng, new PngOptions());
}
```

### देखें भी

* class [RasterImage](../rasterimage/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



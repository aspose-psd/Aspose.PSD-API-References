---
title: Class RasterImage
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.RasterImage कक्ष. रेखपुंज ग्रफक्स संचलन क समर्थन करने वल रेखपुंज छव क प्रतनधत्व करत है
type: docs
weight: 5320
url: /hi/net/aspose.psd/rasterimage/
---
## RasterImage class

रेखापुंज ग्राफिक्स संचालन का समर्थन करने वाली रेखापुंज छवि का प्रतिनिधित्व करता है।

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
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
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या इस उदाहरण में अल्फ़ा है. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | एक मान प्राप्त या सेट करता है जो बताता है कि छवि में पृष्ठभूमि का रंग है या नहीं। |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | एक मान प्राप्त करता है जो बताता है कि छवि में पारदर्शी रंग है या नहीं। |
| abstract [Height](../../aspose.psd/image/height/) { get; } | छवि ऊंचाई प्राप्त करता है। |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | इसमें से पिक्सल प्रति इंच में हॉरिजॉन्टल रेजोल्यूशन प्राप्त या सेट करता है`RasterImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | इस छवि की अस्पष्टता प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनीटर प्राप्त या सेट करता है। |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | एक मान प्राप्त करता है जो इंगित करता है कि वस्तु का डेटा वर्तमान में कैश किया गया है और कोई डेटा पढ़ने की आवश्यकता नहीं है। |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोड हो रहा है या नहीं। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। रंग पैलेट का उपयोग तब नहीं किया जाता है जब पिक्सेल को सीधे प्रदर्शित किया जाता है. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि छवि घटकों को पूर्व-गुणा किया जाना चाहिए। |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | कस्टम कलर कन्वर्टर प्राप्त या सेट करता है |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | अपरिष्कृत डेटा प्रारूप प्राप्त करता है। |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | वर्तमान अपरिष्कृत डेटा सेटिंग प्राप्त करता है। नोट करें कि इन सेटिंग का उपयोग करते समय डेटा रूपांतरण के बिना लोड होता है. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग करने के लिए फ़ॉलबैक इंडेक्स प्राप्त या सेट करता है |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | अनुक्रमित रंग कनवर्टर प्राप्त या सेट करता है |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | बाइट्स में कच्ची रेखा का आकार प्राप्त करता है। |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | इमेज को पारदर्शी रंग देता है. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो बताता है कि XMP मेटाडेटा को अपडेट करना है या नहीं। |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो बताता है कि कच्चे डेटा लोड होने पर कच्चे डेटा लोडिंग का उपयोग करना है या नहीं। |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | इसमें से पिक्सेल प्रति इंच में लंबवत रिज़ॉल्यूशन प्राप्त या सेट करता है`RasterImage` . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | छवि चौड़ाई प्राप्त करता है। |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | एक्सएमपी मेटाडेटा प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | छवि के लिए चमक समायोजित करें। |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | विषम छवि |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | गामा-एक छवि का सुधार। |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | गामा-एक छवि का सुधार। |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | इंटीग्रल इमेज थ्रेशोल्डिंग का उपयोग करके ब्रैडली के एडेप्टिव थ्रेशोल्डिंग एल्गोरिथम का उपयोग करके इमेज का बाइनेराइज़ेशन |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | इंटीग्रल इमेज थ्रेशोल्डिंग का उपयोग करके ब्रैडली के एडेप्टिव थ्रेशोल्डिंग एल्गोरिथम का उपयोग करके इमेज का बाइनेराइज़ेशन |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | पूर्वनिर्धारित थ्रेसहोल्ड के साथ एक छवि का बिनराइजेशन |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | ओत्सू थ्रेसहोल्डिंग के साथ एक छवि का बाइनराइजेशन |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | डेटा को कैश करता है और यह सुनिश्चित करता है कि अंतर्निहित से कोई अतिरिक्त डेटा लोड नहीं किया जाएगा[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | यह निर्धारित करता है कि छवि को पास किए गए सहेजे गए विकल्पों द्वारा दर्शाए गए निर्दिष्ट फ़ाइल स्वरूप में सहेजा जा सकता है या नहीं। |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | निर्दिष्ट आयत को क्रॉप करता है। |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | बदलाव के साथ छवि क्रॉप करें। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | वर्तमान छवि पर डिथरिंग करता है। |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | वर्तमान छवि पर डिथरिंग करता है। |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | निर्दिष्ट आयत को फ़िल्टर करता है। |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 32-बिट ARGB पिक्सेल की छवि प्राप्त करता है. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल सरणी प्राप्त करता है. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल सरणी प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | डिफ़ॉल्ट अपरिष्कृत डेटा सरणी प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट अपरिष्कृत डेटा सरणी प्राप्त करता है। |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | वह दिनांक और समय प्राप्त करता है जब संसाधन छवि को अंतिम बार संशोधित किया गया था। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह बिट-डेप्थ और मूल छवि के अन्य मापदंडों को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम एक काले-सफेद PNG छवि को 1 बिट प्रति पिक्सेल के साथ लोड करते हैं और फिर इसे का उपयोग करके सहेजें[`Save`](../datastreamsupporter/save/) विधि, 8-बिट प्रति पिक्सेल के साथ आउटपुट पीएनजी छवि का उत्पादन किया जाएगा।[`Save`](../image/save/)दूसरे पैरामीटर के रूप में विधि। |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | इमेज पिक्सेल प्राप्त करता है. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | तिरछा कोण प्राप्त करता है। स्कैन करते समय तिरछा कोण निर्धारित करने के लिए यह विधि स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होती है। |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | एक छवि का उसके ग्रेस्केल प्रतिनिधित्व में परिवर्तन |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-बिट ARGB पिक्सेल लोड करता है. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-बिट ARGB पिक्सेल लोड करता है. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | पिक्सेल को CMYK प्रारूप में लोड करता है. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32-बिट ARGB पिक्सेल को पैक द्वारा आंशिक रूप से लोड करता है. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | पिक्सेल को आंशिक रूप से पैक द्वारा लोड करता है. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | पिक्सेल लोड करता है. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | अपरिष्कृत डेटा लोड करता है. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | अपरिष्कृत डेटा लोड करता है. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | कोण को सामान्य करता है। यह विधि तिरछी स्कैन से छुटकारा पाने के लिए स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होती है। यह विधि उपयोग करती है[`GetSkewAngle`](./getskewangle/) और[`Rotate`](./rotate/) तरीके. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | कोण को सामान्य करता है। यह विधि तिरछी स्कैन से छुटकारा पाने के लिए स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होती है। यह विधि उपयोग करती है[`GetSkewAngle`](./getskewangle/) और[`Rotate`](./rotate/) तरीके. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन को पढ़ता है। |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन को पढ़ता है। |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | अनुमत अंतर के साथ एक रंग को दूसरे रंग में बदलता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | अनुमत अंतर के साथ एक रंग को दूसरे रंग में बदलता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | सभी गैर-पारदर्शी रंगों को नए रंग से बदल देता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | सभी गैर-पारदर्शी रंगों को नए रंग से बदल देता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | छवि का आकार बदलता है। डिफ़ॉल्टLeftTopToLeftTopप्रयोग किया जाता है. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | विस्तारित विकल्पों के साथ छवि का आकार बदलता है। |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | छवि का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | इमेज को बीच में घुमाएं. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | इमेज को बीच में घुमाएं. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | छवि को घुमाता है, फ़्लिप करता है या घुमाता है और फ़्लिप करता है. |
| [Save](../../aspose.psd/image/save/)() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32-बिट ARGB पिक्सेल सहेजता है. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | पिक्सेल सहेजता है. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | पिक्सेल सहेजता है. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | कच्चे डेटा को सहेजता है। |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | निर्दिष्ट स्थान के लिए एक छवि 32-बिट ARGB पिक्सेल सेट करता है। |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | निर्दिष्ट स्थान के लिए एक छवि पिक्सेल सेट करता है। |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | इसके लिए संकल्प सेट करता है`RasterImage` . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | रेखापुंज छवि को बिटमैप में परिवर्तित करता है। |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स में लिखता है। |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स में लिखता है। |

### उदाहरण

यह उदाहरण दिखाता है कि कैसे पिक्सेल जानकारी को प्रकार के रंग की एक सरणी में लोड किया जाता है, सरणी में हेरफेर किया जाता है और इसे छवि पर वापस सेट किया जाता है। इन कार्यों को करने के लिए, यह उदाहरण मेमोरीस्ट्रीम ऑब्जेक्ट का उपयोग करके एक नई छवि फ़ाइल (PSD प्रारूप में) बनाता है।

```csharp
[C#]

// मेमोरीस्ट्रीम का एक उदाहरण बनाएं
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // PsdOptions का एक उदाहरण बनाएं और स्रोत गुण सहित इसके विभिन्न गुणों को सेट करें
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    // छवि का एक उदाहरण बनाएं
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        // क्षेत्र को छवि सीमा के रूप में निर्दिष्ट करके छवि के पिक्सेल प्राप्त करें
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        // ऐरे पर लूप करें और एलरेनेटिव इंडेक्स्ड पिक्सेल का रंग सेट करें
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // अनुक्रमित पिक्सेल रंग को पीले रंग में सेट करें
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                // अनुक्रमित पिक्सेल रंग को नीले रंग में सेट करें
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // छवि में पिक्सेल परिवर्तन लागू करें
        image.SavePixels(image.Bounds, pixels);

        // सभी परिवर्तनों को सहेजें।
        image.Save();
    }

    // फ़ाइल में मेमोरीस्ट्रीम लिखें
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### यह सभी देखें

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)



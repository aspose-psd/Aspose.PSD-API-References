---
title: Class PsdImage
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.PsdImage कक्ष. PsdImage वर्ग क परभषत करत है ज PSD फ़इलं क लड करने संपदत करने सहेजने के सथसथ गुणं क अपडेट करने वटरमर्क जड़ने ग्रफक्स संचलन करने य एक फ़इल प्ररूप क दूसरे में बदलने क क्षमत प्रदन करत है Aspose.PSD एक परत के रूप में आयत और नर्यत क समर्थन करत है नम्नलखत प्ररूप Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb चयन यग्य text के सथ Pdf क नर्यत के सथ
type: docs
weight: 3590
url: /hi/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

PsdImage वर्ग को परिभाषित करता है जो PSD फ़ाइलों को लोड करने, संपादित करने, सहेजने के साथ-साथ गुणों को अपडेट करने, वॉटरमार्क जोड़ने, ग्राफिक्स संचालन करने या एक फ़ाइल प्रारूप को दूसरे में बदलने की क्षमता प्रदान करता है। Aspose.PSD एक परत के रूप में आयात और निर्यात का समर्थन करता है। निम्नलिखित प्रारूप: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb चयन योग्य text के साथ Pdf को निर्यात के साथ

```csharp
public sealed class PsdImage : RasterCachedImage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` चैनल 8 बिट/चैनल और कोई संपीड़न के साथ आरजीबी रंग मोड के साथ मौजूदा रेखापुंज छवि (पीएसडी छवि नहीं) से वर्ग। |
| [PsdImage](psdimage/#constructor_4)(Stream) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` रेखापुंज छवि से निर्दिष्ट पथ से वर्ग (धारा में psd छवि नहीं)। डिफ़ॉल्ट मापदंडों के साथ psd छवि को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, 8 बिट प्रति चैनल, कम्प्रेशन - रॉ. |
| [PsdImage](psdimage/#constructor_6)(string) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` रेखापुंज छवि से निर्दिष्ट पथ से वर्ग (पथ में पीएसडी छवि नहीं)। डिफ़ॉल्ट मापदंडों के साथ psd छवि को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, 8 बिट प्रति चैनल, कम्प्रेशन - रॉ. |
| [PsdImage](psdimage/#constructor_2)(int, int) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` वर्ग निर्दिष्ट चौड़ाई और ऊंचाई के साथ। खाली पीएसडी इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है। |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` कंस्ट्रक्टर मापदंडों के साथ मौजूदा रेखापुंज छवि (psd छवि नहीं) से वर्ग। |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` रास्टर छवि से निर्दिष्ट पथ से कक्षा (स्ट्रीम में पीएसडी छवि नहीं) कन्स्ट्रक्टर पैरामीटर के साथ। |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` रास्टर छवि से निर्दिष्ट पथ से कक्षा (पथ में पीएसडी छवि नहीं) कन्स्ट्रक्टर पैरामीटर के साथ। |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | का एक नया उदाहरण प्रारंभ करता है`PsdImage` वर्ग निर्दिष्ट चौड़ाई, ऊंचाई, पैलेट, रंग मोड, चैनलों की संख्या और चैनल बिट-लंबाई और निर्दिष्ट संपीड़न मोड पैरामीटर के साथ। खाली पीएसडी इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | सक्रिय परत प्राप्त या सेट करता है। |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि स्वचालित समायोजन पैलेट है या नहीं। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त या सेट करता है। |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | प्रति चैनल बिट्स प्राप्त करता है। |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | छवि बिट्स प्रति पिक्सेल संख्या प्राप्त करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि सीमा प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेत प्राप्त या सेट करता है जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार परिभाषित किया गया है। |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | PSD चैनलों की संख्या प्राप्त करता है. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | CMYK PSD छवियों के लिए CMYK रंग प्रोफ़ाइल प्राप्त या सेट करता है। सही रंग रूपांतरण के लिए RgbColorProfile के साथ जोड़ा जाना चाहिए। |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | रंग मोड प्राप्त या सेट करता है। |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | संपीड़न विधि प्राप्त करता है। |
| [Container](../../aspose.psd/image/container/) { get; } | हो जाता है[`Image`](../../aspose.psd/image/) कंटेनर. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट की डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण निपटाया गया है। |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | फ़ाइल स्वरूप का मान प्राप्त करता है |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | वैश्विक कोण प्राप्त या सेट करता है। |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | ग्लोबल लेयर मास्क जानकारी प्राप्त करता है। |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | वैश्विक परत संसाधनों को प्राप्त या सेट करता है। |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | ग्रेस्केल PSD छवियों के लिए ग्रे (मोनोक्रोम) रंग प्रोफ़ाइल प्राप्त या सेट करता है। |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | इसमें से पिक्सेल प्रति इंच में लंबवत रिज़ॉल्यूशन प्राप्त या सेट करता है[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | एक मान प्राप्त या सेट करता है जो बताता है कि छवि में पृष्ठभूमि का रंग है या नहीं। |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | परत डेटा निर्दिष्ट करते समय मर्ज किए गए परिणाम के लिए पहले अल्फा चैनल में पारदर्शिता डेटा शामिल है या नहीं, यह इंगित करने वाला मान प्राप्त या सेट करता है। |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | एक मान प्राप्त करता है जो बताता है कि छवि में पारदर्शी रंग है या नहीं। |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | छवि ऊंचाई प्राप्त करता है। |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | इसमें से पिक्सल प्रति इंच में हॉरिजॉन्टल रेजोल्यूशन प्राप्त या सेट करता है`PsdImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | इस छवि की अस्पष्टता प्राप्त करता है। |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | PSD छवि संसाधनों को प्राप्त या सेट करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनीटर प्राप्त या सेट करता है। |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि छवि डेटा वर्तमान में कैश किया गया है या नहीं। |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | यह इंगित करने वाला मान प्राप्त करता है कि क्या PSD छवि चपटी है। |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोड हो रहा है या नहीं। |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | PSD परतें प्राप्त या सेट करता है. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | लिंक्ड लेयर मैनेजर प्राप्त करता है। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | कलर पैलेट प्राप्त या सेट करता है। रंग पैलेट का उपयोग तब नहीं किया जाता है जब पिक्सेल को सीधे प्रदर्शित किया जाता है. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो इंगित करता है कि छवि घटकों को पूर्व-गुणा किया जाना चाहिए। |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | कस्टम कलर कन्वर्टर प्राप्त या सेट करता है |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | अपरिष्कृत डेटा प्रारूप प्राप्त करता है। |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | वर्तमान अपरिष्कृत डेटा सेटिंग प्राप्त करता है। नोट करें कि इन सेटिंग का उपयोग करते समय डेटा रूपांतरण के बिना लोड होता है. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग करने के लिए फ़ॉलबैक इंडेक्स प्राप्त या सेट करता है |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | अनुक्रमित रंग कनवर्टर प्राप्त या सेट करता है |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | बाइट्स में कच्ची रेखा का आकार प्राप्त करता है। |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | CMYK PSD छवियों के लिए RGB रंग प्रोफ़ाइल प्राप्त या सेट करता है। सही रंग रूपांतरण के लिए CmykColorProfile के साथ जोड़ा जाना चाहिए। |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | स्मार्ट ऑब्जेक्ट प्रदाता प्राप्त करता है। |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | इमेज को पारदर्शी रंग देता है. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो बताता है कि XMP मेटाडेटा को अपडेट करना है या नहीं। |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो बताता है कि कच्चे डेटा लोड होने पर कच्चे डेटा लोडिंग का उपयोग करना है या नहीं। |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | संस्करण प्राप्त या सेट करता है। |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | इसमें से पिक्सेल प्रति इंच में लंबवत रिज़ॉल्यूशन प्राप्त या सेट करता है`PsdImage` . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | छवि चौड़ाई प्राप्त करता है। |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | एक्सएमपी मेटाडेटा प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | काले सफेद समायोजन परत जोड़ता है। |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | चमक/कंट्रास्ट समायोजन परत जोड़ता है। |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | चैनल मिक्सर समायोजन परत को डिफ़ॉल्ट पैरामीटर के साथ जोड़ता है |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | रंग संतुलन समायोजन परत जोड़ता है। |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | वक्र समायोजन परत जोड़ता है. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | एक्सपोजर एडजस्टमेंट लेयर जोड़ता है। |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | रंग/संतृप्ति समायोजन परत जोड़ता है। |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | एक उलटी समायोजन परत जोड़ता है। |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | परत जोड़ता है. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | परत समूह जोड़ता है. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | स्तर समायोजन परत जोड़ता है। |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | फोटोफिल्टर परत जोड़ता है। |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | एक नई नियमित परत जोड़ता है. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | एक नई पाठ परत जोड़ता है। |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | वाइब्रेंस समायोजन परत जोड़ता है. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | छवि के लिए चमक समायोजित करें। |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | विषम छवि |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | गामा-एक छवि का सुधार। |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | गामा-एक छवि का सुधार। |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | इंटीग्रल इमेज थ्रेशोल्डिंग का उपयोग करके ब्रैडली के एडेप्टिव थ्रेशोल्डिंग एल्गोरिथम का उपयोग करके इमेज का बाइनेराइज़ेशन |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | इंटीग्रल इमेज थ्रेशोल्डिंग का उपयोग करके ब्रैडली के एडेप्टिव थ्रेशोल्डिंग एल्गोरिथम का उपयोग करके इमेज का बाइनेराइज़ेशन |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | पूर्वनिर्धारित थ्रेसहोल्ड के साथ एक छवि का बिनराइजेशन |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | ओत्सू थ्रेसहोल्डिंग के साथ एक छवि का बाइनराइजेशन |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | डेटा को कैश करता है और यह सुनिश्चित करता है कि अंतर्निहित से कोई अतिरिक्त डेटा लोड नहीं किया जाएगा[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | यह निर्धारित करता है कि छवि को पास किए गए सहेजे गए विकल्पों द्वारा दर्शाए गए निर्दिष्ट फ़ाइल स्वरूप में सहेजा जा सकता है या नहीं। |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | इस इमेज फ़ॉर्मैट को विकल्पों में बताए गए फ़ॉर्मैट में बदलता है. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | इमेज को क्रॉप किया जा रहा है. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | बदलाव के साथ छवि क्रॉप करें। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान उदाहरण का निपटान करता है। |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | वर्तमान छवि पर डिथरिंग करता है। |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | वर्तमान छवि पर डिथरिंग करता है। |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | निर्दिष्ट आयत को फ़िल्टर करता है। |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | सभी परतों को समतल करता है. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | 32-बिट ARGB पिक्सेल की छवि प्राप्त करता है. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल सरणी प्राप्त करता है. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल सरणी प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | डिफ़ॉल्ट अपरिष्कृत डेटा सरणी प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट अपरिष्कृत डेटा सरणी प्राप्त करता है। |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | वह दिनांक और समय प्राप्त करता है जब संसाधन छवि को अंतिम बार संशोधित किया गया था। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह बिट-डेप्थ और मूल छवि के अन्य मापदंडों को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम एक काले-सफेद PNG छवि को 1 बिट प्रति पिक्सेल के साथ लोड करते हैं और फिर इसे का उपयोग करके सहेजें[`Save`](../../aspose.psd/datastreamsupporter/save/) विधि, 8-बिट प्रति पिक्सेल के साथ आउटपुट पीएनजी छवि का उत्पादन किया जाएगा।[`Save`](../../aspose.psd/image/save/)दूसरे पैरामीटर के रूप में विधि। |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | इमेज पिक्सेल प्राप्त करता है. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | तिरछा कोण प्राप्त करता है। स्कैन करते समय तिरछा कोण निर्धारित करने के लिए यह विधि स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होती है। |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | एक छवि का उसके ग्रेस्केल प्रतिनिधित्व में परिवर्तन |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-बिट ARGB पिक्सेल लोड करता है. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-बिट ARGB पिक्सेल लोड करता है. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | पिक्सेल को CMYK प्रारूप में लोड करता है. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | 32-बिट ARGB पिक्सेल को पैक द्वारा आंशिक रूप से लोड करता है. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | पिक्सेल को आंशिक रूप से पैक द्वारा लोड करता है. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | पिक्सेल लोड करता है. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | अपरिष्कृत डेटा लोड करता है. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | अपरिष्कृत डेटा लोड करता है. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | परतों को मर्ज करता है। |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | कोण को सामान्य करता है। यह विधि तिरछी स्कैन से छुटकारा पाने के लिए स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होती है। यह विधि उपयोग करती है[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) और[`Rotate`](../../aspose.psd/rasterimage/rotate/) तरीके. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | कोण को सामान्य करता है। यह विधि तिरछी स्कैन से छुटकारा पाने के लिए स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होती है। यह विधि उपयोग करती है[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) और[`Rotate`](../../aspose.psd/rasterimage/rotate/) तरीके. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन को पढ़ता है। |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन को पढ़ता है। |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | अनुमत अंतर के साथ एक रंग को दूसरे रंग में बदलता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | अनुमत अंतर के साथ एक रंग को दूसरे रंग में बदलता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | सभी गैर-पारदर्शी रंगों को नए रंग से बदल देता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | सभी गैर-पारदर्शी रंगों को नए रंग से बदल देता है और चिकनी किनारों को बचाने के लिए मूल अल्फा मान को संरक्षित करता है। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | छवि का आकार बदलता है। डिफ़ॉल्टLeftTopToLeftTopप्रयोग किया जाता है. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | छवि का आकार बदलता है। |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | छवि का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | ऊँचाई को आनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | आनुपातिक रूप से चौड़ाई का आकार बदलता है। |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | इमेज को बीच में घुमाएं. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | इमेज को बीच में घुमाएं. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | छवि को घुमाता है, फ़्लिप करता है या घुमाता है और फ़्लिप करता है. |
| [Save](../../aspose.psd/image/save/)() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | ऑब्जेक्ट के डेटा को निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | इमेज के डेटा को सेव ऑप्शन के अनुसार निर्दिष्ट फ़ाइल प्रारूप में निर्दिष्ट स्ट्रीम में सहेजता है। |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट के डेटा को निर्दिष्ट फ़ाइल स्थान पर निर्दिष्ट फ़ाइल स्वरूप में सहेजें विकल्पों के अनुसार सहेजता है। |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32-बिट ARGB पिक्सेल सहेजता है. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | पिक्सेल सहेजता है. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | पिक्सेल सहेजता है. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | कच्चे डेटा को सहेजता है। |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | निर्दिष्ट स्थान के लिए एक छवि 32-बिट ARGB पिक्सेल सेट करता है। |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | निर्दिष्ट स्थान के लिए एक छवि पिक्सेल सेट करता है। |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | इसके लिए संकल्प सेट करता है[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | रेखापुंज छवि को बिटमैप में परिवर्तित करता है। |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स में लिखता है। |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स में लिखता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | डिफ़ॉल्ट PSD संस्करण. |

### उदाहरण

निम्न कोड विशिष्ट कोण मान द्वारा छवि को घुमाने की क्षमता प्रदर्शित करता है।

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// पूरी छवि घूम रही है
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// परत घूम रही है
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### यह सभी देखें

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* सभा [Aspose.PSD](../../)



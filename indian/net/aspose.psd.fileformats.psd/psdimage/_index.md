---
title: "क्लास PsdImage"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.PsdImage क्लास। यह PsdImage क्लास को परिभाषित करता है जो PSD फ़ाइलों को लोड, संपादित, सहेजने, साथ ही गुणों को अपडेट करने, वॉटरमार्क जोड़ने, ग्राफ़िक ऑपरेशन्स करने या एक फ़ाइल फ़ॉर्मेट को दूसरे में परिवर्तित करने की क्षमता प्रदान करता है। Aspose.PSD लेयर के रूप में आयात को समर्थन देता है और निम्नलिखित फ़ॉर्मेट्स में निर्यात करता है: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, साथ ही चयन योग्य टेक्स्ट के साथ Pdf में निर्यात।"
type: docs
weight: 4050
url: /hi/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

PsdImage क्लास को परिभाषित करता है जो PSD फ़ाइलों को लोड, एडिट, सेव करने के साथ-साथ प्रॉपर्टीज़ को अपडेट करने, वॉटरमार्क जोड़ने, ग्राफ़िक ऑपरेशन्स करने या एक फ़ाइल फ़ॉर्मेट को दूसरे में बदलने की क्षमता प्रदान करता है। Aspose.PSD लेयर के रूप में इम्पोर्ट और निम्नलिखित फ़ॉर्मेट्स में एक्सपोर्ट का समर्थन करता है: PNG, JPEG, JPEG2000, GIF, BMP, TIFF, PSD, PSB, साथ ही चयन योग्य टेक्स्ट के साथ PDF में एक्सपोर्ट।

```csharp
public sealed class PsdImage : RasterCachedImage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | मौजूदा रास्टर इमेज (psd इमेज नहीं) से `PsdImage` क्लास की नई इंस्टेंस को आरजीबी कलर मोड, 4 चैनल, 8 बिट/चैनल और बिना संपीड़न के साथ प्रारंभ करता है। |
| [PsdImage](psdimage/#constructor_4)(Stream) | निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में psd इमेज नहीं) से `PsdImage` क्लास की नई इंस्टेंस को प्रारंभ करता है। यह psd इमेज को डिफ़ॉल्ट पैरामीटरों के साथ प्रारंभ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, 8 बिट प्रति चैनल, संपीड़न - Raw। |
| [PsdImage](psdimage/#constructor_6)(string) | निर्दिष्ट पथ से रास्टर इमेज (पथ में psd इमेज नहीं) से `PsdImage` क्लास की नई इंस्टेंस को प्रारंभ करता है। यह psd इमेज को डिफ़ॉल्ट पैरामीटरों के साथ प्रारंभ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, 8 बिट प्रति चैनल, संपीड़न - Raw। |
| [PsdImage](psdimage/#constructor_2)(int, int) | निर्दिष्ट चौड़ाई और ऊँचाई के साथ `PsdImage` क्लास की नई इंस्टेंस को प्रारंभ करता है। यह खाली psd इमेज को प्रारंभ करने के लिए उपयोग किया जाता है। |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | मौजूदा रास्टर इमेज (psd इमेज नहीं) से `PsdImage` क्लास की नई इंस्टेंस को कंस्ट्रक्टर पैरामीटरों के साथ प्रारंभ करता है। |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में psd इमेज नहीं) से `PsdImage` क्लास की नई इंस्टेंस को कंस्ट्रक्टर पैरामीटरों के साथ प्रारंभ करता है। |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | निर्दिष्ट पथ से रास्टर इमेज (पथ में psd इमेज नहीं) से `PsdImage` क्लास की नई इंस्टेंस को कंस्ट्रक्टर पैरामीटरों के साथ प्रारंभ करता है। |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | निर्दिष्ट चौड़ाई, ऊँचाई, पैलेट, कलर मोड, चैनल गिनती और चैनल बिट-लेंथ तथा निर्दिष्ट संपीड़न मोड पैरामीटरों के साथ `PsdImage` क्लास की नई इंस्टेंस को प्रारंभ करता है। यह खाली psd इमेज को प्रारंभ करने के लिए उपयोग किया जाता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | सक्रिय लेयर को प्राप्त करता है या सेट करता है। |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | स्वचालित समायोजन पैलेट को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त करता है या सेट करता है। |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | प्रति चैनल बिट्स प्राप्त करता है। |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | छवि के बिट्स प्रति पिक्सेल की गिनती प्राप्त करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि की सीमाएँ प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | PSD चैनलों की गिनती प्राप्त करता है। |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | CMYK PSD इमेजों के लिए CMYK कलर प्रोफ़ाइल को प्राप्त करता है या सेट करता है। सही रंग रूपांतरण के लिए इसे RgbColorProfile के साथ जोड़ा होना चाहिए। |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | कलर मोड को प्राप्त करता है या सेट करता है। |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | संपीड़न विधि प्राप्त करता है। |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../../aspose.psd/image/) कंटेनर प्राप्त करता है। |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | ग्लोबल एंगल को प्राप्त करता है या सेट करता है। |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | ग्लोबल लेयर मास्क जानकारी प्राप्त करता है। |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | ग्लोबल लेयर रिसोर्सेज को प्राप्त करता है या सेट करता है। |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | ग्रेस्केल PSD इमेजों के लिए GRAY (मोनोक्रोम) कलर प्रोफ़ाइल को प्राप्त करता है या सेट करता है। |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | इस [`RasterImage`](../../aspose.psd/rasterimage/) की लंबवत रेज़ोल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | पहले अल्फा चैनल में लेयर डेटा निर्दिष्ट करने पर मर्ज्ड परिणाम के लिए पारदर्शिता डेटा है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | छवि में पारदर्शी रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | छवि की ऊँचाई प्राप्त करता है। |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | इस `PsdImage` की क्षैतिज रिज़ॉल्यूशन (पिक्सेल प्रति इंच) को प्राप्त करता है या सेट करता है। |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | इस छवि की अपारदर्शिता प्राप्त करता है। |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | PSD इमेज रिसोर्सेज को प्राप्त करता है या सेट करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनिटर को प्राप्त करता है या सेट करता है। |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान में छवि डेटा कैश किया गया है या नहीं। |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | psd इमेज फ्लैटेन्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोडिंग उपलब्ध है या नहीं। |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | PSD लेयरों को प्राप्त करता है या सेट करता है। |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | लिंक्ड लेयरों के प्रबंधक को प्राप्त करता है। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे प्रतिनिधित्व किए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता। |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि छवि घटकों को पूर्व-गुणा किया जाना चाहिए या नहीं। |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | कस्टम रंग कनवर्टर को प्राप्त करता है या सेट करता है। |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | कच्चा डेटा फ़ॉर्मेट प्राप्त करता है। |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। ध्यान दें कि इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग करने के लिए फॉलबैक इंडेक्स प्राप्त करता है या सेट करता है |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | इंडेक्स्ड कलर कनवर्टर प्राप्त करता है या सेट करता है |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | बाइट्स में कच्ची लाइन आकार प्राप्त करता है। |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | CMYK PSD छवियों के लिए RGB रंग प्रोफ़ाइल को प्राप्त करता है या सेट करता है। सही रंग रूपांतरण के लिए इसे CmykColorProfile के साथ जोड़ा होना चाहिए। |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | स्मार्ट ऑब्जेक्ट प्रोवाइडर प्राप्त करता है। |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | इस `PsdImage` की [`Timeline`](./timeline/) को प्राप्त करता है। |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | छवि का पारदर्शी रंग प्राप्त करता है। |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP मेटाडेटा को अपडेट करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | छवि पैलेट उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | जब कच्चा डेटा लोडिंग उपलब्ध हो, तो कच्चा डेटा लोडिंग उपयोग करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | संस्करण को प्राप्त करता है या सेट करता है। |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | इस `PsdImage` की लंबवत रिज़ॉल्यूशन (पिक्सेल प्रति इंच) को प्राप्त करता है या सेट करता है। |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | छवि की चौड़ाई प्राप्त करता है। |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | XMP मेटाडेटा प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | ब्लैक व्हाइट एडजस्टमेंट लेयर जोड़ता है। |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | ब्राइटनेस/कॉन्ट्रास्ट एडजस्टमेंट लेयर जोड़ता है। |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | डिफ़ॉल्ट पैरामीटरों के साथ चैनल मिक्सर एडजस्टमेंट लेयर जोड़ता है। |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | कलर बैलेंस एडजस्टमेंट लेयर जोड़ता है। |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | कर्व्स एडजस्टमेंट लेयर जोड़ता है। |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | एक्सपोज़र एडजस्टमेंट लेयर जोड़ता है। |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | ग्रेडिएंटमैप एडजस्टमेंट लेयर जोड़ता है। |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | ह्यू/सैचुरेशन एडजस्टमेंट लेयर जोड़ता है। |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | इनवर्ट एडजस्टमेंट लेयर जोड़ता है। |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | लेयर जोड़ता है। |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | लेयर समूह को जोड़ता है। |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | लेवल्स एडजस्टमेंट लेयर जोड़ता है। |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | फ़ोटोफ़िल्टर लेयर जोड़ता है। |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | पोस्टराइज़ एडजस्टमेंट लेयर जोड़ता है। |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | एक नया नियमित लेयर जोड़ता है। |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | सेलेक्टिव कलर एडजस्टमेंट लेयर जोड़ता है। |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | खाली शेप लेयर जोड़ें। बिना पाथ्स के। इन्हें सहेजने से पहले शेप लेयर में जोड़ना चाहिए। |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | एक नया टेक्स्ट लेयर जोड़ता है। |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | थ्रेशहोल्ड एडजस्टमेंट लेयर जोड़ता है। |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | वाइब्रेंस एडजस्टमेंट लेयर जोड़ता है। |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | छवि की चमक को समायोजित करता है। |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | छवि कंट्रास्टिंग |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | छवि का गामा-करेक्शन। |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | छवि का गामा-करेक्शन। |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | पूर्वनिर्धारित थ्रेशोल्ड के साथ छवि का बाइनरीकरण |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | ओट्सु थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) से कोई अतिरिक्त डेटा लोडिंग नहीं की जाएगी। |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | निर्धारित करता है कि क्या छवि को पास किए गए सहेजने विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है। |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | इस इमेज फ़ॉर्मेट को विकल्पों में निर्दिष्ट फ़ॉर्मेट में परिवर्तित करता है। |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | छवि को क्रॉप करना। |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | शिफ्ट के साथ छवि को क्रॉप करें। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | वर्तमान छवि पर डिथरिंग करता है। |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | वर्तमान छवि पर डिथरिंग करता है। |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | निर्दिष्ट आयत को फ़िल्टर करता है। |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | सभी लेयरों को सपाट करता है। |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | एक छवि का 32-बिट ARGB पिक्सेल प्राप्त करता है। |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | संसाधन छवि के अंतिम संशोधित होने की तिथि और समय प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह मूल छवि की बिट-डेप्थ और अन्य पैरामीटर को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले ब्लैक-व्हाइट PNG छवि को लोड करते हैं और फिर [`Save`](../../aspose.psd/datastreamsupporter/save/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी। इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने विकल्प प्राप्त करें और उन्हें दूसरे पैरामीटर के रूप में [`Save`](../../aspose.psd/image/save/) मेथड को पास करें। |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | एक छवि पिक्सेल प्राप्त करता है। प्रदर्शन चेतावनी: सभी छवि पिक्सेल पर इटररेट करने के लिए इस मेथड का उपयोग करने से बचें क्योंकि इससे महत्वपूर्ण प्रदर्शन समस्याएँ हो सकती हैं। अधिक कुशल पिक्सेल हेरफेर के लिए, पूरे पिक्सेल एरे को एक साथ प्राप्त करने हेतु `LoadArgb32Pixels` मेथड का उपयोग करें। |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | स्क्यू कोण प्राप्त करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होता है, स्कैनिंग के दौरान स्क्यू कोण निर्धारित करने के लिए। |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | छवि को उसके ग्रेस्केल प्रतिनिधित्व में रूपांतरित करना |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-बिट ARGB पिक्सेल लोड करता है। |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-बिट ARGB पिक्सेल लोड करता है। |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) मेथड का उपयोग करें। |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | पैक्स द्वारा आंशिक रूप से 32-बिट ARGB पिक्सेल लोड करता है। |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है। |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | पिक्सेल लोड करता है। |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | कच्चा डेटा लोड करता है। |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | कच्चा डेटा लोड करता है। |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | लेयरों को मिलाता है। |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) और [`Rotate`](../../aspose.psd/rasterimage/rotate/) मेथड्स का उपयोग करता है। |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) और [`Rotate`](../../aspose.psd/rasterimage/rotate/) मेथड्स का उपयोग करता है। |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली इमेज पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली इमेज पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | इमेज का आकार बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | इमेज का आकार बदलता है। |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | इमेज का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | इमेज को केंद्र के चारों ओर घुमाता है। |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | इमेज को केंद्र के चारों ओर घुमाता है। |
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
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | पिक्सेल को सहेजता है। यह मेथड अब अप्रचलित है। कृपया अधिक प्रभावी [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) मेथड का उपयोग करें। |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | पिक्सेल को सहेजता है। |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | कच्चा डेटा सहेजता है। |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | निर्दिष्ट स्थिति के लिए इमेज का 32-बिट ARGB पिक्सेल सेट करता है। |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है। |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | निर्दिष्ट स्थिति के लिए इमेज पिक्सेल सेट करता है। |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | `PsdImage` के लिए रिज़ॉल्यूशन सेट करता है। |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | रास्टर इमेज को बिटमैप में बदलता है। |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | डिफ़ॉल्ट PSD संस्करण। |

## उदाहरण

निम्नलिखित कोड यह दर्शाता है कि कैसे छवि को विशिष्ट कोण मान से घुमाया जा सकता है।

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// पूरी छवि का घुमाव
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

// लेयर का घुमाव
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

### देखें भी

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)



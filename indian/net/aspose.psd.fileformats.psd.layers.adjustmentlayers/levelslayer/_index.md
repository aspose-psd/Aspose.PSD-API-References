---
title: "क्लास LevelsLayer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.LevelsLayer क्लास। लेवल्स समायोजन लेयर"
type: docs
weight: 1840
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/
---
{{< psd/tize >}}
## LevelsLayer class

लेवल्स समायोजन लेयर

```csharp
public class LevelsLayer : AdjustmentLayer
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | स्वचालित समायोजन पैलेट को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | पृष्ठभूमि रंग के लिए मान प्राप्त करता है या सेट करता है। |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | छवि के बिट्स प्रति पिक्सेल की गिनती प्राप्त करता है। |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | क्लिप किए गए तत्व के मिश्रण को प्राप्त करता है या सेट करता है। |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | मिश्रण विकल्प प्राप्त करता है। |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | ब्लेंड मोड कुंजी प्राप्त करता है या सेट करता है। |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | ब्लेंड मोड हस्ताक्षर प्राप्त करता है। |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | निचले लेयर की स्थिति प्राप्त करता है या सेट करता है। |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | छवि की सीमाएँ प्राप्त करता है। |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | बफ़र आकार संकेतक प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | चैनल जानकारी प्राप्त करता है या सेट करता है। |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | लेयर के चैनलों की गिनती प्राप्त करता है। |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | लेयर क्लिपिंग प्राप्त करता है या सेट करता है। 0 = बेस, 1 = नॉन-बेस। |
| [Container](../../aspose.psd/image/container/) { get; } | [`Image`](../../aspose.psd/image/) कंटेनर प्राप्त करता है। |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | लेयर का डिस्प्ले नाम प्राप्त करता है या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | लेयर की अतिरिक्त जानकारी की लंबाई बाइट्स में प्राप्त करता है। |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | लेयर फ़िलर प्राप्त करता है या सेट करता है। |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | फ़िल अपारदर्शिता प्राप्त करता है या सेट करता है। |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | लेयर फ़्लैग्स को प्राप्त करता है या सेट करता है। बिट 0 = पारदर्शिता संरक्षित; बिट 1 = दृश्यमान; बिट 2 = अप्रचलित; बिट 3 = Photoshop 5.0 और बाद के संस्करणों के लिए 1, बताता है कि बिट 4 में उपयोगी जानकारी है या नहीं; बिट 4 = दस्तावेज़ की उपस्थिति के लिए अप्रासंगिक पिक्सेल डेटा। |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस अल्फा रखता है या नहीं। |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | छवि में पृष्ठभूमि रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | छवि में पारदर्शी रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | छवि की ऊँचाई प्राप्त करता है। |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | इस [`RasterImage`](../../aspose.psd/rasterimage/) की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | इस छवि की अपारदर्शिता प्राप्त करता है। |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | इंटरप्ट मॉनिटर को प्राप्त करता है या सेट करता है। |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान में छवि डेटा कैश किया गया है या नहीं। |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोडिंग उपलब्ध है या नहीं। |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | लेयर दृश्यमान है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस समूह में दृश्यमान है या नहीं (यदि लेयर समूह में नहीं है तो इसका अर्थ रूट समूह है)। |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | लेयर ब्लेंडिंग रेंज डेटा को प्राप्त करता है या सेट करता है। |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | लेयर निर्माण तिथि और समय को प्राप्त करता है या सेट करता है। |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | लेयर लॉक को प्राप्त करता है या सेट करता है। ध्यान दें कि यदि फ़्लैग LayerFlags.TransparencyProtected सेट है तो इसे लेयर लॉक फ़्लैग द्वारा अधिलेखित किया जाएगा। LayerFlags.TransparencyProtected फ़्लैग को वापस करने के लिए लेयर विकल्प layer.Flags &#x7C;= LayerFlags.TransparencyProtected लागू करना आवश्यक है। |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | लेयर मास्क डेटा को प्राप्त करता है या सेट करता है। |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | लेयर विकल्प प्राप्त करता है। |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | बाएँ लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | बाइट्स में कुल लेयर लंबाई प्राप्त करता है। |
| [MasterChannel](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/masterchannel/) { get; } | मास्टर चैनल प्राप्त करता है। |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | लेयर नाम को प्राप्त करता है या सेट करता है। |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | लेयर अपारदर्शिता को प्राप्त करता है या सेट करता है। 0 = पारदर्शी, 255 = अपारदर्शी। |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे प्रतिनिधित्व किए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता। |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि छवि घटकों को पूर्व-गुणा किया जाना चाहिए या नहीं। |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | कस्टम रंग कनवर्टर को प्राप्त करता है या सेट करता है। |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | कच्चा डेटा फ़ॉर्मेट प्राप्त करता है। |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। ध्यान दें कि इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग करने के लिए फॉलबैक इंडेक्स प्राप्त करता है या सेट करता है |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | इंडेक्स्ड कलर कनवर्टर प्राप्त करता है या सेट करता है |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | बाइट्स में कच्ची लाइन आकार प्राप्त करता है। |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | लेयर रिसोर्सेज़ प्राप्त करता है या सेट करता है। |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | दाएँ लेयर की स्थिति प्राप्त करता है या सेट करता है। |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | लेयर्स की सूची में सजावटी शीट रंग हाइलाइट प्राप्त करता है या सेट करता है |
| [Size](../../aspose.psd/image/size/) { get; } | छवि का आकार प्राप्त करता है। |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | ऊपर की लेयर की स्थिति प्राप्त करता है या सेट करता है। |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | छवि का पारदर्शी रंग प्राप्त करता है। |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | XMP मेटाडेटा को अपडेट करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | छवि पैलेट उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | जब कच्चा डेटा लोडिंग उपलब्ध हो, तो कच्चा डेटा लोडिंग उपयोग करना है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | इस [`RasterImage`](../../aspose.psd/rasterimage/) की लंबवत रेज़ोल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | छवि की चौड़ाई प्राप्त करता है। |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | XMP मेटाडेटा प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | वर्तमान लेयर में मास्क जोड़ता है। |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | छवि की चमक को समायोजित करता है। |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | छवि कंट्रास्टिंग |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | छवि का गामा-करेक्शन। |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | छवि का गामा-करेक्शन। |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | लेयर पर लेयर मास्क लागू करता है, फिर मास्क को हटाता है। |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | पूर्वनिर्धारित थ्रेशोल्ड के साथ छवि का बाइनरीकरण |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | ओट्सु थ्रेशोल्डिंग के साथ छवि का बाइनरीकरण |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) से कोई अतिरिक्त डेटा लोडिंग नहीं की जाएगी। |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | निर्धारित करता है कि क्या छवि को पास किए गए सहेजने विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है। |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | छवि को क्रॉप करना। |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | शिफ्ट के साथ छवि को क्रॉप करें। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | वर्तमान छवि पर डिथरिंग करता है। |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | वर्तमान छवि पर डिथरिंग करता है। |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | लेयर पर छवि को ड्रॉ करता है। |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | निर्दिष्ट आयत को फ़िल्टर करता है। |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | एक छवि का 32-बिट ARGB पिक्सेल प्राप्त करता है। |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/getchannel/)(int) | चैनल प्राप्त करता है। |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है। |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | इस उदाहरण के लिए एक हैश कोड लौटाता है। |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | संसाधन छवि के अंतिम संशोधित होने की तिथि और समय प्राप्त करता है। |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है। यह मूल छवि की बिट-डेप्थ और अन्य पैरामीटर को अपरिवर्तित रखने में मददगार हो सकता है। उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले ब्लैक-व्हाइट PNG छवि को लोड करते हैं और फिर [`Save`](../../aspose.psd/datastreamsupporter/save/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी। इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने विकल्प प्राप्त करें और उन्हें दूसरे पैरामीटर के रूप में [`Save`](../../aspose.psd/image/save/) मेथड को पास करें। |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | एक छवि पिक्सेल प्राप्त करता है। प्रदर्शन चेतावनी: सभी छवि पिक्सेल पर इटररेट करने के लिए इस मेथड का उपयोग करने से बचें क्योंकि इससे महत्वपूर्ण प्रदर्शन समस्याएँ हो सकती हैं। अधिक कुशल पिक्सेल हेरफेर के लिए, पूरे पिक्सेल एरे को एक साथ प्राप्त करने हेतु `LoadArgb32Pixels` मेथड का उपयोग करें। |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | स्क्यू कोण प्राप्त करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर लागू होता है, स्कैनिंग के दौरान स्क्यू कोण निर्धारित करने के लिए। |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | छवि को उसके ग्रेस्केल प्रतिनिधित्व में रूपांतरित करना |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | 32-बिट ARGB पिक्सेल लोड करता है। |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | 64-बिट ARGB पिक्सेल लोड करता है। |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | CMYK फ़ॉर्मेट में पिक्सेल लोड करता है। यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/) मेथड का उपयोग करें। |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | पैक्स द्वारा आंशिक रूप से 32-बिट ARGB पिक्सेल लोड करता है। |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है। |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | पिक्सेल लोड करता है। |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | कच्चा डेटा लोड करता है। |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | कच्चा डेटा लोड करता है। |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | लेयर को निर्दिष्ट लेयर में मर्ज करता है। |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) और [`Rotate`](../../aspose.psd/rasterimage/rotate/) मेथड्स का उपयोग करता है। |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | कोण को सामान्यीकृत करता है। यह मेथड स्कैन किए गए टेक्स्ट दस्तावेज़ों पर विकृत स्कैन को हटाने के लिए लागू होता है। यह मेथड [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) और [`Rotate`](../../aspose.psd/rasterimage/rotate/) मेथड्स का उपयोग करता है। |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | अनुमत अंतर के साथ एक रंग को दूसरे से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली इमेज पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली इमेज पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| [Resize](../../aspose.psd/image/resize/)(int, int) | इमेज का आकार बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | इमेज का आकार बदलता है। |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | इमेज का आकार बदलता है। |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट NearestNeighbourResample उपयोग किया जाता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | इमेज को केंद्र के चारों ओर घुमाता है। |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | इमेज को केंद्र के चारों ओर घुमाता है। |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | इमेज को घुमाता है, फ़्लिप करता है, या घुमाकर फ़्लिप करता है। |
| [Save](../../aspose.psd/image/save/)() | इमेज डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | इमेज का डेटा निर्दिष्ट फ़ाइल फ़ॉर्मेट में, सहेजने के विकल्पों के अनुसार, निर्दिष्ट स्ट्रीम में सहेजता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | ऑब्जेक्ट का डेटा सहेजने के विकल्पों के अनुसार, निर्दिष्ट फ़ाइल फ़ॉर्मेट में, निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | 32-बिट ARGB पिक्सेल को सहेजता है। |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | पिक्सेल को सहेजता है। |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | पिक्सेल को सहेजता है। यह मेथड अब अप्रचलित है। कृपया अधिक प्रभावी [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/) मेथड का उपयोग करें। |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | पिक्सेल को सहेजता है। |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | कच्चा डेटा सहेजता है। |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | निर्दिष्ट स्थिति के लिए इमेज का 32-बिट ARGB पिक्सेल सेट करता है। |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | इमेज पैलेट सेट करता है। |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | निर्दिष्ट स्थिति के लिए इमेज पिक्सेल सेट करता है। |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | इस [`RasterImage`](../../aspose.psd/rasterimage/) की रिज़ॉल्यूशन सेट करता है। |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | वर्तमान लेयर की शैलो कॉपी बनाता है। व्याख्या के लिए कृपया [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) देखें। |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | रास्टर इमेज को बिटमैप में बदलता है। |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |

### देखें भी

* class [AdjustmentLayer](../adjustmentlayer/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)



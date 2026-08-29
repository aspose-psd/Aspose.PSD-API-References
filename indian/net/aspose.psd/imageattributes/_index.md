---
title: "क्लास ImageAttributes"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.ImageAttributes क्लास। एक ImageAttributes ऑब्जेक्ट में यह जानकारी होती है कि रेंडरिंग के दौरान बिटमैप और मेटाफाइल रंग कैसे संशोधित किए जाते हैं। एक ImageAttributes ऑब्जेक्ट कई coloradjustment सेटिंग्स को बनाए रखता है जिसमें coloradjustment मैट्रिक्स, grayscaleadjustment मैट्रिक्स, gammacorrection मान, colormap टेबल और colorthreshold मान शामिल हैं। रेंडरिंग के दौरान रंगों को सुधारा, गहरा, हल्का या हटाया जा सकता है। ऐसी संशोधनों को लागू करने के लिए एक ImageAttributes ऑब्जेक्ट को इनिशियलाइज़ करें और उस ImageAttributes ऑब्जेक्ट का पथ तथा एक Image का पथ DrawImage मेथड को पास करें।"
type: docs
weight: 5080
url: /hi/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

एक `ImageAttributes` ऑब्जेक्ट में यह जानकारी होती है कि रेंडरिंग के दौरान बिटमैप और मेटाफाइल रंग कैसे संशोधित किए जाते हैं। एक `ImageAttributes` ऑब्जेक्ट कई color-adjustment सेटिंग्स को बनाए रखता है, जिसमें color-adjustment मैट्रिक्स, grayscale-adjustment मैट्रिक्स, gamma-correction मान, color-map टेबल, और color-threshold मान शामिल हैं। रेंडरिंग के दौरान रंगों को सुधारा, गहरा, हल्का या हटाया जा सकता है। ऐसी संशोधनों को लागू करने के लिए, एक `ImageAttributes` ऑब्जेक्ट को इनिशियलाइज़ करें और उस `ImageAttributes` ऑब्जेक्ट का पथ (साथ ही एक [`Image`](../image/) का पथ) DrawImage मेथड को पास करें।

```csharp
public sealed class ImageAttributes
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageAttributes](imageattributes/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | इस `ImageAttributes` ऑब्जेक्ट की ब्रश color-remap टेबल को साफ़ करता है। |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | डिफ़ॉल्ट श्रेणी के लिए color key (पारदर्शिता रेंज) को साफ़ करता है। |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए color key (पारदर्शिता रेंज) को साफ़ करता है। |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | डिफ़ॉल्ट श्रेणी के लिए color-adjustment मैट्रिक्स को साफ़ करता है। |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए color-adjustment मैट्रिक्स को साफ़ करता है। |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | डिफ़ॉल्ट श्रेणी के लिए gamma correction को निष्क्रिय करता है। |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए gamma correction को निष्क्रिय करता है। |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | डिफ़ॉल्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल color profile सेटिंग को साफ़ करता है। |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए आउटपुट चैनल color profile सेटिंग को साफ़ करता है। |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | डिफ़ॉल्ट श्रेणी के लिए color-remap टेबल को साफ़ करता है। |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए color-remap टेबल को साफ़ करता है। |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है। |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है। |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | ब्रश श्रेणी के लिए कलर-रीमैप तालिका सेट करता है। |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | डिफ़ॉल्ट श्रेणी के लिए कलर की सेट करता है। |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | निर्दिष्ट श्रेणी के लिए कलर की (पारदर्शिता सीमा) सेट करता है। |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | डिफ़ॉल्ट श्रेणी के लिए कलर-एडजस्टमेंट मैट्रिक्स और ग्रेस्केल-एडजस्टमेंट मैट्रिक्स सेट करता है। |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | डिफ़ॉल्ट श्रेणी के लिए कलर-एडजस्टमेंट मैट्रिक्स और ग्रेस्केल-एडजस्टमेंट मैट्रिक्स सेट करता है। |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | निर्दिष्ट श्रेणी के लिए कलर-एडजस्टमेंट मैट्रिक्स और ग्रेस्केल-एडजस्टमेंट मैट्रिक्स सेट करता है। |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | डिफ़ॉल्ट श्रेणी के लिए कलर-एडजस्टमेंट मैट्रिक्स सेट करता है। |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | डिफ़ॉल्ट श्रेणी के लिए कलर-एडजस्टमेंट मैट्रिक्स सेट करता है। |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | निर्दिष्ट श्रेणी के लिए कलर-एडजस्टमेंट मैट्रिक्स सेट करता है। |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | डिफ़ॉल्ट श्रेणी के लिए गामा मान सेट करता है। |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | निर्दिष्ट श्रेणी के लिए गामा मान सेट करता है। |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | डिफ़ॉल्ट श्रेणी के लिए कलर एडजस्टमेंट को बंद करता है। |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | निर्दिष्ट श्रेणी के लिए कलर एडजस्टमेंट को बंद करता है। |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | निर्दिष्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल कलर-प्रोफ़ाइल फ़ाइल सेट करता है। |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | निर्दिष्ट श्रेणी के लिए आउटपुट चैनल कलर-प्रोफ़ाइल फ़ाइल सेट करता है। |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | डिफ़ॉल्ट श्रेणी के लिए कलर-रीमैप तालिका सेट करता है। |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | निर्दिष्ट श्रेणी के लिए कलर-रीमैप तालिका सेट करता है। |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड (पारदर्शिता सीमा) सेट करता है। |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | निर्दिष्ट श्रेणी के लिए थ्रेशहोल्ड (पारदर्शिता सीमा) सेट करता है। |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | रैप मोड सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा होता है तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है। |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा होता है तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है। |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा होता है तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



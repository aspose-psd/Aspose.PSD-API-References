---
title: Class PixelDataFormat
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.PixelDataFormat कक्ष. पक्सेल डेट प्ररूप यह एक अपरवर्तनय वस्तु है
type: docs
weight: 5230
url: /hi/net/aspose.psd/pixeldataformat/
---
## PixelDataFormat class

पिक्सेल डेटा प्रारूप। यह एक अपरिवर्तनीय वस्तु है।

```csharp
public class PixelDataFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | हो जाता है`PixelDataFormat` सियान, मैजेंटा, पीले और काले प्रत्येक के लिए 8 बिट्स के साथ 32 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | acmyk प्राप्त करता है। |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | हो जाता है`PixelDataFormat`0-255 अंतराल में ग्रेस्केल तीव्रता का प्रतिनिधित्व करने वाले 8 बिट्स के साथ 8 बिट प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | हो जाता है`PixelDataFormat` 0-255 अंतराल और अतिरिक्त 8 बिट अल्फा घटक में ग्रेस्केल तीव्रता का प्रतिनिधित्व करने वाले 8 बिट्स के साथ 16 बिट प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | हो जाता है`PixelDataFormat` लाल, हरे और नीले रंग में से प्रत्येक के लिए 5 बिट्स के साथ 16 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है, अल्फा परिभाषित नहीं है। |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | हो जाता है`PixelDataFormat`लाल के लिए 5 बिट, हरे रंग के लिए 6 बिट और नीले रंग के लिए 5 बिट के साथ 16 बिट प्रति पिक्सेल के लिए परिभाषित किया गया है, अल्फा परिभाषित नहीं है। |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | हो जाता है`PixelDataFormat` 24 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है, प्रत्येक अल्फा, लाल, हरे और नीले रंग के लिए 8 बिट्स के साथ, अल्फा परिभाषित नहीं है। |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | हो जाता है`PixelDataFormat` 24 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है, प्रत्येक अल्फा, लाल, हरे और नीले रंग के लिए 8 बिट्स के साथ, अल्फा परिभाषित नहीं है। |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | हो जाता है`PixelDataFormat` प्रत्येक अल्फा, लाल, हरे और नीले रंग के लिए 8 बिट्स के साथ 32 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | हो जाता है`PixelDataFormat` प्रत्येक अल्फा, लाल, हरे और नीले रंग के लिए 8 बिट्स के साथ 32 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | हो जाता है`PixelDataFormat` प्रत्येक अल्फा, लाल, हरे और नीले रंग के लिए 16 बिट्स के साथ 64 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | हो जाता है`PixelDataFormat` अनुक्रमित 1 बिट प्रति रंग के लिए परिभाषित किया गया है। अनुक्रमित पिक्सेल डेटा स्टोरेज का उद्देश्य रंग पैलेट का उपयोग करने वाले हर जगह डेटा संग्रहण और पुनर्प्राप्ति की अनुमति देना है। सावधानी के साथ उपयोग करें, क्योंकि एक पैलेट से दूसरे या आरजीबीए से अनुक्रमित रंग मॉडल में रूपांतरण की आवश्यकता हो सकती है . |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | हो जाता है`PixelDataFormat`अनुक्रमित 2 बिट प्रति रंग के लिए परिभाषित किया गया है। अनुक्रमित पिक्सेल डेटा स्टोरेज का उद्देश्य हर जगह रंग पैलेट का उपयोग करने वाले डेटा भंडारण और पुनर्प्राप्ति की अनुमति देना है। सावधानी के साथ उपयोग करें, क्योंकि एक पैलेट से दूसरे या आरजीबीए से अनुक्रमित रंग मॉडल में रूपांतरण की आवश्यकता हो सकती है . |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | हो जाता है`PixelDataFormat` अनुक्रमित 4 बिट प्रति रंग के लिए परिभाषित किया गया है। अनुक्रमित पिक्सेल डेटा स्टोरेज का उद्देश्य हर जगह रंग पैलेट का उपयोग करने वाले डेटा भंडारण और पुनर्प्राप्ति की अनुमति देना है। सावधानी के साथ उपयोग करें, क्योंकि एक पैलेट से दूसरे में या आरजीबीए से अनुक्रमित रंग मॉडल में रूपांतरण की आवश्यकता हो सकती है . |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | हो जाता है`PixelDataFormat` अनुक्रमित 8 बिट प्रति रंग के लिए परिभाषित किया गया है। अनुक्रमित पिक्सेल डेटा स्टोरेज का उद्देश्य हर जगह रंग पैलेट का उपयोग करने वाले डेटा भंडारण और पुनर्प्राप्ति की अनुमति देना है। सावधानी के साथ उपयोग करें, क्योंकि एक पैलेट से दूसरे या आरजीबीए से अनुक्रमित रंग मॉडल में रूपांतरण की आवश्यकता हो सकती है . |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | हो जाता है`PixelDataFormat` लूमा, ब्लू-डिफरेंस और रेड-डिफरेंस क्रोमा घटकों में से प्रत्येक के लिए 8 बिट्स के साथ 24 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | हो जाता है`PixelDataFormat` प्रत्येक लूमा, ब्लू-डिफरेंस, रेड-डिफरेंस और ब्लैक क्रोमा घटकों के लिए 8 बिट्स के साथ 32 बिट्स प्रति पिक्सेल के लिए परिभाषित किया गया है। |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | बिट्स प्रति पिक्सेल प्राप्त करता है। |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | पिक्सेल डेटा प्रारूप कैप्शन प्राप्त करता है। |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | प्रत्येक चैनल के लिए बिट्स की गणना करता है। |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | चैनलों की गिनती करता है. |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | पिक्सेल प्रारूप प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ बीजीआर रंग प्राप्त करता है। |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ बीजीआरए रंग प्राप्त करता है। |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | प्रति नमूने बिट्स की एक निर्दिष्ट संख्या के साथ CIE लैब रंग प्राप्त करता है। |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | प्रति नमूना बिट्स की निर्दिष्ट संख्या के साथ CMYK रंग प्राप्त करता है। |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | प्रति नमूना बिट्स की निर्दिष्ट संख्या के साथ CMYK रंग प्राप्त करता है। |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ CMYKA रंग प्राप्त करता है। |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ ग्रेस्केल रंग प्राप्त करता है। |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | ग्रेस्केलअल्फा रंग प्राप्त करता है जिसमें प्रति नमूना बिट्स की निर्दिष्ट संख्या होती है। |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | ग्रेस्केलअल्फा रंग प्राप्त करता है जिसमें प्रति नमूना बिट्स की निर्दिष्ट संख्या होती है। |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ आरजीबी रंग प्राप्त करता है। |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ आरजीबी रंग प्राप्त करता है। |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ RGBA रंग प्राप्त करता है। |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ RGBA रंग प्राप्त करता है। |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ बीजीआरए अनुक्रमित रंग प्राप्त करता है। |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | वाईसीबीसीआर रंग प्राप्त करता है जिसमें प्रति नमूना बिट्स की निर्दिष्ट संख्या होती है। |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | वाईसीबीसीआर रंग प्राप्त करता है जिसमें प्रति नमूना बिट्स की निर्दिष्ट संख्या होती है। |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | प्रति नमूने बिट्स की निर्दिष्ट संख्या के साथ YCCK रंग प्राप्त करता है। |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | निर्धारित करता है कि निर्दिष्ट किया गया है या नहींObject इस उदाहरण के बराबर है. |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | इस उदाहरण के लिए एक हैश कोड लौटाता है। |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | दो के लिए समानता का परिणाम लौटाता है`PixelDataFormat` कक्षाएं. |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | दो के लिए असमानता का परिणाम देता है`PixelDataFormat` कक्षाएं. |

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)



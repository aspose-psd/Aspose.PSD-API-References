---
title: "क्लास PixelDataFormat"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.PixelDataFormat क्लास। पिक्सेल डेटा फ़ॉर्मेट। यह एक अपरिवर्तनीय ऑब्जेक्ट है।"
type: docs
weight: 5720
url: /hi/net/aspose.psd/pixeldataformat/
---
{{< psd/tize >}}
## PixelDataFormat class

पिक्सेल डेटा फ़ॉर्मेट। यह एक अपरिवर्तनीय ऑब्जेक्ट है।

```csharp
public class PixelDataFormat
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Cmyk](../../aspose.psd/pixeldataformat/cmyk/) { get; } | `PixelDataFormat` प्राप्त करता है जो 32 बिट्स प्रति पिक्सेल के लिए परिभाषित है, जिसमें सियान, मैजेंटा, येलो और ब्लैक के लिए प्रत्येक 8 बिट्स हैं। |
| static [Cmyka](../../aspose.psd/pixeldataformat/cmyka/) { get; } | acmyk प्राप्त करता है। |
| static [Grayscale](../../aspose.psd/pixeldataformat/grayscale/) { get; } | `PixelDataFormat` प्राप्त करता है जो 8 बिट्स प्रति पिक्सेल के लिए परिभाषित है, जिसमें 0-255 अंतराल में ग्रेस्केल इंटेंसिटी को दर्शाने के लिए 8 बिट्स होते हैं। |
| static [GrayscaleAlpha](../../aspose.psd/pixeldataformat/grayscalealpha/) { get; } | `PixelDataFormat` प्राप्त करता है जो 16 बिट्स प्रति पिक्सेल के लिए परिभाषित है, जिसमें 0-255 अंतराल में ग्रेस्केल इंटेंसिटी को दर्शाने के लिए 8 बिट्स और अतिरिक्त 8 बिट अल्फा कंपोनेंट है। |
| static [Rgb16Bpp555](../../aspose.psd/pixeldataformat/rgb16bpp555/) { get; } | `PixelDataFormat` प्राप्त करता है जो 16 बिट्स प्रति पिक्सेल के लिए परिभाषित है, जिसमें रेड, ग्रीन और ब्लू के लिए प्रत्येक 5 बिट्स हैं, अल्फा परिभाषित नहीं है। |
| static [Rgb16Bpp565](../../aspose.psd/pixeldataformat/rgb16bpp565/) { get; } | `PixelDataFormat` प्राप्त करता है जो 16 बिट्स प्रति पिक्सेल के लिए परिभाषित है, जिसमें रेड के लिए 5 बिट्स, ग्रीन के लिए 6 बिट्स और ब्लू के लिए 5 बिट्स हैं, अल्फा परिभाषित नहीं है। |
| static [Rgb24Bpp](../../aspose.psd/pixeldataformat/rgb24bpp/) { get; } | `PixelDataFormat` प्राप्त करता है जो 24 बिट्स प्रति पिक्सेल के लिए परिभाषित है, जिसमें अल्फा, रेड, ग्रीन और ब्लू के लिए प्रत्येक 8 बिट्स हैं, अल्फा परिभाषित नहीं है। |
| static [Rgb24BppPng](../../aspose.psd/pixeldataformat/rgb24bpppng/) { get; } | `PixelDataFormat` प्राप्त करता है जो 24 बिट्स प्रति पिक्सेल के लिए परिभाषित है, जिसमें अल्फा, रेड, ग्रीन और ब्लू के लिए प्रत्येक 8 बिट्स हैं, अल्फा परिभाषित नहीं है। |
| static [Rgb32Bpp](../../aspose.psd/pixeldataformat/rgb32bpp/) { get; } | 32 बिट प्रति पिक्सेल के लिए परिभाषित `PixelDataFormat` प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट होते हैं। |
| static [Rgba32Bpp](../../aspose.psd/pixeldataformat/rgba32bpp/) { get; } | 32 बिट प्रति पिक्सेल के लिए परिभाषित `PixelDataFormat` प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट होते हैं। |
| static [Rgba64Bpp](../../aspose.psd/pixeldataformat/rgba64bpp/) { get; } | 64 बिट प्रति पिक्सेल के लिए परिभाषित `PixelDataFormat` प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 16 बिट होते हैं। |
| static [RgbIndexed1Bpp](../../aspose.psd/pixeldataformat/rgbindexed1bpp/) { get; } | इंडेक्स्ड 1 बिट प्रति रंग के लिए परिभाषित `PixelDataFormat` प्राप्त करता है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य रंग पैलेट के उपयोग किए जाने वाले सभी स्थानों पर डेटा संग्रह और पुनर्प्राप्ति की सुविधा प्रदान करना है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे में या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| static [RgbIndexed2Bpp](../../aspose.psd/pixeldataformat/rgbindexed2bpp/) { get; } | इंडेक्स्ड 2 बिट प्रति रंग के लिए परिभाषित `PixelDataFormat` प्राप्त करता है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य रंग पैलेट के उपयोग किए जाने वाले सभी स्थानों पर डेटा संग्रह और पुनर्प्राप्ति की सुविधा प्रदान करना है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे में या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| static [RgbIndexed4Bpp](../../aspose.psd/pixeldataformat/rgbindexed4bpp/) { get; } | इंडेक्स्ड 4 बिट प्रति रंग के लिए परिभाषित `PixelDataFormat` प्राप्त करता है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य रंग पैलेट के उपयोग किए जाने वाले सभी स्थानों पर डेटा संग्रह और पुनर्प्राप्ति की सुविधा प्रदान करना है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे में या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| static [RgbIndexed8Bpp](../../aspose.psd/pixeldataformat/rgbindexed8bpp/) { get; } | इंडेक्स्ड 8 बिट प्रति रंग के लिए परिभाषित `PixelDataFormat` प्राप्त करता है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य रंग पैलेट के उपयोग किए जाने वाले सभी स्थानों पर डेटा संग्रह और पुनर्प्राप्ति की सुविधा प्रदान करना है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे में या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| static [YCbCr](../../aspose.psd/pixeldataformat/ycbcr/) { get; } | 24 बिट प्रति पिक्सेल के लिए परिभाषित `PixelDataFormat` प्राप्त करता है, जिसमें ल्यूमा, ब्लू-डिफरेंस और रेड-डिफरेंस क्रोमा घटकों के प्रत्येक के लिए 8 बिट होते हैं। |
| static [Ycck](../../aspose.psd/pixeldataformat/ycck/) { get; } | 32 बिट प्रति पिक्सेल के लिए परिभाषित `PixelDataFormat` प्राप्त करता है, जिसमें ल्यूमा, ब्लू-डिफरेंस, रेड-डिफरेंस और ब्लैक क्रोमा घटकों के प्रत्येक के लिए 8 बिट होते हैं। |
| [BitsPerPixel](../../aspose.psd/pixeldataformat/bitsperpixel/) { get; } | पिक्सेल प्रति बिट्स प्राप्त करता है। |
| [Caption](../../aspose.psd/pixeldataformat/caption/) { get; } | पिक्सेल डेटा फ़ॉर्मेट कैप्शन प्राप्त करता है। |
| [ChannelBits](../../aspose.psd/pixeldataformat/channelbits/) { get; } | प्रत्येक चैनल के लिए बिट्स की गिनती प्राप्त करता है। |
| [ChannelsCount](../../aspose.psd/pixeldataformat/channelscount/) { get; } | चैनलों की गिनती प्राप्त करता है। |
| [PixelFormat](../../aspose.psd/pixeldataformat/pixelformat/) { get; } | पिक्सेल फ़ॉर्मेट प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [GetBgr](../../aspose.psd/pixeldataformat/getbgr/)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ BGR रंग प्राप्त करता है। |
| static [GetBgra](../../aspose.psd/pixeldataformat/getbgra/)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA रंग प्राप्त करता है। |
| static [GetCieLab](../../aspose.psd/pixeldataformat/getcielab/)(int, int, int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CIE Lab रंग प्राप्त करता है। |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYK रंग प्राप्त करता है। |
| static [GetCmyk](../../aspose.psd/pixeldataformat/getcmyk/#getcmyk_1)(int, int, int, int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYK रंग प्राप्त करता है। |
| static [GetCmyka](../../aspose.psd/pixeldataformat/getcmyka/)(int, int, int, int, int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYKA रंग प्राप्त करता है। |
| static [GetGrayscale](../../aspose.psd/pixeldataformat/getgrayscale/)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ ग्रेस्केल रंग प्राप्त करता है। |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ GrayscaleAlpha रंग प्राप्त करता है। |
| static [GetGrayscaleAlpha](../../aspose.psd/pixeldataformat/getgrayscalealpha/#getgrayscalealpha_1)(int, int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ GrayscaleAlpha रंग प्राप्त करता है। |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGB रंग प्राप्त करता है। |
| static [GetRgb](../../aspose.psd/pixeldataformat/getrgb/#getrgb_1)(int, int, int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGB रंग प्राप्त करता है। |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGBA रंग प्राप्त करता है। |
| static [GetRgba](../../aspose.psd/pixeldataformat/getrgba/#getrgba_1)(int, int, int, int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGBA रंग प्राप्त करता है। |
| static [GetRgbIndexed](../../aspose.psd/pixeldataformat/getrgbindexed/)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA इंडेक्स्ड रंग प्राप्त करता है। |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ YCbCr रंग प्राप्त करता है। |
| static [GetYCbCr](../../aspose.psd/pixeldataformat/getycbcr/#getycbcr_1)(int, int, int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ YCbCr रंग प्राप्त करता है। |
| static [GetYcck](../../aspose.psd/pixeldataformat/getycck/)(int) | निर्दिष्ट नमूना बिट्स की संख्या के साथ YCCK रंग प्राप्त करता है। |
| override [Equals](../../aspose.psd/pixeldataformat/equals/)(object) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.psd/pixeldataformat/gethashcode/)() | इस उदाहरण के लिए एक हैश कोड लौटाता है। |
| override [ToString](../../aspose.psd/pixeldataformat/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [operator ==](../../aspose.psd/pixeldataformat/op_equality/) | दो `PixelDataFormat` क्लासों के लिए समानता का परिणाम लौटाता है। |
| [operator !=](../../aspose.psd/pixeldataformat/op_inequality/) | दो `PixelDataFormat` क्लासों के बीच असमानता का परिणाम लौटाता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



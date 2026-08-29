---
title: "क्लास RawColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor class. Raw Color क्लास किसी भी चैनल संख्या, किसी भी रंग मोड और किसी भी बिट गहराई के साथ रंगों को संग्रहीत करने में मदद करती है। कृपया ध्यान दें कि कुछ आंतरिक क्लासों को RawColor को उसके मूल स्वरूप में परिवर्तित करने में समस्याएँ हो सकती हैं, इसलिए यदि API आपके लिए CMYK रंग प्रदान करती है तो प्रदान किए गए स्वरूप का उपयोग अधिक विश्वसनीय है। साथ ही कुछ मामलों में Raw Color को परिवर्तित किया जा सकता है।"
type: docs
weight: 1650
url: /hi/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class किसी भी चैनल संख्या, किसी भी कलर मोड और किसी भी बिट डेप्थ के साथ रंगों को स्टोर करने में मदद करता है। कृपया ध्यान दें, कुछ आंतरिक क्लासेज़ RawColor को उसके मूल फ़ॉर्मेट में बदलने में समस्याएँ पैदा कर सकती हैं, इसलिए यदि API आपके लिए CMYK रंग प्रदान करती है, तो प्रदान किए गए फ़ॉर्मेट का उपयोग करना अधिक विश्वसनीय है। साथ ही, कुछ मामलों में Raw Color को बदला जा सकता है।

```csharp
public sealed class RawColor
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | `RawColor` क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | प्रीडिफाइंड कलर मोड्स का उपयोग करके पिक्सेल डेटा फ़ॉर्मेट से `RawColor` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | रंग के लिए अनुसरण करने वाला मोड। |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | रंग के घटकों को प्राप्त करता है। प्रत्येक घटक एक अलग चैनल है, और यदि आप कम लोकप्रिय रंग योजना का उपयोग करते हैं, तो प्रत्येक चैनल के साथ अलग-अलग काम करना बेहतर है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं। |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | यदि संभव हो तो रंग को int के रूप में प्राप्त करता है। |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | यदि संभव हो तो रंग को long के रूप में प्राप्त करता है। |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Raw Color की बिट डेप्थ प्राप्त करता है। उदाहरण के लिए, ARGB रंग के लिए प्रत्येक चैनल/कॉम्पोनेन्ट में 8 बिट होने पर कुल बिट डेप्थ 32 होती है, और प्रत्येक चैनल/कॉम्पोनेन्ट में 16 बिट होने पर कुल बिट डेप्थ 64 होती है। बिट डेप्थ चैनलों की बिट डेप्थ के योग से प्राप्त होती है। यह संभव है यदि विभिन्न चैनलों की बिट डेप्थ अलग-अलग हो। |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | रंग मोड का नाम प्राप्त करता है। रंग मोड का नाम चैनलों/कॉम्पोनेन्ट्स के नामों से संकलित होता है। |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | वर्तमान ऑब्जेक्ट का हैश कोड प्राप्त करें। |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | यदि संभव हो तो int आर्ग्यूमेंट से सभी चैनलों के डेटा को सेट करता है। |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | यदि संभव हो तो int आर्ग्यूमेंट से सभी चैनलों के डेटा को सेट करता है। |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | ऑपरेटर == को लागू करता है। |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | ऑपरेटर != को लागू करता है। |

## उदाहरण

निम्नलिखित कोड पुरानी Color स्ट्रक्ट के बजाय RawColor क्लास के समर्थन को दर्शाता है।

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)



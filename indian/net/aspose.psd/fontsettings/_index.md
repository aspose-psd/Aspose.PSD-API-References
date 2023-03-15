---
title: Class FontSettings
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FontSettings कक्ष. समन्य PSD वेक्टर प्ररूप रेंडरर फ़न्ट सेटंग.
type: docs
weight: 4290
url: /hi/net/aspose.psd/fontsettings/
---
## FontSettings class

सामान्य PSD वेक्टर प्रारूप रेंडरर फ़ॉन्ट सेटिंग.

```csharp
public static class FontSettings
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | फ़ॉन्ट का डिफ़ॉल्ट नाम प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | सभी फ़ॉन्ट प्रतिस्थापन साफ़ करता है |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | फ़ॉन्ट परिवार के नाम से एडोब फ़ॉन्ट नाम प्राप्त करता है। |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | डिफ़ॉल्ट फ़ॉन्ट फ़ोल्डर प्राप्त करता है। |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | फ़ॉन्ट नाम द्वारा फ़ॉन्ट प्रतिस्थापन सरणी प्राप्त करता है |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | उस सरणी की एक प्रति प्राप्त करता है जिसमें उन फ़ोल्डरों की सूची होती है जहाँ Aspose.Words ट्रू टाइप फ़ॉन्ट्स की तलाश करता है। |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | सबसे उपयुक्त प्रतिस्थापन फ़ॉन्ट प्राप्त करता है। यदि सभी प्रतिस्थापनों की अनुमति नहीं है तो पहले अनुमत और उपलब्ध फ़ॉन्ट वापस कर दिया जाएगा। |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | निर्धारित करता है कि क्या [फ़ॉन्ट की अनुमति है] [निर्दिष्ट फ़ॉन्ट नाम]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | फ़ॉन्ट फ़ोल्डर और डिफ़ॉल्ट फ़ॉन्ट नाम को सिस्टम डिफ़ॉल्ट पर रीसेट करता है। |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | फोंट की सूची द्वारा उपयोग करने वाले फ़ॉन्ट को प्रतिबंधित करता है। कृपया प्रतिबंध से पहले वास्तविक फ़ॉन्ट नामों की जांच करें प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को शून्य पर सेट करें |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फॉन्ट की अनुमति नहीं है तो प्रतिस्थापन ढूंढा जाएगा। सूची में पहले वाले फॉन्ट का पहले उपयोग किया जाएगा। यदि यह भी हटा दिया गया है, तो सूची से अगले फ़ॉन्ट का चयन किया जाएगा। सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने का प्रयास करें, भले ही इसकी अनुमति न हो। |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | यह एक शॉर्टकट है[`SetFontsFolders`](./setfontsfolders/) केवल एक फ़ॉन्ट निर्देशिका सेट करने के लिए। फोंट फ़ोल्डर पर कोई जांच नहीं की जाती है। |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | उन फ़ोल्डरों को सेट करता है जहां से ट्रू टाइप फ़ॉन्ट लोड किए जाते हैं और सभी लोड किए गए फ़ॉन्ट साफ़ करते हैं. फ़ॉन्ट फ़ोल्डर पर कोई जांच नहीं की जाती है. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | उन PSD फ़ाइलों के लिए फ़ॉन्ट कैश अपडेट करता है जिनमें टेक्स्ट परतें होती हैं। यह विधि इस बात की गारंटी देती है कि फॉन्टसेटिंग.सेटफोल्डर(फोंटफोल्डर) का उपयोग करते हुए विधि का उपयोग करके फोल्डर फोंटफोल्डर से फॉन्ट या फॉन्टसेटिंग.रीसेट () का उपयोग करके फॉन्ट को रीसेट करने के बाद PSD फाइलों को संसाधित करते समय ध्यान में रखा जाएगा। कृपया हर बार इस विधि का उपयोग करें जब FontSettings.SetFontsFolder(fontsFolder) या FontSettings.Reset() PSD छवियों के लिए कहा जाता है। इस विधि को कॉल किए बिना इस बात की कोई गारंटी नहीं है कि फोंट अपडेट हो जाएंगे। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)



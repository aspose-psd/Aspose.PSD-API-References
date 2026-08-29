---
title: "Class FontSettings"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FontSettings class. सामान्य PSD वेक्टर फ़ॉर्मेट रेंडरर फ़ॉन्ट सेटिंग्स।"
type: docs
weight: 4760
url: /hi/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

सामान्य PSD वेक्टर फ़ॉर्मेट रेंडरर फ़ॉन्ट सेटिंग्स।

```csharp
public static class FontSettings
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | फ़ॉन्ट का डिफ़ॉल्ट नाम प्राप्त करता है या सेट करता है। |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [get alternative font]। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | सभी फ़ॉन्ट प्रतिस्थापनों को साफ़ करता है। |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | फ़ॉन्ट परिवार नाम के आधार पर Adobe फ़ॉन्ट नाम प्राप्त करता है। |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | डिफ़ॉल्ट फ़ॉन्ट फ़ोल्डर प्राप्त करता है। |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | फ़ॉन्ट नाम के द्वारा फ़ॉन्ट प्रतिस्थापन एरे प्राप्त करता है। |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | एक एरे की प्रतिलिपि प्राप्त करता है जिसमें उन फ़ोल्डरों की सूची होती है जहाँ Aspose.Words TrueType फ़ॉन्ट्स खोजता है। |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | सबसे उपयुक्त प्रतिस्थापन फ़ॉन्ट प्राप्त करता है। यदि सभी प्रतिस्थापन अनुमत नहीं हैं तो पहला अनुमत और उपलब्ध फ़ॉन्ट लौटाया जाएगा। यदि कोई उपलब्ध फ़ॉन्ट नहीं है तो तर्क से दिया गया फ़ॉन्ट लौटाया जाएगा। |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | निर्धारित करता है कि क्या [is font allowed] [निर्दिष्ट फ़ॉन्ट नाम]। |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | फ़ॉन्ट कैश फ़ाइल को हटाता है। |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | फ़ॉन्ट फ़ोल्डर और डिफ़ॉल्ट फ़ॉन्ट नाम को सिस्टम डिफ़ॉल्ट पर रीसेट करता है। |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | फ़ॉन्ट को फ़ॉन्टों की सूची द्वारा प्रतिबंधित करता है। प्रतिबंध से पहले वास्तविक फ़ॉन्ट नाम जाँचें। प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को Null सेट करें। |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फ़ॉन्ट अनुमत नहीं है तो प्रतिस्थापन खोजा जाएगा। सूची में पहला फ़ॉन्ट पहले उपयोग किया जाएगा। यदि वह भी प्रतिबंधित है, तो सूची से अगला फ़ॉन्ट चुना जाएगा। यदि फ़ॉन्ट के पास कोई प्रतिस्थापन नहीं है या सभी प्रतिस्थापन अनुमत नहीं हैं, तो अनुमत फ़ॉन्ट सूची से पहला अनुमत फ़ॉन्ट उपयोग किया जाएगा। यदि कोई अनुमत और उपलब्ध फ़ॉन्ट नहीं है, तो लाइब्रेरी सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने का प्रयास करेगी, भले ही वह अनुमत न हो। |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | यह केवल एक फ़ॉन्ट डायरेक्टरी सेट करने के लिए [`SetFontsFolders`](./setfontsfolders/) का शॉर्टकट है। फ़ॉन्ट फ़ोल्डर पर कोई जाँच नहीं की जाती है। |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | TrueType फ़ॉन्ट्स जहाँ लोड होते हैं, उन फ़ोल्डरों को सेट करता है और सभी लोडेड फ़ॉन्ट्स को साफ़ करता है। फ़ॉन्ट फ़ोल्डरों पर कोई जाँच नहीं की जाती है। |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | टेक्स्ट लेयर वाले PSD फ़ाइलों के लिए फ़ॉन्ट कैश को अपडेट करता है। यह मेथड यह सुनिश्चित करता है कि फ़ॉन्ट फ़ोल्डर (fontsFolder) से फ़ॉन्ट्स, चाहे FontSettings.SetFontsFolder(fontsFolder) मेथड द्वारा हों या FontSettings.Reset() के बाद रीसेट किए गए हों, PSD फ़ाइलों को प्रोसेस करते समय विचार में लिए जाएँ। कृपया इस मेथड को प्रत्येक बार उपयोग करें जब भी PSD इमेजेज के लिए FontSettings.SetFontsFolder(fontsFolder) या FontSettings.Reset() कॉल किया जाए। इस मेथड को कॉल किए बिना फ़ॉन्ट्स के अपडेट होने की कोई गारंटी नहीं है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



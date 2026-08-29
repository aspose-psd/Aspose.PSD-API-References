---
title: "क्लास CmykColorHelper"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.CmykColorHelper क्लास। CMYK रंग को एक साइन्ड 32-बिट इंटीजर वैल्यू के रूप में प्रस्तुत करने के लिए हेल्पर मेथड्स। यह CmykColor स्ट्रक्ट के समान API प्रदान करता है। यह अधिक हल्का है क्योंकि CMYK रंग केवल Int32 के रूप में प्रस्तुत किया जाता है, न कि आंतरिक फ़ील्ड वाले स्ट्रक्ट के रूप में। कृपया संभव होने पर इस क्लास के स्टैटिक मेथड्स का उपयोग करें, बजाय अप्रचलित CmykColor स्ट्रक्ट के।"
type: docs
weight: 280
url: /hi/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

CMYK रंग को एक साइन्ड 32-बिट इंटीजर वैल्यू के रूप में प्रस्तुत करने के लिए हेल्पर मेथड्स। यह [`CmykColor`](../cmykcolor/) स्ट्रक्ट के समान API प्रदान करता है। यह अधिक हल्का है क्योंकि CMYK रंग केवल Int32 के रूप में प्रस्तुत किया जाता है, न कि आंतरिक फ़ील्ड वाले स्ट्रक्ट के रूप में। कृपया संभव होने पर इस क्लास के स्टैटिक मेथड्स का उपयोग करें, बजाय अप्रचलित [`CmykColor`](../cmykcolor/) स्ट्रक्ट के।

```csharp
public static class CmykColorHelper
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 32-बिट सियान, मैजेंटा, येलो और ब्लैक मानों से CMYK बनाता है। |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | सियान कंपोनेंट वैल्यू प्राप्त करता है। |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | ब्लैक कंपोनेंट वैल्यू प्राप्त करता है। |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | मैजेंटा कंपोनेंट वैल्यू प्राप्त करता है। |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | येलो कंपोनेंट वैल्यू प्राप्त करता है। |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | CMYK रंग से ARGB रंग में रूपांतरण। |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | CMYK रंगों से ARGB रंगों में रूपांतरण। |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | CMYK रंगों से ARGB रंगों में रूपांतरण। |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंग से ARGB रंग में रूपांतरण। |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण। |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | कस्टम प्रोफ़ाइल के साथ Icc रूपांतरण का उपयोग करके CMYK रंग से ARGB रंग में रूपांतरण। |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण। |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | ARGB रंग से CMYK रंग में रूपांतरण। |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | ARGB रंग से CMYK रंग में रूपांतरण। |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | RGB को CMYK में परिवर्तित करता है। |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंग से CMYK रंग में रूपांतरण। |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण। |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंग से CMYK रंग में रूपांतरण। |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण। |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | कस्टम ICC प्रोफ़ाइलों का उपयोग करके RGB को CMYK में परिवर्तित करता है। |

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



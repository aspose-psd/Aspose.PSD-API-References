---
title: "Class StringFormat"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.StringFormat class. यह टेक्स्ट लेआउट जानकारी को समेटे हुए है जैसे संरेखण दिशा, टैब स्टॉप्स, एलिप्सिस डालना, राष्ट्रीय अंक प्रतिस्थापन और OpenType सुविधाएँ। यह क्लास विरासत में नहीं ली जा सकती।"
type: docs
weight: 6170
url: /hi/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

टेक्स्ट लेआउट जानकारी (जैसे संरेखण, अभिविन्यास और टैब स्टॉप), डिस्प्ले हेरफेर (जैसे एलिप्सिस सम्मिलन और राष्ट्रीय अंक प्रतिस्थापन) और OpenType फीचर्स को संलग्न करता है। इस क्लास को विरासत में नहीं लिया जा सकता।

```csharp
public sealed class StringFormat : DisposableObject
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | एक नया `StringFormat` ऑब्जेक्ट प्रारंभ करता है। |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | निर्दिष्ट मौजूदा `StringFormat` ऑब्जेक्ट से एक नया `StringFormat` ऑब्जेक्ट प्रारंभ करता है। |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | निर्दिष्ट [`StringFormatFlags`](../stringformatflags/) एन्क्यूमरेशन और भाषा के साथ एक नया `StringFormat` ऑब्जेक्ट प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | एक सामान्य डिफ़ॉल्ट `StringFormat` ऑब्जेक्ट प्राप्त करता है। |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | एक सामान्य टाइपोग्राफ़िक `StringFormat` ऑब्जेक्ट प्राप्त करता है। |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | ऊर्ध्वाधर तल पर टेक्स्ट संरेखण जानकारी प्राप्त करता है या सेट करता है। |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | कस्टम कैरेक्टर आइडेंट प्राप्त करता है या सेट करता है। |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | स्थानीय अंकों को पश्चिमी अंकों से बदलने पर उपयोग की जाने वाली भाषा प्राप्त करता है या सेट करता है। |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि प्राप्त करता है या सेट करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | टेक्स्ट की एक पंक्ति की शुरुआत और पहले टैब स्टॉप के बीच स्पेस की संख्या प्राप्त करता है। |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | फ़ॉर्मेटिंग जानकारी शामिल करने वाले एक [`StringFormatFlags`](../stringformatflags/) एनेमरेशन को प्राप्त करता है या सेट करता है। |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | इस `StringFormat` ऑब्जेक्ट के लिए [`HotkeyPrefix`](../hotkeyprefix/) ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | क्षैतिज तल पर लाइन संरेखण प्राप्त करता है या सेट करता है। |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | टैब स्टॉप्स के बीच दूरी की एक एरे प्राप्त करता है, जो [`PageUnit`](../graphics/pageunit/) प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में है। |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | इस `StringFormat` ऑब्जेक्ट के लिए [`StringTrimming`](../stringtrimming/) एनेमरेशन को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | इस `StringFormat` ऑब्जेक्ट की एक डीप क्लोन बनाता है। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | जाँचें कि ऑब्जेक्ट समान हैं या नहीं। |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | वर्तमान ऑब्जेक्ट का हैश कोड प्राप्त करें। |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | इस `StringFormat` ऑब्जेक्ट के लिए टैब स्टॉप्स सेट करता है। |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | इस `StringFormat` ऑब्जेक्ट को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |

### देखें भी

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



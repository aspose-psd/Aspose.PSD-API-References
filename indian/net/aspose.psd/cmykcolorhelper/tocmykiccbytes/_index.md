---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "CmykColorHelper मेथड। कस्टम ICC प्रोफाइल्स का उपयोग करके RGB को CMYK में परिवर्तित करता है"
type: docs
weight: 120
url: /hi/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

कस्टम ICC प्रोफ़ाइलों का उपयोग करके RGB को CMYK में परिवर्तित करता है।

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| पिक्सेल | Int32[] | RGB रंग 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किए गए हैं। |
| startIndex | Int32 | RGB रंग का प्रारंभिक सूचकांक। |
| लंबाई | Int32 | परिवर्तित करने के लिए RGB पिक्सेल की संख्या। |
| rgbIccStream | Stream | RGB प्रोफ़ाइल स्ट्रीम। |
| cmykIccStream | Stream | CMYK प्रोफ़ाइल स्ट्रीम। |

### रिटर्न वैल्यू

CMYK रंग बाइट एरे के रूप में प्रस्तुत किए गए हैं।

### देखें भी

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



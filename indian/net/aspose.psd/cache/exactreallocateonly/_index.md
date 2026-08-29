---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Cache property. यह दर्शाने वाला मान प्राप्त या सेट करता है कि पुनः आवंटन सटीक होना चाहिए या नहीं। यदि पुनः आवंटन सटीक नहीं है तो प्रदर्शन अधिक होना चाहिए।"
type: docs
weight: 50
url: /hi/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

पुनः आवंटन सटीक होना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि पुनः आवंटन सटीक नहीं है तो प्रदर्शन अधिक होना चाहिए।

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` यदि पुनः आवंटन सटीक है; अन्यथा, `false`।

## टिप्पणियाँ

सटीक reallocation केवल निर्दिष्ट ऊपरी सीमा तक अतिरिक्त मेमोरी का reallocation करेगा। reallocation के दौरान इन‑मे़मोरी के लिए ऊपरी सीमा पास करने पर, यदि संभव हो तो कैश किया गया डेटा डिस्क पर कॉपी किया जाएगा। डिस्क मेमोरी के लिए ऊपरी सीमा पास करने पर उपयुक्त अपवाद फेंका जाएगा। यदि यह विकल्प बंद किया जाता है तो प्रदर्शन अधिक होना चाहिए क्योंकि संभव होने पर कोई अतिरिक्त कॉपी नहीं की जाएगी, हालांकि इससे मेमोरी या डिस्क के लिए निर्दिष्ट ऊपरी सीमाओं को पार करने का जोखिम भी हो सकता है।

### देखें भी

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



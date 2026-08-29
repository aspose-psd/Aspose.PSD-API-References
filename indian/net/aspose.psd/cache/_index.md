---
title: "क्लास Cache"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.Cache क्लास। कैश सेटिंग्स शामिल करता है"
type: docs
weight: 240
url: /hi/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

कैश सेटिंग्स को शामिल करता है।

```csharp
public static class Cache
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | आवंटित डिस्क बाइट्स की गिनती प्राप्त करता है। |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | आवंटित इन‑मेमोरी बाइट्स की गिनती प्राप्त करता है। |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | कैश फ़ोल्डर को प्राप्त करता है या सेट करता है। |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | उपयोग किए गए कैश स्कीम को प्राप्त करता है या सेट करता है। |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | पुनः आवंटन सटीक होना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। यदि पुनः आवंटन सटीक नहीं है तो प्रदर्शन अधिक होना चाहिए। |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | कैश के लिए अधिकतम उपलब्ध डिस्क स्पेस को प्राप्त करता है या सेट करता है। निर्दिष्ट मान मेगाबाइट्स की गिनती है। |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | कैश के लिए मेमोरी में अधिकतम उपलब्ध मेमोरी को प्राप्त करता है या सेट करता है। निर्दिष्ट मान मेगाबाइट्स की गिनती है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | `Cache` सेटिंग्स को डिफ़ॉल्ट पर सेट करता है। |

## उदाहरण

यह उदाहरण Aspose.PSD.Cache के उपयोग को दर्शाता है।

```csharp
[C#]

// डिफ़ॉल्ट रूप से कैश फ़ोल्डर को उपयोगकर्ता की स्थानीय टेम्प डायरेक्टरी पर सेट किया जाता है।
// आप डिफ़ॉल्ट के अलावा किसी अन्य कैश फ़ोल्डर को निम्नलिखित रूप में निर्दिष्ट कर सकते हैं:
// Cache.CacheFolder = @\"D:\\\\MyTemp\";

string path = "C:\\temp\\image.psd";

// ऑटो मोड लचीला और कुशल है।
Cache.CacheType = CacheType.Auto;

// डिफ़ॉल्ट मान 0 है, जिसका अर्थ है कोई ऊपरी सीमा नहीं है।
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// निम्नलिखित प्रॉपर्टी को बदलने की अनुशंसा नहीं की जाती है क्योंकि यह प्रदर्शन को बहुत प्रभावित कर सकता है।
Cache.ExactReallocateOnly = false;

// किसी भी समय आप जांच सकते हैं कि वर्तमान में मेमोरी या डिस्क के लिए कितने बाइट्स आवंटित हैं
// कैश को निम्नलिखित प्रॉपर्टीज़ की जाँच करके
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// नीचे दर्शाए अनुसार कुछ इमेज प्रोसेसिंग करें
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // ऊपर दिया गया कोड चलाने के बाद इन‑मेमोरी में 40000 बाइट्स आवंटित हो जाएंगे।
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// आवंटन गुणों का उपयोग यह जांचने के लिए किया जा सकता है कि सभी Aspose.PSD ऑब्जेक्ट्स सही तरीके से डिस्पोज़ किए गए हैं।
// यदि आप किसी ऑब्जेक्ट पर डिस्पोज़ कॉल करना भूल गए हैं तो कैश मान 0 से अलग होंगे।
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### देखें भी

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



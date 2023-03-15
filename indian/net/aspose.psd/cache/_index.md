---
title: Class Cache
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.Cache कक्ष. में कैश सेटंग शमल है
type: docs
weight: 240
url: /hi/net/aspose.psd/cache/
---
## Cache class

में कैश सेटिंग शामिल है।

```csharp
public static class Cache
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | आवंटित डिस्क बाइट गिनती प्राप्त करता है। |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | आवंटित इन-मेमोरी बाइट काउंट प्राप्त करता है। |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | कैश फ़ोल्डर प्राप्त या सेट करता है। |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | उपयोग की गई कैश योजना प्राप्त या सेट करता है। |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि पुनर्आवंटन सटीक होना चाहिए या नहीं। यदि पुनर्आवंटन सटीक नहीं है तो प्रदर्शन अधिक होना चाहिए. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | कैश के लिए अधिकतम उपलब्ध डिस्क स्थान प्राप्त या सेट करता है। निर्दिष्ट मान मेगाबाइट्स काउंट है। |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | मेमोरी में कैशे के लिए अधिकतम उपलब्ध मेमोरी प्राप्त या सेट करता है। निर्दिष्ट मान मेगाबाइट्स काउंट है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | सेट करता है`Cache` डिफ़ॉल्ट के लिए सेटिंग. |

### उदाहरण

यह उदाहरण Aspose.PSD.Cache के उपयोग को प्रदर्शित करता है

```csharp
[C#]

// डिफ़ॉल्ट रूप से कैश फ़ोल्डर उपयोगकर्ता की स्थानीय अस्थायी निर्देशिका पर सेट होता है।
// आप निम्न की तरह डिफ़ॉल्ट के अलावा अन्य कैश फ़ोल्डर भी निर्दिष्ट कर सकते हैं:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// ऑटो मोड लचीला और कुशल है
Cache.CacheType = CacheType.Auto;

// डिफ़ॉल्ट मान 0 है, जिसका अर्थ है कि कोई ऊपरी सीमा नहीं है
Cache.MaxDiskSpaceForCache = 1073741824; // 1 गीगाबाइट
Cache.MaxMemoryForCache = 1073741824; // 1 गीगाबाइट

// निम्नलिखित संपत्ति को बदलने की अनुशंसा नहीं की जाती है क्योंकि यह प्रदर्शन को बहुत प्रभावित कर सकती है
Cache.ExactReallocateOnly = false;

// किसी भी समय आप जांच सकते हैं कि मेमोरी या डिस्क के लिए वर्तमान में कितने बाइट आवंटित किए गए हैं 
// कैश निम्नलिखित गुणों की जांच करके
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// नीचे के रूप में कुछ इमेज प्रोसेसिंग करें
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // ऊपर दिए गए कोड को निष्पादित करने के बाद 40000 बाइट्स इन-मेमोरी आवंटित की जाएगी।
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// आवंटन गुणों का उपयोग यह जांचने के लिए किया जा सकता है कि सभी Aspose.PSD ऑब्जेक्ट्स ठीक से निपटाए गए थे या नहीं।
// यदि आप किसी वस्तु पर निपटान करना भूल गए हैं तो कैश मान 0 से भिन्न होगा।            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD](../../aspose.psd/)
* सभा [Aspose.PSD](../../)



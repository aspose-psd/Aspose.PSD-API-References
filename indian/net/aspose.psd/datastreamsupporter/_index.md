---
title: "क्लास DataStreamSupporter"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.DataStreamSupporter क्लास। डेटा स्ट्रीम कंटेनर"
type: docs
weight: 750
url: /hi/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

डेटा स्ट्रीम कंटेनर।

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ना आवश्यक नहीं है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित [`DataStreamContainer`](./datastreamcontainer/) से कोई अतिरिक्त डेटा लोडिंग नहीं की जाएगी। |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | वर्तमान इंस्टेंस को डिस्पोज़ करता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | ऑब्जेक्ट का डेटा वर्तमान `DataStreamSupporter` में सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम में सहेजता है। |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |

### देखें भी

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



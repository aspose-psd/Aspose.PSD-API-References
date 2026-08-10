---
title: "क्लास LinkResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource क्लास। LinkResource क्लास को परिभाषित करता है जो PSD फ़ॉर्मेट छवि में लिंक्ड या एम्बेडेड फ़ाइलों के बारे में जानकारी रखता है। लिंक रिसोर्स में कई LinkDataSource इंस्टेंस हो सकते हैं जिन्हें किसी भी व्युत्पन्न क्लास में इंडेक्सर द्वारा एक्सेस किया जा सकता है।"
type: docs
weight: 3010
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

LinkResource क्लास को परिभाषित करता है जो PSD फ़ॉर्मेट छवि में लिंक्ड या एम्बेडेड फ़ाइलों के बारे में जानकारी रखता है। लिंक रिसोर्स में कई [`LinkDataSource`](../linkdatasource/) इंस्टेंस हो सकते हैं जिन्हें किसी भी व्युत्पन्न क्लास में इंडेकर्स द्वारा एक्सेस किया जा सकता है।

```csharp
public abstract class LinkResource : LayerResource
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | इंडेक्सर द्वारा एक्सेस किए जा सकने वाले लिंक डेटा स्रोतों की संख्या प्राप्त करता है। |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | यह दर्शाने वाला मान प्राप्त करता है कि यह लिंक रिसोर्स इंस्टेंस खाली है या नहीं। |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | निर्दिष्ट इंडेक्स पर स्थित [`LinkDataSource`](../linkdatasource/) प्राप्त करता है, जो लिंक डेटा स्रोत का अद्वितीय पहचानकर्ता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD ग्लोबल लिंक रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | रिसोर्स ब्लॉक डेटा को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

### देखें भी

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



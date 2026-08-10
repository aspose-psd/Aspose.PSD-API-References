---
title: "क्लास Lnk2Resource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource क्लास। वह क्लास परिभाषित करता है जो PSD फ़ॉर्मेट छवि में एम्बेडेड फ़ाइलों की जानकारी रखती है। लिंक रिसोर्स में कई LiFdDataSource इंस्टेंस हो सकते हैं जिन्हें इंडेक्सर द्वारा एक्सेस किया जा सकता है।"
type: docs
weight: 3030
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

वह क्लास परिभाषित करता है जो PSD फ़ॉर्मेट छवि में एम्बेडेड फ़ाइलों की जानकारी रखती है। लिंक रिसोर्स में कई [`LiFdDataSource`](../lifddatasource/) इंस्टेंस हो सकते हैं जिन्हें इंडेक्सर द्वारा एक्सेस किया जा सकता है।

```csharp
public class Lnk2Resource : LinkResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | `Lnk2Resource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | इंडेक्सर द्वारा एक्सेस किए जा सकने वाले लिंक डेटा स्रोतों की संख्या प्राप्त करता है। |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | यह दर्शाने वाला मान प्राप्त करता है कि यह लिंक रिसोर्स इंस्टेंस खाली है या नहीं। |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | निर्दिष्ट इंडेक्स पर स्थित [`LiFdDataSource`](../lifddatasource/) प्राप्त करता है। (2 इंडेक्सर) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | PSD ग्लोबल लिंक रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | रिसोर्स ब्लॉक डेटा को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

### देखें भी

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



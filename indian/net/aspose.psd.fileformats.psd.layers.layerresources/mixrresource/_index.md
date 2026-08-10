---
title: "क्लास MixrResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource क्लास। क्लास MixrResource। Channel Mixer Adjustment लेयर का संसाधन।"
type: docs
weight: 3160
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

क्लास MixrResource। चैनल मिक्सर एडजस्टमेंट लेयर का रिसोर्स

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | `MixrResource` क्लास का एक नया उदाहरण प्रारंभ करता है। PSD फ़ॉर्मेट विनिर्देश में निम्न विवरण शामिल है: 2 संस्करण (= 1) 2 मोनोक्रोम 20 RGB या CMYK रंग प्लस मिक्सर सेटिंग्स के लिए स्थिरांक। 4 * 2 बाइट्स रंग के साथ 2 बाइट्स स्थिरांक। |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | `MixrResource` क्लास का एक नया उदाहरण प्रारंभ करता है। PSD फ़ॉर्मेट विनिर्देश में निम्न विवरण शामिल है: 2 संस्करण (= 1) 2 मोनोक्रोम 20 RGB या CMYK रंग प्लस मिक्सर सेटिंग्स के लिए स्थिरांक। 4 * 2 बाइट्स रंग के साथ 2 बाइट्स स्थिरांक। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | इस `MixrResource` मोनोक्रोम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | संस्करण को प्राप्त करता है या सेट करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | चैनल जानकारी का कच्चा डेटा प्राप्त करता है |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | चैनल जानकारी सेट करता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

### देखें भी

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



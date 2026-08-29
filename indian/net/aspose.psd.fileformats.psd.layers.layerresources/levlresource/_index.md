---
title: "क्लास LevlResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource क्लास। क्लास LevlResource। एक्सपोज़र एडजस्टमेंट लेयर का रिसोर्स।"
type: docs
weight: 2950
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

क्लास LevlResource. एक्सपोज़र एडजस्टमेंट लेयर का रिसोर्स।

```csharp
public class LevlResource : AdjustmentLayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | `LevlResource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LevlResource](levlresource/#constructor_1)(byte[]) | `LevlResource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। ग्रे स्केल, डुओटोन, RGB, CMYK, लैब कलर मोड्स में समर्थित। 2 बाइट्स - संस्करण (=2) 29 * 10 बाइट्स - 5 शॉर्ट इंटीजर वाले लेवल रिकॉर्ड सेट 4 बाइट्स - Lvls हेडर (इंडेक्स 292 से शुरू) 2 बाइट्स - संस्करण (=3) 2 बाइट्स - कुल लेवल रिकॉर्ड की गिनती 10 * (कुल गिनती - 29) शून्य समाप्ति वाले Lvls रिसोर्स को भी फोल्ड किया जाना चाहिए। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | वर्ज़न प्राप्त करता है। डिफ़ॉल्ट 2 है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | चैनल प्राप्त करता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

### देखें भी

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



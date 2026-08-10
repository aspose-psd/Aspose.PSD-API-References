---
title: "क्लास PhflResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource क्लास। क्लास PhflResource। एक्सपोजर एडजस्टमेंट लेयर 2 का रिसोर्स, संस्करण 3 या 2। प्रत्येक XYZ रंग के लिए 12‑4 बाइट्स, केवल संस्करण 3 में 10‑2 बाइट्स रंग स्पेस के बाद 4‑2 बाइट्स रंग घटक, केवल संस्करण 2 में। 4 घनत्व, 1 ल्यूमिनोसिटी संरक्षित करता है।"
type: docs
weight: 3240
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

क्लास PhflResource। एक्सपोज़र एडजस्टमेंट लेयर 2 का रिसोर्स संस्करण ( = 3 ) या ( = 2 ) 12 4 बाइट्स प्रत्येक XYZ रंग के लिए (केवल संस्करण 3 में) 10 2 बाइट्स कलर स्पेस जिसके बाद 4 * 2 बाइट्स कलर कंपोनेंट (केवल संस्करण 2 में) 4 डेंसिटी 1 ल्यूमिनोसिटी बनाए रखें

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | घनत्व को प्राप्त करता है या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [preserve luminosity]। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | संस्करण को प्राप्त करता है। डिफ़ॉल्ट 2 या 3 है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | RGB का रंग प्राप्त करता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | RGB रंग सेट करता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

### देखें भी

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



---
title: "क्लास PhflResourceVersion2"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 क्लास। क्लास PhflResource। एक्सपोज़र एडजस्टमेंट लेयर 2 का रिसोर्स, संस्करण 3 या 2। प्रत्येक XYZ रंग के लिए 12‑4 बाइट्स, संस्करण 3 में केवल रंग, 10‑2 बाइट्स रंग स्पेस के बाद 4‑2 बाइट्स रंग घटक, संस्करण 2 में। 4 डेंसिटी 1, ल्यूमिनोसिटी को संरक्षित करता है।"
type: docs
weight: 3250
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

क्लास PhflResource। एक्सपोज़र एडजस्टमेंट लेयर 2 का रिसोर्स संस्करण ( = 3 ) या ( = 2 ) 12 4 बाइट्स प्रत्येक XYZ रंग के लिए (केवल संस्करण 3 में) 10 2 बाइट्स कलर स्पेस जिसके बाद 4 * 2 बाइट्स कलर कंपोनेंट (केवल संस्करण 2 में) 4 डेंसिटी 1 ल्यूमिनोसिटी बनाए रखें

```csharp
public class PhflResourceVersion2 : PhflResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | `PhflResourceVersion2` क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | `PhflResourceVersion2` क्लास का नया इंस्टेंस प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | रंग स्थान को प्राप्त करता है। |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | रंग के A घटक को प्राप्त करता है या सेट करता है |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | B घटक को प्राप्त करता है या सेट करता है |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | रंग के L घटक को प्राप्त करता है या सेट करता है। |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | घनत्व को प्राप्त करता है या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [preserve luminosity]। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | संस्करण को प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | रंग को प्राप्त करता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | RGB रंग सेट करता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

### देखें भी

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



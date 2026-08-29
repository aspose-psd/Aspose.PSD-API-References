---
title: "क्लास PhflResourceVersion3"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3 क्लास। क्लास PhflResource। एक्सपोज़र एडजस्टमेंट लेयर 2 का रिसोर्स संस्करण 3 या 2। प्रत्येक XYZ रंग के लिए 12 4 बाइट्स। केवल संस्करण 3 में 10 2 बाइट्स कलर स्पेस के बाद 4 2 बाइट्स कलर कंपोनेंट। केवल संस्करण 2 में 4 डेंसिटी 1 प्रिज़र्व ल्यूमिनोसिटी।"
type: docs
weight: 3260
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

क्लास PhflResource। एक्सपोज़र एडजस्टमेंट लेयर 2 का रिसोर्स संस्करण ( = 3 ) या ( = 2 ) 12 4 बाइट्स प्रत्येक XYZ रंग के लिए (केवल संस्करण 3 में) 10 2 बाइट्स कलर स्पेस जिसके बाद 4 * 2 बाइट्स कलर कंपोनेंट (केवल संस्करण 2 में) 4 डेंसिटी 1 ल्यूमिनोसिटी बनाए रखें

```csharp
public class PhflResourceVersion3 : PhflResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | `PhflResourceVersion3` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | `PhflResourceVersion3` क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | रंग स्थान को प्राप्त करता है। |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | X रंग को प्राप्त करता है या सेट करता है। |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | Y रंग को प्राप्त करता है या सेट करता है। |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | Z रंग को प्राप्त करता है या सेट करता है। |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | घनत्व को प्राप्त करता है या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [preserve luminosity]। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | संस्करण को प्राप्त करता है। डिफ़ॉल्ट 2 या 3 है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | रंग को प्राप्त करता है। |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | RGB रंग सेट करता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

### देखें भी

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



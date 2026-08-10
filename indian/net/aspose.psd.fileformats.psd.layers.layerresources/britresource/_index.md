---
title: "क्लास BritResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource क्लास। क्लास BritResource। ब्राइटनेस/कॉन्ट्रास्ट एडजस्टमेंट लेयर का रिसोर्स।"
type: docs
weight: 2600
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

क्लास BritResource। Brightness/Contrast Adjustment Layer का रिसोर्स।

```csharp
public class BritResource : AdjustmentLayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BritResource](britresource/#constructor)() | `BritResource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BritResource](britresource/#constructor_1)(byte[]) | `BritResource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। PSD फ़ॉर्मेट स्पेसिफिकेशन में निम्न विवरण शामिल है: 2 ब्राइटनेस 2 कॉन्ट्रास्ट 2 ब्राइटनेस और कॉन्ट्रास्ट के लिए औसत मान 1 केवल लैब कलर। यह आधुनिक PSD (CS5 और ऊपर) में उपयोग नहीं होता जहाँ CgEd है। CgEd जानकारी प्रॉपर्टीज़ स्टोर करता है। |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | `BritResource` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | ब्राइटनेस को प्राप्त करता है या सेट करता है। |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | कॉन्ट्रास्ट को प्राप्त करता है या सेट करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [lab color] है या नहीं। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | ब्राइटनेस और कॉन्ट्रास्ट के लिए औसत मान को प्राप्त करता है या सेट करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | टाइप टूल जानकारी कुंजी। |

### देखें भी

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)



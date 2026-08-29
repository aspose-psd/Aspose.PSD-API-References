---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "GifOptions प्रॉपर्टी। GIF पिक्सेल पहलू अनुपात प्राप्त करता है या सेट करता है"
type: docs
weight: 90
url: /hi/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

GIF पिक्सेल पहलू अनुपात को प्राप्त करता है या सेट करता है।

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

GIF पिक्सेल पहलू अनुपात।

## टिप्पणियाँ

Pixel Aspect Ratio - मूल छवि में पिक्सेल के पहलू अनुपात का अनुमान लगाने के लिए उपयोग किया जाने वाला कारक। यदि फ़ील्ड का मान 0 नहीं है, तो यह अनुमान सूत्र के आधार पर गणना किया जाता है: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64। Pixel Aspect Ratio को पिक्सेल की चौड़ाई को उसकी ऊँचाई से विभाजित करने के रूप में परिभाषित किया गया है। इस फ़ील्ड में मान की सीमा 4:1 के सबसे चौड़े पिक्सेल से लेकर 1:4 के सबसे ऊँचे पिक्सेल तक, 1/64वें हिस्से के वृद्धि में निर्दिष्ट करने की अनुमति देती है। मान : 0 - कोई पहलू अनुपात जानकारी नहीं दी गई है। 1..255 - गणना में उपयोग किया गया मान।

### देखें भी

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)



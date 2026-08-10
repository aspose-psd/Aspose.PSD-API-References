---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IColorPalette प्रॉपर्टी। यह दर्शाने वाला मान प्राप्त करता है कि कॉम्पैक्ट पैलेट उपयोग किया गया है या नहीं"
type: docs
weight: 40
url: /hi/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

एक मान प्राप्त करता है जो दर्शाता है कि कॉम्पैक्ट पैलेट उपयोग किया गया है या नहीं।

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` यदि कॉम्पैक्ट पैलेट उपयोग किया गया है; अन्यथा, `false`।

## टिप्पणियाँ

कॉम्पैक्ट पैलेट का अर्थ है कि छवि केवल निर्दिष्ट पैलेट एंट्रीज़ को ही शामिल करेगी यदि संभव हो, या दूसरे शब्दों में छवि अधिक कॉम्पैक्ट होगी और कम स्थान घेरेंगी; अन्यथा 2^BitsPerPixel एंट्रीज़ होंगी और छवि सभी संभावित पैलेट एंट्रीज़ के लिए अधिक स्थान आरक्षित करेगी। इस मान को `true` पर सेट करना और पैलेट एंट्रीज़ को बदलना प्रदर्शन में गिरावट का कारण बन सकता है क्योंकि डेटा मूवमेंट हो सकता है, इसलिए इसे सावधानीपूर्वक उपयोग करें।

### देखें भी

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)



---
title: "Enum CompressionMethod"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod एन्नुम। इमेज डेटा के लिए उपयोग किए जाने वाले संपीड़न विधि को परिभाषित करता है।"
type: docs
weight: 1630
url: /hi/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

इमेज डेटा के लिए उपयोग की जाने वाली संपीड़न विधि को परिभाषित करता है।

```csharp
public enum CompressionMethod : short
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Raw | `0` | कोई संपीड़न नहीं। इमेज डेटा को RGBA प्लेनर क्रम में कच्चे बाइट्स के रूप में संग्रहीत किया जाता है। इसका मतलब है कि पहले सभी R डेटा लिखा जाता है, फिर सभी G, फिर सभी B और अंत में सभी A डेटा लिखा जाता है। |
| RLE | `1` | RLE संपीड़ित इमेज डेटा सभी स्कैन लाइनों (पंक्तियाँ * चैनल) के बाइट काउंट से शुरू होता है, जहाँ प्रत्येक काउंट दो-बाइट मान के रूप में संग्रहीत होता है। इसके बाद RLE संपीड़ित डेटा आता है, जहाँ प्रत्येक स्कैन लाइन अलग‑अलग संपीड़ित की जाती है। RLE संपीड़न वही संपीड़न एल्गोरिद्म है जो Macintosh ROM रूटीन PackBits और TIFF मानक द्वारा उपयोग किया जाता है। |
| ZipWithoutPrediction | `2` | प्रेडिक्शन के बिना ZIP। |
| ZipWithPrediction | `3` | प्रेडिक्शन के साथ ZIP। |

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)



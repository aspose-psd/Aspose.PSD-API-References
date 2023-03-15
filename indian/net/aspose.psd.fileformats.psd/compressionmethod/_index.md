---
title: Enum CompressionMethod
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.CompressionMethod एनुम. छव डेट के लए उपयग क जने वल संपड़न वध क परभषत करत है
type: docs
weight: 1620
url: /hi/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

छवि डेटा के लिए उपयोग की जाने वाली संपीड़न विधि को परिभाषित करता है।

```csharp
public enum CompressionMethod : short
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Raw | `0` | कोई संपीड़न नहीं। आरजीबीए प्लानर ऑर्डर में कच्चे बाइट्स के रूप में संग्रहीत छवि डेटा। इसका मतलब है कि पहले सभी आर डेटा लिखे गए हैं, फिर सभी जी लिखे गए हैं, फिर सभी बी और अंत में सभी ए डेटा लिखे गए हैं। |
| RLE | `1` | RLE संकुचित छवि डेटा सभी स्कैन लाइनों (पंक्तियों * चैनलों) के लिए बाइट की संख्या के साथ शुरू होता है, प्रत्येक गणना को दो-बाइट मान के रूप में संग्रहीत किया जाता है। RLE कंप्रेस्ड डेटा अनुसरण करता है, प्रत्येक स्कैन लाइन के साथ अलग से कम्प्रेस किया जाता है। |
| ZipWithoutPrediction | `2` | ज़िप बिना भविष्यवाणी के। |
| ZipWithPrediction | `3` | भविष्यवाणी के साथ ज़िप। |

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* सभा [Aspose.PSD](../../)



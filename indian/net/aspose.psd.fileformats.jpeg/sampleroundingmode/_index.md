---
title: Enum SampleRoundingMode
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode एनुम. उस तरके क परभषत करत है जसमें एनबट मन क 8बट मन में परवर्तत कय जत है
type: docs
weight: 1530
url: /hi/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

उस तरीके को परिभाषित करता है जिसमें एन-बिट मान को 8-बिट मान में परिवर्तित किया जाता है।

```csharp
public enum SampleRoundingMode
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Extrapolate | `0` | एक 8-बिट मान को n बिट्स में फ़िट करने के लिए एक्सट्रपलेशन करें, जहाँ 1 &lt;n &lt; 8. सभी संभव 8-बिट मानों की संख्या 1 &lt;&lt; 8 = 256 है, 0 से 255 तक। सभी संभव की संख्या n-बिट मान 1 &lt;&lt; n है, 0 से (1 &lt;&lt; n) - 1. कुछ 8-बिट मान V8 के अनुरूप सबसे उचित n-बिट मान V8 Vn = V8 &gt;&gt; (8 - के बराबर है - एन)। |
| Truncate | `1` | 8-बिट मान को n बिट्स में फिट करने के लिए छोटा करें, जहां 1 &lt;n &lt; 8. सभी संभावित n-बिट मानों की संख्या 1 &lt;&lt; n है, 0 से (1 &lt;&lt; n) - 1. कुछ 8-बिट मान V8 के संगत सबसे उचित n-बिट मान Vn, Vn = V8 &amp; ((1 &lt;&lt; n) - 1). के बराबर है |

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* सभा [Aspose.PSD](../../)



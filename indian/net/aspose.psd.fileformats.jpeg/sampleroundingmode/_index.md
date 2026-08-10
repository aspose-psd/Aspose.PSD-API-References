---
title: "एनम SampleRoundingMode"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode एनम। यह निर्धारित करता है कि n‑बिट मान को 8‑बिट मान में कैसे परिवर्तित किया जाता है।"
type: docs
weight: 1540
url: /hi/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

परिभाषित करता है कि n-बिट मान को 8-बिट मान में कैसे परिवर्तित किया जाता है।

```csharp
public enum SampleRoundingMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Extrapolate | `0` | एक 8‑बिट मान को n बिट्स में फिट करने के लिए एक्सट्रापोलेट करें, जहाँ 1 &lt; n &lt; 8। सभी संभावित 8‑बिट मानों की संख्या 1 &lt;&lt; 8 = 256 है, 0 से 255 तक। सभी संभावित n‑बिट मानों की संख्या 1 &lt;&lt; n है, 0 से (1 &lt;&lt; n) - 1 तक। सबसे उचित n‑बिट मान Vn, जो किसी 8‑बिट मान V8 से संबंधित है, Vn = V8 &gt;&gt; (8 - n) के बराबर है। |
| Truncate | `1` | एक 8‑बिट मान को n बिट्स में फिट करने के लिए ट्रंकेट करें, जहाँ 1 &lt; n &lt; 8। सभी संभावित n‑बिट मानों की संख्या 1 &lt;&lt; n है, 0 से (1 &lt;&lt; n) - 1 तक। सबसे उचित n‑बिट मान Vn, जो किसी 8‑बिट मान V8 से संबंधित है, Vn = V8 &amp; ((1 &lt;&lt; n) - 1) के बराबर है। |

### देखें भी

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)



---
title: "SampleRoundingMode एन्उमरेशन"
type: docs
weight: 70
url: /hi/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

एक n-बिट मान को 8-बिट मान में परिवर्तित करने का तरीका परिभाषित करता है।

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **सदस्य नाम** | **विवरण** |
| :- | :- |
| EXTRAPOLATE | 8-बिट मान को n बिट्स में फिट करने के लिए एक्सट्रापोलेट करें, जहाँ 1 < n < 8.<br/> सभी संभावित 8-बिट मानों की संख्या 1 << 8 = 256 है, 0 से 255 तक.<br/> सभी संभावित n-बिट मानों की संख्या 1 << n है, 0 से (1 << n) - 1 तक.<br/> किसी 8-बिट मान V8 के अनुरूप सबसे उचित n-बिट मान Vn बराबर है Vn = V8 >> (8 - n). |
| TRUNCATE | 8-बिट मान को n बिट्स में फिट करने के लिए ट्रंकेट करें, जहाँ 1 < n < 8.<br/> सभी संभावित n-बिट मानों की संख्या 1 << n है, 0 से (1 << n) - 1 तक.<br/> किसी 8-बिट मान V8 के अनुरूप सबसे उचित n-बिट मान Vn बराबर है Vn = V8 & ((1 << n) - 1). |

---
title: "CompressionMethod एन्यूमरेशन"
type: docs
weight: 2410
url: /hi/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

छवि डेटा के लिए उपयोग की जाने वाली संपीड़न विधि को परिभाषित करता है।

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **सदस्य नाम** | **विवरण** |
| :- | :- |
| RAW | कोई संपीड़न नहीं। इमेज डेटा RGBA प्लेनर क्रम में कच्चे बाइट्स के रूप में संग्रहीत होता है।<br/>            इसका मतलब है कि पहले सभी R डेटा लिखा जाता है, फिर सभी G, फिर सभी B और अंत में सभी A डेटा लिखा जाता है। |
| RLE | RLE संपीड़ित इमेज डेटा सभी स्कैन लाइनों (पंक्तियों * चैनल) के बाइट काउंट से शुरू होता है, जहाँ प्रत्येक<br/>            काउंट दो-बाइट मान के रूप में संग्रहीत होता है। इसके बाद RLE संपीड़ित डेटा आता है, जहाँ प्रत्येक स्कैन लाइन अलग-अलग संपीड़ित होती है।<br/>            RLE संपीड़न वही संपीड़न एल्गोरिद्म है जो Macintosh ROM रूटीन PackBits और TIFF मानक द्वारा उपयोग किया जाता है। |
| ZIP_WITHOUT_PREDICTION | पूर्वानुमान के बिना ZIP। |
| ZIP_WITH_PREDICTION | पूर्वानुमान के साथ ZIP। |

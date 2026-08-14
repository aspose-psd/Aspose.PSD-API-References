---
title: "ThumbnailResource क्लास"
type: docs
weight: 250
url: /hi/python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | ThumbnailResource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady की संसाधन हस्ताक्षर। |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | सामान्य Photoshop संसाधन हस्ताक्षर। |
| bits_pixel | short | r/w | बिट्स पिक्सेल प्राप्त करता है या सेट करता है। |
| data_size | int | r | संसाधन डेटा आकार बाइट्स में प्राप्त करता है। |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | थंबनेल डेटा फ़ॉर्मेट प्राप्त करता है या सेट करता है। |
| height | int | r/w | थंबनेल की ऊँचाई पिक्सेल में प्राप्त करता है या सेट करता है। |
| id | short | r/w | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त करता है या सेट करता है। |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | JPEG विकल्प प्राप्त करता है या सेट करता है। केवल तब उपयुक्त जब थंबनेल रिसोर्स को JPEG फ़ाइल फ़ॉर्मेट में सहेजा जाता है। जब RAW फ़ॉर्मेट परिभाषित होता है तो यह विकल्प कोई प्रभाव नहीं डालता। |
| minimal_version | int | r | न्यूनतम आवश्यक psd संस्करण प्राप्त करता है। |
| name | string | r/w | संसाधन नाम प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट 0 से बना होता है)। |
| planes_count | short | r/w | planes count प्राप्त करता है या सेट करता है। |
| signature | int | r | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| आकार | int | r | डेटा सहित संसाधन ब्लॉक का आकार बाइट्स में प्राप्त करता है। |
| size_after_compression | int | r | संकुचन के बाद आकार प्राप्त करता है या सेट करता है। स्थिरता जांच के लिए उपयोग किया जाता है। |
| thumbnail_argb_32_data | int | r/w | 32-बिट ARGB थंबनेल डेटा प्राप्त करता है या सेट करता है। |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | थंबनेल डेटा प्राप्त करता है या सेट करता है। |
| total_size | int | r | कुल डेटा आकार प्राप्त करता है। |
| width | int | r/w | पिक्सेल में थंबनेल की चौड़ाई प्राप्त करता है या सेट करता है। |
| width_bytes | int | r | बाइट्स में पंक्ति की चौड़ाई प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream)](#save_stream_1) | संसाधन ब्लॉक डेटा को सहेजता है। |
| validate_values() | संसाधन मानों को मान्य करता है। |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

ThumbnailResource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

संसाधन ब्लॉक डेटा को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |


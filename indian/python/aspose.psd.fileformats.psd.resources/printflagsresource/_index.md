---
title: "PrintFlagsResource Class"
type: docs
weight: 200
url: /hi/python-net/aspose.psd.fileformats.psd.resources/printflagsresource/
---

**Summary:** Print flags resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.PrintFlagsResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PrintFlagsResource()](#PrintFlagsResource__1) | PrintFlagsResource class की नई इंस्टेंस को प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady की संसाधन हस्ताक्षर। |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | सामान्य Photoshop संसाधन हस्ताक्षर। |
| bleed_scale | short | r/w | bleed scale को प्राप्त करता है या सेट करता है। |
| bleed_width | int | r/w | bleed की चौड़ाई को प्राप्त करता है या सेट करता है। |
| center_crop_mark | byte | r/w | center crop mark को प्राप्त करता है या सेट करता है। |
| data_size | int | r | संसाधन डेटा आकार बाइट्स में प्राप्त करता है। |
| id | short | r/w | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त करता है या सेट करता है। |
| minimal_version | int | r | आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| name | string | r/w | संसाधन नाम प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट 0 से बना होता है)। |
| signature | int | r | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| आकार | int | r | डेटा सहित संसाधन ब्लॉक का आकार बाइट्स में प्राप्त करता है। |
| version | short | r/w | संस्करण प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream)](#save_stream_1) | निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है। |
| validate_values() | संसाधन मानों को मान्य करता है। |


### Constructor: PrintFlagsResource() {#PrintFlagsResource__1}


```
 PrintFlagsResource() 
```

PrintFlagsResource class की नई इंस्टेंस को प्रारंभ करता है

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | संसाधन ब्लॉक को सहेजने के लिए स्ट्रीम। |


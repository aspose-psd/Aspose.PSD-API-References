---
title: "ResolutionInfoResource क्लास"
type: docs
weight: 230
url: /hi/python-net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Summary:** The resolution info resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ResolutionInfoResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ResolutionInfoResource()](#ResolutionInfoResource__1) | ResolutionInfoResource क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady की संसाधन हस्ताक्षर। |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | सामान्य Photoshop संसाधन हस्ताक्षर। |
| data_size | int | r | संसाधन डेटा आकार बाइट्स में प्राप्त करता है। |
| h_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | क्षैतिज DPI। |
| h_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | क्षैतिज रिज़ॉल्यूशन के लिए डिस्प्ले इकाइयाँ। यह केवल <br/> उपयोगकर्ता इंटरफ़ेस को प्रभावित करता है; रिज़ॉल्यूशन अभी भी PSD फ़ाइल में <br/> पिक्सेल/इंच के रूप में संग्रहीत रहता है। |
| height_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | ऊँचाई डिस्प्ले इकाई को प्राप्त करता है या सेट करता है। |
| id | short | r/w | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त करता है या सेट करता है। |
| minimal_version | int | r | आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| name | string | r/w | संसाधन नाम प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट 0 से बना होता है)। |
| signature | int | r | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| आकार | int | r | डेटा सहित संसाधन ब्लॉक का आकार बाइट्स में प्राप्त करता है। |
| v_dpi | [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal) | r/w | ऊर्ध्वाधर DPI। |
| v_res_display_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit/) | r/w | ऊर्ध्वाधर रिज़ॉल्यूशन के लिए डिस्प्ले इकाइयाँ। |
| width_display_unit | [PhysicalUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/) | r/w | चौड़ाई डिस्प्ले इकाई को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream)](#save_stream_1) | निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है। |
| validate_values() | संसाधन मानों को मान्य करता है। |


### Constructor: ResolutionInfoResource() {#ResolutionInfoResource__1}


```
 ResolutionInfoResource() 
```

ResolutionInfoResource क्लास का नया उदाहरण प्रारंभ करता है

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | संसाधन ब्लॉक को सहेजने के लिए स्ट्रीम। |


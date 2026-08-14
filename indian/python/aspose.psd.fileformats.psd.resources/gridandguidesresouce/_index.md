---
title: "GridAndGuidesResouce क्लास"
type: docs
weight: 110
url: /hi/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | GridAndGuidesResouce क्लास का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady की संसाधन हस्ताक्षर। |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | सामान्य Photoshop संसाधन हस्ताक्षर। |
| data_size | int | r | संसाधन डेटा आकार बाइट्स में प्राप्त करता है। |
| grid_cycle_x | int | r/w | क्षैतिज ग्रिड चक्र प्राप्त करता है या सेट करता है। डिफ़ॉल्ट 576 है। |
| grid_cycle_y | int | r/w | ऊर्ध्वाधर ग्रिड चक्र प्राप्त करता है या सेट करता है। डिफ़ॉल्ट 576 है। |
| guide_count | int | r | गाइड संसाधन ब्लॉक की गिनती प्राप्त करता है। |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | गाइड्स प्राप्त करता है या सेट करता है। |
| header_version | int | r/w | हेडर संस्करण को प्राप्त करता है या सेट करता है। यह मान हमेशा 1 होना चाहिए। |
| id | short | r/w | संसाधन के लिए अद्वितीय पहचानकर्ता प्राप्त करता है या सेट करता है। |
| minimal_version | int | r | न्यूनतम आवश्यक psd संस्करण प्राप्त करता है। |
| name | string | r/w | संसाधन नाम प्राप्त करता है या सेट करता है। पास्कल स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट 0 से बना होता है)। |
| signature | int | r | संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए। |
| आकार | int | r | डेटा सहित संसाधन ब्लॉक का आकार बाइट्स में प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream)](#save_stream_1) | निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है। |
| validate_values() | संसाधन मानों को मान्य करता है। |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

GridAndGuidesResouce क्लास का नया उदाहरण प्रारंभ करता है।

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

निर्दिष्ट स्ट्रीम में संसाधन ब्लॉक को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | संसाधन ब्लॉक को सहेजने के लिए स्ट्रीम। |


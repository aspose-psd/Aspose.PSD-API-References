---
title: "Txt2Resource क्लास"
type: docs
weight: 970
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | नया उदाहरण प्रारंभ करता है Txt2Resource क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| data | byte | r/w | डेटा प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | टेक्स्ट रिकॉर्ड को Resource में जोड़ता है और टेक्स्ट रिकॉर्ड का आईडी लौटाता है। |
| [get_text_data()](#get_text_data__2) | resource डेटा से टेक्स्ट रिकॉर्ड प्राप्त करता है। |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

नया उदाहरण प्रारंभ करता है Txt2Resource क्लास का।

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

टेक्स्ट रिकॉर्ड को Resource में जोड़ता है और टेक्स्ट रिकॉर्ड का आईडी लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | string | रिकॉर्ड टेक्स्ट। |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | सीमाएँ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | resource के लिए टेक्स्ट रिकॉर्ड का आईडी लौटाता है। |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

resource डेटा से टेक्स्ट रिकॉर्ड प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | टेक्स्ट रिकॉर्ड की एरे |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है.

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


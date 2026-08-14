---
title: "CgEdResource क्लास"
type: docs
weight: 130
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | CgEdResource क्लास का एक नया उदाहरण प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| auto | bool | r/w | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) स्वचालित है या नहीं। |
| चमक | int | r/w | ब्राइटनेस को प्राप्त करता है या सेट करता है। |
| कॉन्ट्रास्ट | int | r/w | कॉन्ट्रास्ट को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| lab_color | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [lab color] उपयोग किया गया है या नहीं। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| mean_value_for_brightness_and_contrast | int | r/w | ब्राइटनेस और कॉन्ट्रास्ट के लिए औसत मान को प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| use_legacy | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [use legacy] उपयोग किया गया है या नहीं। |
| version | int | r/w | संस्करण प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

CgEdResource क्लास का एक नया उदाहरण प्रारंभ करता है

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


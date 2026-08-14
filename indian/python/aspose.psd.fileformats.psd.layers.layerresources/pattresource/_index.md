---
title: "PattResource क्लास"
type: docs
weight: 770
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PattResource()](#PattResource__1) | एक नया उदाहरण प्रारंभ करता है [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) क्लास का। |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | एक नया उदाहरण प्रारंभ करता है [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | 8-बिट के लिए 'Patt' प्रकार टूल इन्फो कुंजी। |
| TYPE_TOOL_KEY2 [static] | int | r | 16-बिट के लिए 'Pat2' प्रकार टूल इन्फो कुंजी। |
| TYPE_TOOL_KEY3 [static] | int | r | 32-बिट के लिए 'Pat3' प्रकार टूल इन्फो कुंजी। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | पैटर्न डेटा को प्राप्त करता है या सेट करता है; |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | संसाधन ब्लॉक डेटा को सहेजता है। |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

एक नया उदाहरण प्रारंभ करता है [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) क्लास का।

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

एक नया उदाहरण प्रारंभ करता है [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | int | रिसोर्स प्रकार कुंजी। |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | पैटर्न डेटा। |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

संसाधन ब्लॉक डेटा को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


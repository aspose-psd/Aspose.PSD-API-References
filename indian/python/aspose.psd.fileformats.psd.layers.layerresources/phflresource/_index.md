---
title: "PhflResource क्लास"
type: docs
weight: 790
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| density | int | r/w | घनत्व को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| preserve_luminosity | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [preserve luminosity]। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| version | short | r | संस्करण प्राप्त करता है। डिफ़ॉल्ट 2 या 3 है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | RGB का रंग प्राप्त करता है। |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |
| [set_rgb_color(color)](#set_rgb_color_color_3) | RGB रंग सेट करता है। |


### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

RGB का रंग प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB रंग |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

RGB रंग सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | RGB रंग। |


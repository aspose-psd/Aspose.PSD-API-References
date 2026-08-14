---
title: "PattResourceData क्लास"
type: docs
weight: 780
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | PattResourceData क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| height | short | r | ऊँचाई प्राप्त करता है। |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | इमेज मोड प्राप्त करता है। |
| लंबाई | int | r | पैटर्न की लंबाई प्राप्त करता है। |
| name | string | r/w | नाम प्राप्त करता या सेट करता है। |
| pattern_data | int | r | पैटर्न डेटा प्राप्त करता है। |
| pattern_id | string | r/w | पैटर्न पहचानकर्ता प्राप्त करता है या सेट करता है। |
| version | int | r | संस्करण को प्राप्त करता है। |
| width | short | r | चौड़ाई प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | पैटर्न डेटा सहेजता है। |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | पैटर्न सेट करता है। |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

PattResourceData क्लास का नया उदाहरण प्रारंभ करता है

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

पैटर्न डेटा सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

पैटर्न सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixels | int | पिक्सेल। |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | सीमाएँ। |


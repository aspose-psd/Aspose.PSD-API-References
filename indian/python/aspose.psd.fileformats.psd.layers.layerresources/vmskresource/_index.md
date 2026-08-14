---
title: "VmskResource क्लास"
type: docs
weight: 1100
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---

**Summary:** Class VmskResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VmskResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [VmskResource()](#VmskResource__1) | एक नया उदाहरण प्रारंभ करता है [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) क्लास। |
| [VmskResource(data)](#VmskResource_data_2) | एक नया उदाहरण प्रारंभ करता है [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) क्लास। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| is_disabled | bool | r/w | इस उदाहरण के निष्क्रिय होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| is_inverted | bool | r/w | इस उदाहरण के उल्टा होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| is_not_linked | bool | r/w | इस उदाहरण के न जुड़ा होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | पाथ रिकॉर्ड्स को प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| version | int | r/w | संस्करण प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: VmskResource() {#VmskResource__1}


```
 VmskResource() 
```

एक नया उदाहरण प्रारंभ करता है [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) क्लास।

### Constructor: VmskResource(data) {#VmskResource_data_2}


```
 VmskResource(data) 
```

एक नया उदाहरण प्रारंभ करता है [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | संसाधन डेटा। |

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


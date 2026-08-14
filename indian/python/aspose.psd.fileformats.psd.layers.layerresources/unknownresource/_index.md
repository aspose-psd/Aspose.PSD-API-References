---
title: "UnknownResource क्लास"
type: docs
weight: 1050
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/
---

**Summary:** The unknown resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.UnknownResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [UnknownResource(signature, key)](#UnknownResource_signature_key_1) | एक नया उदाहरण प्रारंभ करता है [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| data | byte | r/w | डेटा प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है. |


### Constructor: UnknownResource(signature, key) {#UnknownResource_signature_key_1}


```
 UnknownResource(signature, key) 
```

एक नया उदाहरण प्रारंभ करता है [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| signature | int | सिग्नेचर। |
| key | int | संसाधन कुंजी। |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है.

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


---
title: "Lr32Resource वर्ग"
type: docs
weight: 620
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/
---

**Summary:** The lr32 resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lr32Resource

**Inheritance:** LrXxResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Lr32Resource()](#Lr32Resource__1) | Lr32Resource वर्ग का एक नया उदाहरण प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| layers | [Layer[]](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | r/w | लेयर्स को प्राप्त करता है या सेट करता है। |
| लंबाई | int | r | छवि के PSD हेडर संस्करण के लिए रिसोर्स लंबाई प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | लेयर रिकॉर्ड को सहेजता है। |


### Constructor: Lr32Resource() {#Lr32Resource__1}


```
 Lr32Resource() 
```

Lr32Resource वर्ग का एक नया उदाहरण प्रारंभ करता है

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

लेयर रिकॉर्ड को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psd_version | int | psd संस्करण। |


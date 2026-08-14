---
title: "CustResource वर्ग"
type: docs
weight: 230
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [CustResource()](#CustResource__1) | नया उदाहरण आरंभ करता है [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) वर्ग का। |
| [CustResource(data)](#CustResource_data_2) | नया उदाहरण आरंभ करता है [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) वर्ग का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| layer_created_date_time | datetime | r/w | लेयर बनाये जाने की तिथि प्राप्त करता है या सेट करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

नया उदाहरण आरंभ करता है [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) वर्ग का।

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

नया उदाहरण आरंभ करता है [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) वर्ग का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | संसाधन का डेटा। |

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


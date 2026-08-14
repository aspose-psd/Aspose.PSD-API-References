---
title: "ShmdResource वर्ग"
type: docs
weight: 890
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---

**Summary:** Class ShmdResource. Metadata settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ShmdResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ShmdResource()](#ShmdResource__1) | नया उदाहरण आरंभ करता है [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) वर्ग का। |
| [ShmdResource(data)](#ShmdResource_data_2) | नया उदाहरण आरंभ करता है [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) वर्ग का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| SUB_RESOURCE_HEADER_LENGTH [स्थैतिक] | int | r | सब रिसोर्स हेडर की लंबाई |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| layer_created_date_time | datetime | r/w | लेयर बनाये जाने का समय प्राप्त करता है या सेट करता है। यदि लेयर बनाये जाने का समय निर्दिष्ट नहीं है तो नया DateTime(0) लौटाता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| sub_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r | shmd रिसोर्स के सब रिसोर्स प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है. |


### Constructor: ShmdResource() {#ShmdResource__1}


```
 ShmdResource() 
```

नया उदाहरण आरंभ करता है [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) वर्ग का।

### Constructor: ShmdResource(data) {#ShmdResource_data_2}


```
 ShmdResource(data) 
```

नया उदाहरण आरंभ करता है [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) वर्ग का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | संसाधन का डेटा। |

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


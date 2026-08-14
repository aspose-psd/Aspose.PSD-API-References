---
title: "LevlResource क्लास"
type: docs
weight: 490
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) क्लास का नया उदाहरण आरंभ करता है। |
| [LevlResource(bytes)](#LevlResource_bytes_2) | [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) क्लास का नया उदाहरण आरंभ करता है।<br/>            GrayScale, Duotone, RGB, CMYK, Lab रंग मोड में समर्थित<br/>            2 बाइट - संस्करण (=2)<br/>            29 * 10 बाइट - 5 शॉर्ट इंटीजर वाले लेवल रिकॉर्ड सेट<br/>            4 बाइट - Lvls हेडर (इंडेक्स 292 से शुरू)<br/>            2 बाइट - संस्करण (=3)<br/>            2 बाइट - कुल लेवल रिकॉर्ड की गिनती<br/>            10 * (कुल गिनती - 29)<br/>            Lvls संसाधन का शून्य समाप्ति चार के लिए भी मोड़ना चाहिए |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| version | short | r | संस्करण प्राप्त करता है। डिफ़ॉल्ट 2 है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | चैनल प्राप्त करता है। |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) क्लास का नया उदाहरण आरंभ करता है।

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

[LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) क्लास का नया उदाहरण आरंभ करता है।<br/>            GrayScale, Duotone, RGB, CMYK, Lab रंग मोड में समर्थित<br/>            2 बाइट - संस्करण (=2)<br/>            29 * 10 बाइट - 5 शॉर्ट इंटीजर वाले लेवल रिकॉर्ड सेट<br/>            4 बाइट - Lvls हेडर (इंडेक्स 292 से शुरू)<br/>            2 बाइट - संस्करण (=3)<br/>            2 बाइट - कुल लेवल रिकॉर्ड की गिनती<br/>            10 * (कुल गिनती - 29)<br/>            Lvls संसाधन का शून्य समाप्ति चार के लिए भी मोड़ना चाहिए

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बाइट्स | byte | बाइट्स। |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

चैनल प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | चैनल का लेवल डेटा |


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


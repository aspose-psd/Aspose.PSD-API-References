---
title: "MixrResource क्लास"
type: docs
weight: 680
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | नए [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।<br/>            PSD फ़ॉर्मेट स्पेसिफिकेशन में निम्नलिखित विवरण शामिल है:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB या CMYK रंग प्लस मिक्सर सेटिंग्स के लिए स्थिरांक। 4 * 2 बाइट्स रंग के साथ 2 बाइट्स स्थिरांक। |
| [MixrResource(data)](#MixrResource_data_2) | नए [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।<br/>            PSD फ़ॉर्मेट स्पेसिफिकेशन में निम्नलिखित विवरण शामिल है:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB या CMYK रंग प्लस मिक्सर सेटिंग्स के लिए स्थिरांक। 4 * 2 बाइट्स रंग के साथ 2 बाइट्स स्थिरांक। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| monochrome | bool | r/w | इस [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) के मोनोक्रोम होने का संकेत देने वाले मान को प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| version | short | r/w | संस्करण प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | चैनल जानकारी के कच्चे डेटा को प्राप्त करता है |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | चैनल जानकारी को सेट करता है। |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

नए [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।<br/>            PSD फ़ॉर्मेट स्पेसिफिकेशन में निम्नलिखित विवरण शामिल है:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB या CMYK रंग प्लस मिक्सर सेटिंग्स के लिए स्थिरांक। 4 * 2 बाइट्स रंग के साथ 2 बाइट्स स्थिरांक।

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

नए [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।<br/>            PSD फ़ॉर्मेट स्पेसिफिकेशन में निम्नलिखित विवरण शामिल है:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB या CMYK रंग प्लस मिक्सर सेटिंग्स के लिए स्थिरांक। 4 * 2 बाइट्स रंग के साथ 2 बाइट्स स्थिरांक।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | संसाधन का डेटा। |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

चैनल जानकारी के कच्चे डेटा को प्राप्त करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | चैनल जानकारी का कच्चा बाइट एरे। |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

चैनल जानकारी को सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |
| value | byte | मान। |


---
title: "CurvResource क्लास"
type: docs
weight: 190
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) क्लास का नया उदाहरण आरंभ करता है। |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) क्लास का नया उदाहरण आरंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| is_data_stored_discretely | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण डेटा को अलग-अलग संग्रहीत करता है या नहीं। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | सक्रिय प्रबंधक को प्राप्त करता है। |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | चैनल डेटा प्राप्त करता है। |
| [get_curve_manager()](#get_curve_manager__3) | कर्व प्रबंधक प्राप्त करता है। |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

[CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बाइट्स | byte | बाइट्स। |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

[CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| max_channel_count | int | अधिकतम चैनल गिनती। |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

सक्रिय प्रबंधक को प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | सक्रिय प्रबंधक |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

चैनल डेटा प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| channel_index | int | चैनल का सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | चैनल डेटा |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

कर्व प्रबंधक प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) या [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


---
title: "ClblResource वर्ग"
type: docs
weight: 160
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | नया उदाहरण आरंभ करता है [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) वर्ग का। |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | नया उदाहरण आरंभ करता है [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) वर्ग का। |
| [ClblResource(data)](#ClblResource_data_3) | नया उदाहरण आरंभ करता है [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) वर्ग का।<br/>            कस्टम या अज्ञात मान के साथ |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| ब्लेंड_क्लिप्ड_एलिमेंट्स | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [कटे हुए तत्वों को मिश्रित किया जाए]। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

नया उदाहरण आरंभ करता है [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) वर्ग का।

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

नया उदाहरण आरंभ करता है [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) वर्ग का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ब्लेंड_क्लिप्ड_एलिमेंट्स | bool | यदि <c>true</c> पर सेट किया गया है तो [कटे हुए तत्वों को मिश्रित किया जाए]। |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

नया उदाहरण आरंभ करता है [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) वर्ग का।<br/>            कस्टम या अज्ञात मान के साथ

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | संसाधन डेटा। |

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


---
title: "PtFlResource क्लास"
type: docs
weight: 860
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | नए उदाहरण को प्रारंभ करता है [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) क्लास। |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | नए उदाहरण को प्रारंभ करता है [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) क्लास। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| align_with_layer | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [align with layer]। |
| कोण | डबल | r/w | कोण प्राप्त करता है या सेट करता है। |
| is_linked_with_layer | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण लेयर के साथ जुड़ा है या नहीं। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| pattern_id | string | r/w | पैटर्न पहचानकर्ता प्राप्त करता है या सेट करता है। |
| pattern_name | string | r/w | पैटर्न का नाम प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| scale | डबल | r/w | scale को प्राप्त करता है या सेट करता है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

नए उदाहरण को प्रारंभ करता है [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) क्लास।

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

नए उदाहरण को प्रारंभ करता है [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) क्लास।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pattern_name | string | पैटर्न का नाम। |
| pattern_id | string | पैटर्न पहचानकर्ता। |

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


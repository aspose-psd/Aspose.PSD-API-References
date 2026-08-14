---
title: "ExpaResource क्लास"
type: docs
weight: 280
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| एक्सपोज़र | float | r/w | एक्सपोज़र को प्राप्त करता है या सेट करता है। |
| gamma_correction | float | r/w | गामा को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| offset | float | r/w | ऑफ़सेट को प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| version | short | r | संस्करण प्राप्त करता है। डिफ़ॉल्ट 1 है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

[ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

[ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| बाइट्स | byte | बाइट्स। |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

[ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| एक्सपोज़र | float | एक्सपोज़र। |
| offset | float | ऑफ़सेट। |
| गामा | float | गामा। |

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


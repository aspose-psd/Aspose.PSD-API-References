---
title: "LclrResource क्लास"
type: docs
weight: 470
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LclrResource(color)](#LclrResource_color_2) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LclrResource(data)](#LclrResource_data_3) | [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | लेयर के रंग को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | रंग। |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

[LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | संसाधन डेटा। |

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


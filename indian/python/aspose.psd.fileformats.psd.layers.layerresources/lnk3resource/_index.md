---
title: "Lnk3Resource क्लास"
type: docs
weight: 580
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---

**Summary:** Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk3Resource

**Inheritance:** Lnk2Resource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Lnk3Resource()](#Lnk3Resource__1) | एक नया उदाहरण प्रारंभ करता है [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| data_source_count | int | r | इंडेक्सर द्वारा एक्सेस किए जा सकने वाले लिंक डेटा स्रोतों की गिनती प्राप्त करता है। |
| is_empty | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह लिंक रिसोर्स इंस्टेंस खाली है या नहीं। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | बाइट्स में PSD ग्लोबल लिंक रिसोर्स की लंबाई प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | संसाधन ब्लॉक डेटा को सहेजता है। |


### Constructor: Lnk3Resource() {#Lnk3Resource__1}


```
 Lnk3Resource() 
```

एक नया उदाहरण प्रारंभ करता है [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) क्लास का।

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

संसाधन ब्लॉक डेटा को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


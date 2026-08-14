---
title: "LspfResource वर्ग"
type: docs
weight: 640
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | एक नया उदाहरण प्रारंभ करता है [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) वर्ग का। |
| [LspfResource(data)](#LspfResource_data_2) | एक नया उदाहरण प्रारंभ करता है [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) वर्ग का।<br/>            कस्टम या अज्ञात मान के साथ |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | एक नया उदाहरण प्रारंभ करता है [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) वर्ग का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी 1819504742 |
| is_composite_protected | bool | r/w | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि यह उदाहरण संयुक्त रूप से संरक्षित है या नहीं। |
| is_position_protected | bool | r/w | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि यह उदाहरण स्थिति संरक्षित है या नहीं। |
| is_transparency_protected | bool | r/w | एक मान प्राप्त करता या सेट करता है जो दर्शाता है कि यह उदाहरण पारदर्शिता संरक्षित है या नहीं। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | लॉक के प्रकार को प्राप्त करता या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

एक नया उदाहरण प्रारंभ करता है [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) वर्ग का।

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

एक नया उदाहरण प्रारंभ करता है [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) वर्ग का।<br/>            कस्टम या अज्ञात मान के साथ

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | संसाधन डेटा। |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

एक नया उदाहरण प्रारंभ करता है [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) वर्ग का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| is_transparency_protected | bool | यदि <c>true</c> पर सेट किया गया है तो [पारदर्शिता संरक्षित है]. |
| is_composite_protected | bool | यदि <c>true</c> पर सेट किया गया है तो [संयोजन संरक्षित है]. |
| is_position_protected | bool | यदि <c>true</c> पर सेट किया गया है तो [स्थिति संरक्षित है]. |

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


---
title: "VscgResource वर्ग"
type: docs
weight: 30
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | VscgResource वर्ग का एक नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | संरचना आइटमों की सरणी को प्राप्त करता है या सेट करता है।<br/>            **Warning:** `Items` सरणी मानों को `KeyForData` प्रॉपर्टी के साथ मेल खाना चाहिए, जो `Items` के भीतर संरचनाओं में संग्रहीत फ़िल सेटिंग्स के प्रकार को निर्धारित करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| key_for_data | int | r | संसाधन में संग्रहीत फ़िल सेटिंग्स के प्रकार को परिभाषित करने वाली पूर्णांक कुंजी को प्राप्त करता है:<br/>            * रंग - 0x536f436f - SoCoResource.TypeToolKey<br/>            * ग्रेडिएंट - 0x4764466c - GdFlResource.TypeToolKey<br/>            * पैटर्न - 0x5074466c - PtFlResource.TypeToolKey<br/>            Warning! प्रॉपर्टी KeyForData का मान Items संरचनाओं में संग्रहीत फ़िल सेटिंग्स के प्रकार से मेल खाना चाहिए। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

VscgResource वर्ग का एक नया उदाहरण प्रारंभ करता है।

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


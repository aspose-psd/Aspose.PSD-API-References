---
title: "TypeToolInfoResource क्लास"
type: docs
weight: 1000
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | एक नया उदाहरण प्रारंभ करता है TypeToolInfoResource क्लास |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| a_component | short | r/w | एक घटक प्राप्त करता है या सेट करता है। |
| b_component | short | r/w | b घटक प्राप्त करता है या सेट करता है। |
| character_count | int | r/w | अक्षर गिनती प्राप्त करता है या सेट करता है। |
| color_space_value | short | r/w | रंग स्थान मान प्राप्त करता है या सेट करता है। |
| font_version | short | r/w | फ़ॉन्ट संस्करण प्राप्त करता है या सेट करता है। |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | फ़ॉन्ट्स प्राप्त करता है या सेट करता है। |
| fonts_count | short | r | फ़ॉन्ट्स की गिनती प्राप्त करता है। |
| g_component | short | r/w | g घटक प्राप्त करता है या सेट करता है। |
| horizontal_placement | int | r/w | क्षैतिज प्लेसमेंट प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| line_count | short | r | लाइन गिनती प्राप्त करता है. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | लाइन प्राप्त करता है या सेट करता है. |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| r_component | short | r/w | r घटक प्राप्त करता है या सेट करता है. |
| scale_factor | int | r/w | स्केल फ़ैक्टर प्राप्त करता है या सेट करता है. |
| selection_end | int | r/w | चयन समाप्ति प्राप्त करता है या सेट करता है. |
| selection_start | int | r/w | चयन प्रारंभ प्राप्त करता है या सेट करता है. |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | फ़ॉन्ट शैलियों को प्राप्त करता है या सेट करता है. |
| styles_count | short | r | शैलियों की गिनती प्राप्त करता है. |
| transform_matrix | डबल | r/w | रूपांतरण मैट्रिक्स प्राप्त करता है या सेट करता है. |
| type_value | short | r/w | टाइप मान प्राप्त करता है या सेट करता है. |
| version | short | r/w | संस्करण प्राप्त करता है या सेट करता है। |
| vertical_placement | int | r/w | ऊर्ध्वाधर प्लेसमेंट प्राप्त करता है या सेट करता है. |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

एक नया उदाहरण प्रारंभ करता है TypeToolInfoResource क्लास

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


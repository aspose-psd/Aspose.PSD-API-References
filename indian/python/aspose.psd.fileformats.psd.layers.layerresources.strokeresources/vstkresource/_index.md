---
title: "VstkResource क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | VstkResource क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| fill_enabled | bool | r/w | Stroke fill सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | स्ट्रोक की फ़िल सेटिंग्स को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| लंबाई | int | r | लेयर संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| stroke_enabled | bool | r/w | stroke effect सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Stroke Blend मोड प्राप्त करता है या सेट करता है। |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Stroke एंटिटी प्राप्त करता है या सेट करता है। यह प्रॉपर्टी स्ट्रोक की फ़िल सेटिंग्स निर्धारित करती है। |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | स्ट्रोक शैली की लाइन संरेखण को प्राप्त करता है या सेट करता है। |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | स्ट्रोक स्टाइल लाइन कैप का प्रकार प्राप्त करता है या सेट करता है। |
| stroke_style_line_cap_width | डबल | r/w | Stroke लाइन कैप की चौड़ाई प्राप्त करता है या सेट करता है। |
| stroke_style_line_dash_offset | int | r/w | स्ट्रोक स्टाइल लाइन डैश ऑफसेट प्राप्त करता है या सेट करता है। |
| stroke_style_line_dash_set | डबल | r/w | लाइन डैश की सरणी को प्राप्त करता है या सेट करता है। |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Stroke स्टाइल लाइन जॉइन प्रकार प्राप्त करता है या सेट करता है। |
| stroke_style_line_width | डबल | r/w | Stroke लाइन की चौड़ाई प्राप्त करता है या सेट करता है। |
| stroke_style_miter_limit | डबल | r/w | स्ट्रोक स्टाइल मिटर लिमिट प्राप्त करता है या सेट करता है। |
| stroke_style_opacity | int | r/w | Stroke स्टाइल अपारदर्शिता (0-100%) प्राप्त करता है या सेट करता है। |
| stroke_style_resolution | डबल | r/w | Stroke शैली रिज़ॉल्यूशन को प्राप्त करता है या सेट करता है। |
| stroke_style_scale_lock | bool | r/w | Stroke शैली स्केल लॉक को प्राप्त करता है या सेट करता है। |
| stroke_style_stroke_adjust | bool | r/w | Stroke समायोजन को प्राप्त करता है या सेट करता है। |
| stroke_style_version | int | r/w | stroke शैली संस्करण को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में संसाधन को सहेजता है। |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

VstkResource क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

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


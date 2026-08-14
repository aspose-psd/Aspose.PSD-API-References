---
title: "PlLdResource क्लास"
type: docs
weight: 820
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.<br/>            It was replaced by SoLdResource in the Adobe� Photoshop� CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | टाइप टूल जानकारी कुंजी। |
| anti_alias_policy | int | r/w | PSD इमेज में प्लेस्ड लेयर की एंटी-एलियास नीति प्राप्त करता है या सेट करता है। |
| नीचे | डबल | r/w | PSD इमेज में प्लेस्ड लेयर के बॉटम लोकेशन को प्राप्त करता है या सेट करता है। |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD फ़ाइल में प्लेस्ड लेयर की सीमाएँ प्राप्त करता है या सेट करता है। |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | क्षैतिज मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| horizontal_mesh_points | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| is_custom | bool | r/w | इस उदाहरण के वार्प शैली कस्टम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।<br/>यदि true है तो इसमें मेष बिंदु होते हैं। यदि false सेट किया जाता है तो मेष बिंदु मिटा देता है। |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | वार्प आइटम्स को प्राप्त करता है या सेट करता है। |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| left | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के बाएँ स्थान को प्राप्त करता है या सेट करता है। |
| लंबाई | int | r | PlLd संसाधन की लंबाई बाइट्स में प्राप्त करता है। |
| page_number | int | r/w | PSD फ़ाइल में रखी गई लेयर के पृष्ठ संख्या को प्राप्त करता है या सेट करता है। |
| perspective | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| perspective_other | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के अन्य परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD फ़ाइल में रखी गई लेयर के प्रकार को प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| right | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के दाएँ स्थान को प्राप्त करता है या सेट करता है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| ऊपर | डबल | r/w | PSD छवि में रखी गई लेयर के शीर्ष स्थान को प्राप्त करता है या सेट करता है। |
| total_pages | int | r/w | PSD फ़ाइल में रखी गई लेयर के कुल पृष्ठों को प्राप्त करता है या सेट करता है। |
| transform_matrix | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| u_order | int | r/w | PSD फ़ाइल में रखी गई लेयर के U क्रम मान को प्राप्त करता है या सेट करता है। |
| unique_id | Guid | r/w | PSD छवि में रखी गई लेयर के वैश्विक अद्वितीय पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| v_order | int | r/w | PSD फ़ाइल में रखी गई लेयर के V क्रम मान को प्राप्त करता है या सेट करता है। |
| value | डबल | r/w | PSD छवि में रखी गई लेयर के वार्प मान को प्राप्त करता है या सेट करता है। |
| version | int | r | PSD फ़ाइल में रखी गई लेयर का संस्करण प्राप्त करता है, आमतौर पर 3। |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | ऊर्ध्वाधर मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| vertical_mesh_points | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | PlLD संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

PlLD संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


---
title: "SoLdResource क्लास"
type: docs
weight: 930
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/
---

**Summary:** Defines the SoLdResource class that contains information about a smart object layer in a PSD file.<br/>            Is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLdResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [SoLdResource()](#SoLdResource__1) | एक नया उदाहरण प्रारंभ करता है [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) क्लास का।<br/> यह डिफ़ॉल्ट कंस्ट्रक्टर [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/) द्वारा उपयोग के लिए डिज़ाइन किया गया है।<br/> SoLdResource क्लास बनाने के लिए [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) का उपयोग करें। |
| [SoLdResource(unique_id, is_custom, has_comp_info)](#SoLdResource_unique_id_is_custom_has_comp_info_2) | एक नया उदाहरण प्रारंभ करता है [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) क्लास का।<br/> तैयार उदाहरण प्राप्त करने के लिए Items प्रॉपर्टी सेट करना या InitializeItems() कॉल करना आवश्यक है।<br/> यह कंस्ट्रक्टर [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) द्वारा उपयोग के लिए डिज़ाइन किया गया है<br/> और यूनिट टेस्ट में।<br/> SoLdResource क्लास बनाने के लिए [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) का उपयोग करें। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB-विशिष्ट संसाधन हस्ताक्षर। |
| RESOURCE_SIGNATURE [static] | int | r | सामान्य संसाधन हस्ताक्षर। |
| TYPE_TOOL_KEY [static] | int | r | प्रकार टूल जानकारी कुंजी: 'SoLd'। |
| anti_alias_policy | int | r/w | PSD छवि में स्मार्ट ऑब्जेक्ट लेयर डेटा की एंटी‑एलियास नीति प्राप्त करता है या सेट करता है। |
| नीचे | डबल | r/w | PSD इमेज में प्लेस्ड लेयर के बॉटम लोकेशन को प्राप्त करता है या सेट करता है। |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD फ़ाइल में प्लेस्ड लेयर की सीमाएँ प्राप्त करता है या सेट करता है। |
| comp | int | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के comp मान को प्राप्त करता है या सेट करता है।<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">स्मार्ट ऑब्जेक्ट्स में लेयर कंप्स</see> |
| comp_id | int | r/w | वर्तमान में चयनित comp का ID प्राप्त करता है या सेट करता है, जो बच्चा दस्तावेज़ के लिए है, यदि कोई चयन नहीं है तो यह -1 होगा।<br/>            कंप्स पेज लेआउट की रचनाएँ हैं जिन्हें डिजाइनर बना सकते हैं। लेयर कंप्स का उपयोग करके आप एक ही Adobe Photoshop फ़ाइल में लेआउट के कई संस्करण बना, प्रबंधित और देख सकते हैं। लेयर कंप लेयर्स पैनल की स्थिति का एक स्नैपशॉट है। लेयर कंप्स तीन प्रकार के लेयर विकल्प सहेजते हैं लेकिन यह प्रॉपर्टी PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर के लिए लेयर कंप चयन पहचानकर्ता प्राप्त करती है।<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">स्मार्ट ऑब्जेक्ट्स में लेयर कंप्स</see> |
| crop | int | r/w | PSD छवि में स्मार्ट ऑब्जेक्ट लेयर डेटा के क्रॉप को प्राप्त करता है या सेट करता है। |
| duration_denominator | int | r/w | अवधि हर को प्राप्त करता है या सेट करता है। |
| duration_numerator | int | r/w | अवधि अंश को प्राप्त करता है या सेट करता है। |
| frame_count | int | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा की फ्रेम गिनती को प्राप्त करता है या सेट करता है। |
| frame_step_denominator | int | r/w | फ़्रेम स्टेप हर को प्राप्त करता है या सेट करता है। |
| frame_step_numerator | int | r/w | फ़्रेम स्टेप अंश को प्राप्त करता है या सेट करता है। |
| height | डबल | r/w | ऊँचाई को प्राप्त करता है या सेट करता है। |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | क्षैतिज मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| horizontal_mesh_points | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| is_custom | bool | r/w | इस उदाहरण के वार्प शैली कस्टम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।<br/>यदि true है तो इसमें मेष बिंदु होते हैं। यदि false सेट किया जाता है तो मेष बिंदु मिटा देता है। |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Gets or sets the descriptor items of the smart object layer data in the PSD file. |
| key | int | r | लेयर संसाधन कुंजी को प्राप्त करता है। |
| left | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के बाएँ स्थान को प्राप्त करता है या सेट करता है। |
| लंबाई | int | r | स्मार्ट ऑब्जेक्ट रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| non_affine_transform_matrix | डबल | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के नॉन‑अफ़ाइन ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| original_comp_id | int | r | वर्तमान में चयनित चाइल्ड दस्तावेज़ के लिए मूल Comp ID प्राप्त करता है, यदि कोई चयन नहीं है तो यह -1 होगा।<br/>            यह प्रॉपर्टी PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर के लिए मूल लेयर Comp चयन पहचानकर्ता प्राप्त करती है।<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| page_number | int | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा का पेज नंबर प्राप्त करता है या सेट करता है। |
| perspective | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| perspective_other | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के अन्य परिप्रेक्ष्य मान को प्राप्त करता है या सेट करता है। |
| placed_id | Guid | r/w | PSD इमेज में इस स्मार्ट ऑब्जेक्ट लेयर डेटा का यूनिक आइडेंटिफ़ायर प्राप्त करता है या सेट करता है। |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा का प्रकार प्राप्त करता है या सेट करता है। |
| psd_version | int | r | लेयर संसाधन के लिए आवश्यक न्यूनतम psd संस्करण को प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| resolution | डबल | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा का रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा की रिज़ॉल्यूशन माप इकाई प्राप्त करता है या सेट करता है। |
| right | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के दाएँ स्थान को प्राप्त करता है या सेट करता है। |
| signature | int | r | हस्ताक्षर को प्राप्त करता है। |
| ऊपर | डबल | r/w | PSD छवि में रखी गई लेयर के शीर्ष स्थान को प्राप्त करता है या सेट करता है। |
| total_pages | int | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा की कुल पेज संख्या प्राप्त करता है या सेट करता है। |
| transform_matrix | डबल | r/w | PSD फ़ाइल में स्मार्ट ऑब्जेक्ट लेयर डेटा के ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है। |
| u_order | int | r/w | PSD फ़ाइल में रखी गई लेयर के U क्रम मान को प्राप्त करता है या सेट करता है। |
| unique_id | Guid | r/w | PSD इमेज में स्मार्ट ऑब्जेक्ट लेयर डेटा [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त करता है या सेट करता है। |
| v_order | int | r/w | PSD फ़ाइल में रखी गई लेयर के V क्रम मान को प्राप्त करता है या सेट करता है। |
| value | डबल | r/w | PSD छवि में रखी गई लेयर के वार्प मान को प्राप्त करता है या सेट करता है। |
| version | int | r | PSD फ़ाइल में रखी गई लेयर का संस्करण प्राप्त करता है, सामान्यतः 3-5। |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | ऊर्ध्वाधर मेष बिंदुओं की माप इकाई को प्राप्त करता है या सेट करता है। |
| vertical_mesh_points | डबल | r/w | PSD फ़ाइल में रखी गई लेयर के क्षैतिज मेष बिंदुओं को प्राप्त करता है या सेट करता है। |
| width | डबल | r/w | चौड़ाई को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | निर्दिष्ट स्ट्रीम कंटेनर में स्मार्ट ऑब्जेक्ट रिसोर्स को सहेजता है। |


### Constructor: SoLdResource() {#SoLdResource__1}


```
 SoLdResource() 
```

एक नया उदाहरण प्रारंभ करता है [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) क्लास का।<br/> यह डिफ़ॉल्ट कंस्ट्रक्टर [SoLdResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresourcesloaders/soldresourceloader/) द्वारा उपयोग के लिए डिज़ाइन किया गया है।<br/> SoLdResource क्लास बनाने के लिए [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) का उपयोग करें।

### Constructor: SoLdResource(unique_id, is_custom, has_comp_info) {#SoLdResource_unique_id_is_custom_has_comp_info_2}


```
 SoLdResource(unique_id, is_custom, has_comp_info) 
```

एक नया उदाहरण प्रारंभ करता है [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) क्लास का।<br/> तैयार उदाहरण प्राप्त करने के लिए Items प्रॉपर्टी सेट करना या InitializeItems() कॉल करना आवश्यक है।<br/> यह कंस्ट्रक्टर [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) द्वारा उपयोग के लिए डिज़ाइन किया गया है<br/> और यूनिट टेस्ट में।<br/> SoLdResource क्लास बनाने के लिए [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| unique_id | Guid | स्मार्ट ऑब्जेक्ट लेयर डेटा [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) का अद्वितीय पहचानकर्ता। |
| is_custom | bool | यदि सेट किया गया है <c>true</c> [is custom]। |
| has_comp_info | bool | यदि सेट किया गया है <c>true</c> [has comp information]। |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

निर्दिष्ट स्ट्रीम कंटेनर में स्मार्ट ऑब्जेक्ट रिसोर्स को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psd_version | int | PSD संस्करण। |


---
title: "LiFdDataSource क्लास"
type: docs
weight: 510
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---

**Summary:** Defines the liFD data source class in PSD File that contains information about an embedded file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFdDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LiFdDataSource()](#LiFdDataSource__1) | एक नया उदाहरण प्रारंभ करता है [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) क्लास का। |
| [LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | एक नया उदाहरण प्रारंभ करता है [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| asset_locked_state | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि PSD एसेट लॉक है या नहीं।<br/>            एसेट लॉक स्थिति, Adobe® Photoshop® СС लाइब्रेरीज़ एसेट्स के लिए। |
| asset_mod_time | डबल | r/w | Adobe® Photoshop® СС Libraries संपत्तियों के लिए एसेट संशोधित समय को प्राप्त करता है या सेट करता है। |
| child_doc_id | string | r/w | Lnk2 / LnkE Adobe® Photoshop® संसाधन के liFE या liFD डेटा स्रोत में चाइल्ड डॉक्यूमेंट पहचानकर्ता को प्राप्त करता है या सेट करता है। |
| comp_id | int | r/w | चाइल्ड डॉक्यूमेंट के लिए वर्तमान में चयनित कंप का ID प्राप्त करता है या सेट करता है, यदि कोई चयनित नहीं है तो यह -1 होगा।<br/>            कंप्स पेज लेआउट की संरचनाएँ हैं जिन्हें डिज़ाइनर बना सकते हैं। लेयर कंप्स का उपयोग करके आप एक ही Adobe® Photoshop® फ़ाइल में लेआउट के कई संस्करण बना, प्रबंधित और देख सकते हैं। लेयर कंप लेयर्स पैनल की स्थिति का स्नैपशॉट है। लेयर कंप्स तीन प्रकार के लेयर विकल्प सहेजते हैं लेकिन यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए लेयर कंप चयन पहचानकर्ता प्राप्त करती है।<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| data | byte | r/w | PSD फ़ाइल में एम्बेडेड स्मार्ट ऑब्जेक्ट डेटा को प्राप्त करता है या सेट करता है। |
| file_creator | string | r/w | PSD फ़ॉर्मेट LnkE / Lnk2 संसाधन में फ़ाइल निर्माता को प्राप्त करता है या सेट करता है। |
| file_type | string | r/w | Adobe® Photoshop® Lnk2 / LnkE संसाधन द्वारा रखी या लिंक की गई एम्बेडेड या बाहरी फ़ाइल के प्रकार को प्राप्त करता है या सेट करता है। |
| has_file_open_descriptor | bool | r/w | यह संकेत करने वाला मान प्राप्त करता है या सेट करता है कि इस लिंक डेटा स्रोत में फ़ाइल ओपन डिस्क्रिप्टर है या नहीं: CompId और OriginalCompId. |
| is_library_link | bool | r | यह संकेत करने वाला मान प्राप्त करता है कि यह PSD लिंक डेटा स्रोत Adobe® Photoshop® СС Library आइटम से लिंक करता है या नहीं। |
| लंबाई | long | r | लिंक डेटा स्रोत की लंबाई बाइट्स में प्राप्त करता है। |
| original_comp_id | int | r | वर्तमान में चयनित चाइल्ड दस्तावेज़ के लिए मूल Comp ID प्राप्त करता है, यदि कोई चयन नहीं है तो यह -1 होगा।<br/>            यह प्रॉपर्टी स्मार्ट ऑब्जेक्ट्स के लिए मूल लेयर Comp चयन पहचानकर्ता प्राप्त करती है।<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">स्मार्ट ऑब्जेक्ट्स में लेयर कॉम्प्स</see> |
| original_file_name | string | r | Adobe® Photoshop® ग्लोबल लिंक रिसोर्स में डेटा स्रोत की मूल फ़ाइल नाम प्राप्त करता है। |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | Adobe® Photoshop® ग्लोबल लिंक डेटा स्रोत प्रकार प्राप्त करता है जो निम्नलिखित में से कोई एक या कोई नहीं हो सकता है:<br/>            PSD Lnk2Resource के अनुरूप एम्बेडेड लिंक्ड फ़ाइल liFD<br/>            PSD LnkeResource के अनुरूप एक्सटर्नल लिंक्ड फ़ाइल liFE<br/>            लिंक्ड फ़ाइल उपनाम liFA |
| unique_id | Guid | r | PSD लिंक रिसोर्स में डेटा स्रोत का ग्लोबल यूनिक आइडेंटिफ़ायर प्राप्त करता है। |
| version | int | r | PSD LnkE / Lnk2 रिसोर्स में डेटा स्रोत का संस्करण प्राप्त करता है। |


### Constructor: LiFdDataSource() {#LiFdDataSource__1}


```
 LiFdDataSource() 
```

एक नया उदाहरण प्रारंभ करता है [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) क्लास का।

### Constructor: LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFdDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFdDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

एक नया उदाहरण प्रारंभ करता है [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| version | int | संस्करण। |
| unique_id | Guid | यूनिक आइडेंटिफ़ायर। |
| original_file_name | string | मूल फ़ाइल का नाम। |
| file_type | string | फ़ाइल का प्रकार। |
| file_creator | string | फ़ाइल निर्माता। |


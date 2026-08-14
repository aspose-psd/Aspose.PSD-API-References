---
title: "FontSettings क्लास"
type: docs
weight: 1370
url: /hi/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| डिफ़ॉल्ट फ़ॉन्ट नाम [static] | string | r/w | फ़ॉन्ट के डिफ़ॉल्ट नाम को प्राप्त करता है या सेट करता है। |
| get_system_alternative_font [static] | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या [get alternative font]। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| clear_font_replacements() | सभी फ़ॉन्ट प्रतिस्थापनों को साफ़ करता है |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | फ़ॉन्ट परिवार नाम द्वारा एडोब फ़ॉन्ट नाम प्राप्त करता है। |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | डिफ़ॉल्ट फ़ॉन्ट फ़ोल्डर्स प्राप्त करता है। |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | फ़ॉन्ट नाम द्वारा फ़ॉन्ट प्रतिस्थापन एरे प्राप्त करता है |
| [get_fonts_folders()](#get_fonts_folders__4) | एक एरे की कॉपी प्राप्त करता है जिसमें उन फ़ोल्डरों की सूची होती है जहाँ Aspose.Words TrueType फ़ॉन्ट्स खोजता है। |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | सबसे उपयुक्त प्रतिस्थापन फ़ॉन्ट प्राप्त करता है।<br/>            यदि सभी प्रतिस्थापन अनुमत नहीं हैं तो पहला अनुमत और उपलब्ध फ़ॉन्ट लौटाया जाएगा।<br/>            यदि कोई उपलब्ध फ़ॉन्ट नहीं है तो तर्क से फ़ॉन्ट लौटाया जाएगा। |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | निर्धारित करता है कि क्या [is font allowed] [निर्दिष्ट फ़ॉन्ट नाम]। |
| remove_font_cache_file() | फ़ॉन्ट कैश फ़ाइल को हटाता है। |
| reset() | फ़ॉन्ट फ़ोल्डर और डिफ़ॉल्ट फ़ॉन्ट नाम को सिस्टम डिफ़ॉल्ट पर रीसेट करता है। |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | फ़ॉन्ट को फ़ॉन्टों की सूची द्वारा प्रतिबंधित करता है। प्रतिबंध लगाने से पहले वास्तविक फ़ॉन्ट नाम जाँचें<br/>            प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को Null सेट करें। |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फ़ॉन्ट अनुमति नहीं है तो प्रतिस्थापन खोजा जाएगा।<br/>            सूची में पहला फ़ॉन्ट पहले उपयोग किया जाएगा। यदि वह भी प्रतिबंधित है, तो सूची से अगला फ़ॉन्ट चुना जाएगा।<br/>            यदि फ़ॉन्ट के पास कोई प्रतिस्थापन नहीं है या सभी प्रतिस्थापन अनुमति नहीं हैं, तो अनुमत फ़ॉन्ट सूची से पहला अनुमति प्राप्त फ़ॉन्ट उपयोग किया जाएगा।<br/>            यदि कोई अनुमति प्राप्त और उपलब्ध फ़ॉन्ट नहीं हैं, तो लाइब्रेरी सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने की कोशिश करेगी, भले ही वह अनुमति न हो। |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | यह केवल एक फ़ॉन्ट डायरेक्टरी सेट करने के लिए [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) का शॉर्टकट है।<br/>            फ़ॉन्ट फ़ोल्डर पर कोई जाँच नहीं की जाती है। |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | उन फ़ोल्डरों को सेट करता है जहाँ से TrueType फ़ॉन्ट लोड होते हैं और सभी लोड किए गए फ़ॉन्ट साफ़ करता है।<br/>            फ़ॉन्ट फ़ोल्डरों पर कोई जाँच नहीं की जाती है। |
| update_fonts() | टेक्स्ट लेयर वाले PSD फ़ाइलों के लिए फ़ॉन्ट कैश को अपडेट करता है। यह मेथड यह सुनिश्चित करता है कि फ़ॉन्ट फ़ोल्डर fontsFolder से फ़ॉन्ट, मेथड FontSettings.SetFontsFolder(fontsFolder) का उपयोग करके या FontSettings.Reset() द्वारा फ़ॉन्ट रीसेट करने के बाद, PSD फ़ाइलों को प्रोसेस करते समय ध्यान में रखे जाएँ। कृपया इस मेथड को प्रत्येक बार उपयोग करें जब <br/>            FontSettings.SetFontsFolder(fontsFolder) या FontSettings.Reset() को PSD इमेज के लिए कॉल किया जाए। इस मेथड को कॉल किए बिना फ़ॉन्ट अपडेट होने की कोई गारंटी नहीं है। |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

फ़ॉन्ट परिवार नाम द्वारा एडोब फ़ॉन्ट नाम प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_family_name | string | फ़ॉन्ट परिवार का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | फ़ॉन्ट परिवार नाम द्वारा Adobe फ़ॉन्ट नाम। |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

डिफ़ॉल्ट फ़ॉन्ट फ़ोल्डर्स प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | सिस्टम फ़ोल्डर लौटाता है |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

फ़ॉन्ट नाम द्वारा फ़ॉन्ट प्रतिस्थापन एरे प्राप्त करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | फ़ॉन्ट का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | प्रदान किए गए फ़ॉन्टों के प्रतिस्थापन नामों की एरे |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

एक एरे की कॉपी प्राप्त करता है जिसमें उन फ़ोल्डरों की सूची होती है जहाँ Aspose.Words TrueType फ़ॉन्ट्स खोजता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | वर्तमान फ़ॉन्ट स्थानों की एक कॉपी। |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

सबसे उपयुक्त प्रतिस्थापन फ़ॉन्ट प्राप्त करता है।<br/>            यदि सभी प्रतिस्थापन अनुमत नहीं हैं तो पहला अनुमत और उपलब्ध फ़ॉन्ट लौटाया जाएगा।<br/>            यदि कोई उपलब्ध फ़ॉन्ट नहीं है तो तर्क से फ़ॉन्ट लौटाया जाएगा।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | फ़ॉन्ट का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | प्रतिस्थापित फ़ॉन्ट का नाम |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

निर्धारित करता है कि क्या [is font allowed] [निर्दिष्ट फ़ॉन्ट नाम]।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | फ़ॉन्ट का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि [फ़ॉन्ट अनुमति है] [निर्दिष्ट फ़ॉन्ट नाम]; अन्यथा, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

फ़ॉन्ट को फ़ॉन्टों की सूची द्वारा प्रतिबंधित करता है। प्रतिबंध लगाने से पहले वास्तविक फ़ॉन्ट नाम जाँचें<br/>            प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को Null सेट करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_list | string | फ़ॉन्ट सूची। |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फ़ॉन्ट अनुमति नहीं है तो प्रतिस्थापन खोजा जाएगा।<br/>            सूची में पहला फ़ॉन्ट पहले उपयोग किया जाएगा। यदि वह भी प्रतिबंधित है, तो सूची से अगला फ़ॉन्ट चुना जाएगा।<br/>            यदि फ़ॉन्ट के पास कोई प्रतिस्थापन नहीं है या सभी प्रतिस्थापन अनुमति नहीं हैं, तो अनुमत फ़ॉन्ट सूची से पहला अनुमति प्राप्त फ़ॉन्ट उपयोग किया जाएगा।<br/>            यदि कोई अनुमति प्राप्त और उपलब्ध फ़ॉन्ट नहीं हैं, तो लाइब्रेरी सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने की कोशिश करेगी, भले ही वह अनुमति न हो।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_to_replace | string | प्रतिस्थापित करने के लिए फ़ॉन्ट। |
| font_names | string | समानता के क्रम में प्रतिस्थापन फ़ॉन्ट नाम। |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

यह केवल एक फ़ॉन्ट डायरेक्टरी सेट करने के लिए [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) का शॉर्टकट है।<br/>            फ़ॉन्ट फ़ोल्डर पर कोई जाँच नहीं की जाती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_folder | string | फ़ॉन्ट फ़ोल्डर। |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

उन फ़ोल्डरों को सेट करता है जहाँ से TrueType फ़ॉन्ट लोड होते हैं और सभी लोड किए गए फ़ॉन्ट साफ़ करता है।<br/>            फ़ॉन्ट फ़ोल्डरों पर कोई जाँच नहीं की जाती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fonts_folders | string | The फ़ॉन्ट फ़ोल्डर। |
| पुनरावर्ती | bool | यदि <c>true</c> पर सेट किया गया है तो [recursive]। |


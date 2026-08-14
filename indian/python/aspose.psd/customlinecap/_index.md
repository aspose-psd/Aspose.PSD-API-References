---
title: "CustomLineCap क्लास"
type: docs
weight: 1010
url: /hi/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | निर्दिष्ट रूपरेखा और भराव के साथ [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) क्लास का नया उदाहरण आरंभ करता है। |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | निर्दिष्ट रूपरेखा और भराव के साथ निर्दिष्ट मौजूदा [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration से [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) क्लास का नया उदाहरण आरंभ करता है। |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | निर्दिष्ट रूपरेखा, भराव और इनसेट के साथ निर्दिष्ट मौजूदा [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration से [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) क्लास का नया उदाहरण आरंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration को प्राप्त करता है या सेट करता है, जिस पर यह [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) आधारित है। |
| base_inset | float | r/w | कैप और रेखा के बीच की दूरी को प्राप्त करता है या सेट करता है। |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | कस्टम कैप के लिए भराव को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | [LineJoin](/psd/python-net/aspose.psd/linejoin/) enumeration को प्राप्त करता है या सेट करता है, जो निर्धारित करता है कि इस [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) ऑब्जेक्ट को बनाते हुए रेखाएँ कैसे जुड़ती हैं। |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | कस्टम कैप की रूपरेखा को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| width_scale | float | r/w | इस [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) क्लास ऑब्जेक्ट को वस्तु की चौड़ाई के सापेक्ष स्केल करने की मात्रा को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप को प्राप्त करता है। |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप को सेट करता है। |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

निर्दिष्ट रूपरेखा और भराव के साथ [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ऑब्जेक्ट जो कस्टम कैप के लिए भराव को परिभाषित करता है। |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

निर्दिष्ट रूपरेखा और भराव के साथ निर्दिष्ट मौजूदा [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration से [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ऑब्जेक्ट जो कस्टम कैप के लिए भराव को परिभाषित करता है। |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | कस्टम कैप बनाने के लिए उपयोग किया जाने वाला लाइन कैप। |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

निर्दिष्ट रूपरेखा, भराव और इनसेट के साथ निर्दिष्ट मौजूदा [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration से [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ऑब्जेक्ट जो कस्टम कैप के लिए भराव को परिभाषित करता है। |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | कस्टम कैप बनाने के लिए उपयोग किया जाने वाला लाइन कैप। |
| base_inset | float | कैप और रेखा के बीच की दूरी। |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप को प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | इस कैप के भीतर रेखा की शुरुआत में उपयोग किया जाने वाला [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration। |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | इस कैप के भीतर रेखा के अंत में उपयोग किया जाने वाला [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration। |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप को सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | इस कैप के भीतर रेखा की शुरुआत में उपयोग किया जाने वाला [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration। |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | इस कैप के भीतर रेखा के अंत में उपयोग किया जाने वाला [LineCap](/psd/python-net/aspose.psd/linecap/) enumeration। |


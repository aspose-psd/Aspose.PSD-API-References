---
title: "StringFormat क्लास"
type: docs
weight: 4260
url: /hi/python-net/aspose.psd/stringformat/
---

**Summary:** Encapsulates text layout information (such as alignment, orientation and tab stops) display manipulations (such as ellipsis insertion and national digit substitution) and OpenType features. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormat

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [StringFormat()](#StringFormat__1) | एक नया [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट इनिशियलाइज़ करता है। |
| [StringFormat(format)](#StringFormat_format_2) | निर्दिष्ट मौजूदा [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट से एक नया [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट इनिशियलाइज़ करता है। |
| [StringFormat(options)](#StringFormat_options_3) | निर्दिष्ट [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) एन्यूमरेशन और भाषा के साथ एक नया [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | वर्टिकल प्लेन पर टेक्स्ट अलाइनमेंट जानकारी प्राप्त करता है या सेट करता है। |
| custom_char_ident | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | कस्टम कैरेक्टर आइडेंट प्राप्त करता है या सेट करता है। |
| digit_substitution_language | int | r/w | स्थानीय अंकों को पश्चिमी अंकों से बदलने पर उपयोग की जाने वाली भाषा प्राप्त करता है या सेट करता है। |
| digit_substitution_method | [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute) | r/w | अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि प्राप्त करता है या सेट करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| first_tab_offset | float | r | टेक्स्ट की एक पंक्ति की शुरुआत और पहले टैब स्टॉप के बीच स्पेस की संख्या प्राप्त करता है। |
| format_flags | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | r/w | फ़ॉर्मेटिंग जानकारी शामिल करने वाले एक [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) एनेमरेशन को प्राप्त करता है या सेट करता है। |
| generic_default [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | एक सामान्य डिफ़ॉल्ट [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट प्राप्त करता है। |
| generic_typographic [static] | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r | एक सामान्य टाइपोग्राफिक [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट प्राप्त करता है। |
| hotkey_prefix | [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix) | r/w | इस [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट के लिए [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| line_alignment | [StringAlignment](/psd/python-net/aspose.psd/stringalignment) | r/w | हॉरिज़ॉन्टल प्लेन पर लाइन अलाइनमेंट प्राप्त करता है या सेट करता है। |
| tab_stops | float | r | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में टैब स्टॉप्स के बीच दूरी की एक एरे प्राप्त करता है। |
| trimming | [StringTrimming](/psd/python-net/aspose.psd/stringtrimming) | r/w | इस [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट के लिए [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) एनेमरेशन को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | इस [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट की एक डीप क्लोन बनाता है। |
| [set_tab_stops(first_tab_offset, tab_stops)](#set_tab_stops_first_tab_offset_tab_stops_2) | इस [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट के लिए टैब स्टॉप्स सेट करता है। |


### Constructor: StringFormat() {#StringFormat__1}


```
 StringFormat() 
```

एक नया [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट इनिशियलाइज़ करता है।

### Constructor: StringFormat(format) {#StringFormat_format_2}


```
 StringFormat(format) 
```

निर्दिष्ट मौजूदा [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट से एक नया [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | नए [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट को इनिशियलाइज़ करने के लिए [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट। |

### Constructor: StringFormat(options) {#StringFormat_options_3}


```
 StringFormat(options) 
```

निर्दिष्ट [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) एन्यूमरेशन और भाषा के साथ एक नया [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags) | नए [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट के लिए [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) एनेमरेशन। |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

इस [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट की एक डीप क्लोन बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [StringFormat](/psd/python-net/aspose.psd/stringformat) | वर्तमान [StringFormat](/psd/python-net/aspose.psd/stringformat/) की डीप क्लोन। |


### Method: set_tab_stops(first_tab_offset, tab_stops) {#set_tab_stops_first_tab_offset_tab_stops_2}


```
 set_tab_stops(first_tab_offset, tab_stops) 
```

इस [StringFormat](/psd/python-net/aspose.psd/stringformat/) ऑब्जेक्ट के लिए टैब स्टॉप्स सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| first_tab_offset | float | टेक्स्ट की एक पंक्ति की शुरुआत और पहले टैब स्टॉप के बीच स्पेस की संख्या। |
| tab_stops | float | [Graphics.page_unit](/psd/python-net/aspose.psd/graphics/) प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में टैब स्टॉप्स के बीच दूरी की एक एरे। |


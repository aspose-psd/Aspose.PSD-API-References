---
title: "XmpPackage क्लास"
type: docs
weight: 430
url: /hi/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| namespace_uri | string | r | नेमस्पेस URI प्राप्त करता है। |
| उपसर्ग | string | r | उपसर्ग प्राप्त करता है। |
| xml_namespace | string | r | XML नेमस्पेस प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | मान जोड़ता है। |
| clear() | इस इंस्टेंस को साफ करता है। |
| [contains_key(key)](#contains_key_key_2) | निर्धारित करता है कि निर्दिष्ट कुंजी में कुंजी शामिल है या नहीं। |
| [get_xml_value()](#get_xml_value__3) | XMP मान को XML प्रतिनिधित्व में परिवर्तित करता है। |
| [remove(key)](#remove_key_4) | निर्दिष्ट कुंजी के साथ मान को हटाएँ। |
| [set_value(key, value)](#set_value_key_value_5) | मान सेट करता है। |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | XMP प्रकार मान सेट करता है। |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

मान जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | जोड़े गए मान के साथ पहचानी गई कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | string | जोड़ने के लिए मान। |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

निर्धारित करता है कि निर्दिष्ट कुंजी में कुंजी शामिल है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | जाँचने के लिए कुंजी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यदि निर्दिष्ट कुंजी में कुंजी शामिल है तो true लौटाता है। |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP मान को XML प्रतिनिधित्व में परिवर्तित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | XMP मान को XML प्रतिनिधित्व में परिवर्तित करके लौटाता है। |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

निर्दिष्ट कुंजी के साथ मान को हटाएँ।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | हटाए गए मान के साथ पहचानी गई कुंजी का स्ट्रिंग प्रतिनिधित्व। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यदि निर्दिष्ट कुंजी के साथ मान हटाया गया हो तो true लौटाता है। |


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | जोड़े गए मान के साथ पहचानी गई कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | जोड़ने के लिए मान। |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

XMP प्रकार मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | सेट मान के साथ पहचाने गए कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | सेट करने के लिए मान। |


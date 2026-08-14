---
title: "PdfPackage क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | PdfPackage क्लास का नया इंस्टेंस प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| namespace_uri | string | r | नेमस्पेस URI प्राप्त करता है। |
| उपसर्ग | string | r | उपसर्ग प्राप्त करता है। |
| xml_namespace | string | r | XML नेमस्पेस प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | स्ट्रिंग प्रॉपर्टी जोड़ता है। |
| clear() | इस इंस्टेंस को साफ करता है। |
| [contains_key(key)](#contains_key_key_2) | निर्धारित करता है कि निर्दिष्ट कुंजी में कुंजी शामिल है या नहीं। |
| [get_xml_value()](#get_xml_value__3) | XMP मान को XML प्रतिनिधित्व में परिवर्तित करता है। |
| [remove(key)](#remove_key_4) | निर्दिष्ट कुंजी के साथ मान को हटाएँ। |
| [set_keywords(keywords)](#set_keywords_keywords_5) | कीवर्ड सेट करता है। |
| [set_pdf_version(version)](#set_pdf_version_version_6) | PDF संस्करण सेट करता है। |
| [set_producer(producer)](#set_producer_producer_7) | Pdf बनाने वाले टूल का नाम सेट करता है। |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | ट्रैप्ड सेट करता है। |
| [set_value(key, value)](#set_value_key_value_9) | मान सेट करता है। |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | XMP प्रकार मान सेट करता है। |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

PdfPackage क्लास का नया इंस्टेंस प्रारंभ करता है

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

स्ट्रिंग प्रॉपर्टी जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | जोड़े गए मान के साथ पहचानी गई कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | string | स्ट्रिंग मान। |

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

कीवर्ड सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कीवर्ड | string | कीवर्ड। |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

PDF संस्करण सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| version | string | Pdf संस्करण, उदाहरण के लिए: 1.0, 1.3 आदि। |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Pdf बनाने वाले टूल का नाम सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| प्रोड्यूसर | string | प्रोड्यूसर का नाम। |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

ट्रैप्ड सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| is_trapped | bool | यदि <c>true</c> पर सेट किया गया है तो दस्तावेज़ ट्रैप्ड किया गया है। |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | जोड़े गए मान के साथ पहचानी गई कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | जोड़ने के लिए मान। |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

XMP प्रकार मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | सेट मान के साथ पहचाने गए कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | सेट करने के लिए मान। |


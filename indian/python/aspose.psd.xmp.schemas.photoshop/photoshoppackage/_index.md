---
title: "PhotoshopPackage क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Summary:** Represents Adobe Photoshop namespace.

**Module:** [aspose.psd.xmp.schemas.photoshop](/psd/python-net/aspose.psd.xmp.schemas.photoshop/)

**Full Name:** aspose.psd.xmp.schemas.photoshop.PhotoshopPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PhotoshopPackage()](#PhotoshopPackage__1) | PhotoshopPackage class का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| URGENCY_MAX [static] | int | r | अधिकतम तात्कालिकता मान। |
| URGENCY_MIN [static] | int | r | न्यूनतम तात्कालिकता मान। |
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
| [set_authors_position(authors_position)](#set_authors_position_authors_position_5) | लेखकों की स्थिति सेट करता है। |
| [set_caption_writer(caption_writer)](#set_caption_writer_caption_writer_6) | कैप्शन लेखक सेट करता है। |
| [set_category(category)](#set_category_category_7) | श्रेणी सेट करता है। |
| [set_city(city)](#set_city_city_8) | शहर सेट करता है। |
| [set_color_mode(color_mode)](#set_color_mode_color_mode_9) | रंग मोड सेट करता है। |
| [set_country(country)](#set_country_country_10) | देश सेट करता है। |
| [set_created_date(created_date)](#set_created_date_created_date_11) | निर्माण तिथि सेट करता है। |
| [set_credit(credit)](#set_credit_credit_12) | क्रेडिट सेट करता है। |
| [set_document_ancestors(ancestors)](#set_document_ancestors_ancestors_13) | दस्तावेज़ पूर्वज सेट करता है। |
| [set_headline(headline)](#set_headline_headline_14) | हेडलाइन सेट करता है। |
| [set_history(history)](#set_history_history_15) | इतिहास सेट करता है। |
| [set_icc_profile(icc_profile)](#set_icc_profile_icc_profile_16) | आईसीसी प्रोफ़ाइल सेट करता है। |
| [set_instructions(instructions)](#set_instructions_instructions_17) | निर्देश सेट करता है। |
| [set_source(source)](#set_source_source_18) | स्रोत सेट करता है। |
| [set_state(state)](#set_state_state_19) | राज्य सेट करता है। |
| [set_supplemental_categories(supplemental_categories)](#set_supplemental_categories_supplemental_categories_20) | पूरक श्रेणियाँ सेट करता है। |
| [set_transmission_reference(transmission_reference)](#set_transmission_reference_transmission_reference_21) | प्रसारण संदर्भ सेट करता है। |
| [set_urgency(urgency)](#set_urgency_urgency_22) | तात्कालिकता सेट करता है। |
| [set_value(key, value)](#set_value_key_value_23) | मान सेट करता है। |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_24) | XMP प्रकार मान सेट करता है। |


### Constructor: PhotoshopPackage() {#PhotoshopPackage__1}


```
 PhotoshopPackage() 
```

PhotoshopPackage class का नया उदाहरण प्रारंभ करता है।

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


### Method: set_authors_position(authors_position) {#set_authors_position_authors_position_5}


```
 set_authors_position(authors_position) 
```

लेखकों की स्थिति सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| authors_position | string | लेखकों की स्थिति। |

### Method: set_caption_writer(caption_writer) {#set_caption_writer_caption_writer_6}


```
 set_caption_writer(caption_writer) 
```

कैप्शन लेखक सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| caption_writer | string | कैप्शन लेखक। |

### Method: set_category(category) {#set_category_category_7}


```
 set_category(category) 
```

श्रेणी सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| category | string | श्रेणी। |

### Method: set_city(city) {#set_city_city_8}


```
 set_city(city) 
```

शहर सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| city | string | शहर का नाम। |

### Method: set_color_mode(color_mode) {#set_color_mode_color_mode_9}


```
 set_color_mode(color_mode) 
```

रंग मोड सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_mode | [ColorMode](/psd/python-net/aspose.psd.xmp.types.complex.colorant/colormode) | रंग मोड। |

### Method: set_country(country) {#set_country_country_10}


```
 set_country(country) 
```

देश सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| country | string | देश। |

### Method: set_created_date(created_date) {#set_created_date_created_date_11}


```
 set_created_date(created_date) 
```

निर्माण तिथि सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| created_date | datetime | निर्मित तिथि। |

### Method: set_credit(credit) {#set_credit_credit_12}


```
 set_credit(credit) 
```

क्रेडिट सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| credit | string | क्रेडिट। |

### Method: set_document_ancestors(ancestors) {#set_document_ancestors_ancestors_13}


```
 set_document_ancestors(ancestors) 
```

दस्तावेज़ पूर्वज सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ancestors | string | पूर्वज। |

### Method: set_headline(headline) {#set_headline_headline_14}


```
 set_headline(headline) 
```

हेडलाइन सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| headline | string | शीर्षक। |

### Method: set_history(history) {#set_history_history_15}


```
 set_history(history) 
```

इतिहास सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| history | string | इतिहास। |

### Method: set_icc_profile(icc_profile) {#set_icc_profile_icc_profile_16}


```
 set_icc_profile(icc_profile) 
```

आईसीसी प्रोफ़ाइल सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| icc_profile | string | आईसीसी प्रोफ़ाइल। |

### Method: set_instructions(instructions) {#set_instructions_instructions_17}


```
 set_instructions(instructions) 
```

निर्देश सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| instructions | string | निर्देश। |

### Method: set_source(source) {#set_source_source_18}


```
 set_source(source) 
```

स्रोत सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्रोत | string | स्रोत। |

### Method: set_state(state) {#set_state_state_19}


```
 set_state(state) 
```

राज्य सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| state | string | स्थिति। |

### Method: set_supplemental_categories(supplemental_categories) {#set_supplemental_categories_supplemental_categories_20}


```
 set_supplemental_categories(supplemental_categories) 
```

पूरक श्रेणियाँ सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| supplemental_categories | string | पूरक श्रेणियाँ। |

### Method: set_transmission_reference(transmission_reference) {#set_transmission_reference_transmission_reference_21}


```
 set_transmission_reference(transmission_reference) 
```

प्रसारण संदर्भ सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| transmission_reference | string | प्रसारण संदर्भ। |

### Method: set_urgency(urgency) {#set_urgency_urgency_22}


```
 set_urgency(urgency) 
```

तात्कालिकता सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| तत्कालता | int | तत्कालता। |

### Method: set_value(key, value) {#set_value_key_value_23}


```
 set_value(key, value) 
```

मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | जोड़े गए मान के साथ पहचानी गई कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | जोड़ने के लिए मान। |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_24}


```
 set_xmp_type_value(key, value) 
```

XMP प्रकार मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| key | string | सेट मान के साथ पहचाने गए कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | सेट करने के लिए मान। |


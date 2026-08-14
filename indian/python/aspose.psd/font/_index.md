---
title: "Font क्लास"
type: docs
weight: 1340
url: /hi/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | निर्दिष्ट आकार का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है। कैरेक्टर सेट को [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) पर सेट किया जाता है, ग्राफ़िक्स यूनिट को [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) पर, और फ़ॉन्ट शैली को [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) पर सेट किया जाता है। |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | निर्दिष्ट आकार और शैली का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है। कैरेक्टर सेट को [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) पर, ग्राफ़िक्स यूनिट को [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) पर सेट किया जाता है। |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | निर्दिष्ट आकार, शैली और यूनिट का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है। |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | निर्दिष्ट आकार, शैली, यूनिट और कैरेक्टर सेट का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है। |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | निर्दिष्ट आकार और इकाई का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) को प्रारंभ करता है। कैरेक्टर सेट को [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) पर सेट किया गया है, शैली को [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) पर सेट किया गया है। |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | निर्दिष्ट मौजूदा [Font](/psd/python-net/aspose.psd/font/) और [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeration का उपयोग करने वाला एक नया [Font](/psd/python-net/aspose.psd/font/) को प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| bold | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह [Font](/psd/python-net/aspose.psd/font/) बोल्ड है या नहीं। |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | एक बाइट मान प्राप्त करता है जो इस [Font](/psd/python-net/aspose.psd/font/) द्वारा उपयोग किए जाने वाले कैरेक्टर सेट को निर्दिष्ट करता है। |
| italic | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह [Font](/psd/python-net/aspose.psd/font/) इटैलिक है या नहीं। |
| name | string | r | इस [Font](/psd/python-net/aspose.psd/font/) का फ़ेस नाम प्राप्त करता है। |
| size | float | r | इस [Font](/psd/python-net/aspose.psd/font/) का em-size प्राप्त करता है, जिसे [Font.unit](/psd/python-net/aspose.psd/font/) प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में मापा जाता है। |
| strikeout | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह [Font](/psd/python-net/aspose.psd/font/) फ़ॉन्ट के माध्यम से एक क्षैतिज रेखा निर्दिष्ट करता है या नहीं। |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | इस [Font](/psd/python-net/aspose.psd/font/) के लिए शैली जानकारी प्राप्त करता है। |
| underline | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह [Font](/psd/python-net/aspose.psd/font/) अंडरलाइन है या नहीं। |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | इस [Font](/psd/python-net/aspose.psd/font/) के लिए माप इकाई प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | इस [Font](/psd/python-net/aspose.psd/font/) की एक सटीक डीप कॉपी बनाता है। |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

निर्दिष्ट आकार का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है। कैरेक्टर सेट को [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) पर सेट किया जाता है, ग्राफ़िक्स यूनिट को [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) पर, और फ़ॉन्ट शैली को [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) पर सेट किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) नाम का स्ट्रिंग प्रतिनिधित्व। |
| em_size | float | नए फ़ॉन्ट का em-size, पॉइंट्स में। |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

निर्दिष्ट आकार और शैली का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है। कैरेक्टर सेट को [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) पर, ग्राफ़िक्स यूनिट को [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) पर सेट किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) नाम का स्ट्रिंग प्रतिनिधित्व। |
| em_size | float | नए फ़ॉन्ट का em-size, पॉइंट्स में। |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | नए फ़ॉन्ट की [FontStyle](/psd/python-net/aspose.psd/fontstyle/)। |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

निर्दिष्ट आकार, शैली और यूनिट का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) नाम का स्ट्रिंग प्रतिनिधित्व। |
| em_size | float | नए फ़ॉन्ट का em-size, उन इकाइयों में जो <paramref name="unit" /> पैरामीटर द्वारा निर्दिष्ट हैं। |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | नए फ़ॉन्ट की [FontStyle](/psd/python-net/aspose.psd/fontstyle/)। |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | नए फ़ॉन्ट का [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)। |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

निर्दिष्ट आकार, शैली, यूनिट और कैरेक्टर सेट का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) नाम का स्ट्रिंग प्रतिनिधित्व। |
| em_size | float | नए फ़ॉन्ट का em-size, उन इकाइयों में जो <paramref name="unit" /> पैरामीटर द्वारा निर्दिष्ट हैं। |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | नए फ़ॉन्ट की [FontStyle](/psd/python-net/aspose.psd/fontstyle/)। |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | नए फ़ॉन्ट का [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)। |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | इस फ़ॉन्ट के लिए उपयोग करने वाला कैरेक्टर सेट। |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

निर्दिष्ट आकार और इकाई का उपयोग करके एक नया [Font](/psd/python-net/aspose.psd/font/) को प्रारंभ करता है। कैरेक्टर सेट को [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) पर सेट किया गया है, शैली को [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) पर सेट किया गया है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) नाम का स्ट्रिंग प्रतिनिधित्व। |
| em_size | float | नए फ़ॉन्ट का em-size, उन इकाइयों में जो <paramref name="unit" /> पैरामीटर द्वारा निर्दिष्ट हैं। |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | नए फ़ॉन्ट का [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/)। |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

निर्दिष्ट मौजूदा [Font](/psd/python-net/aspose.psd/font/) और [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeration का उपयोग करने वाला एक नया [Font](/psd/python-net/aspose.psd/font/) को प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | वह मौजूदा [Font](/psd/python-net/aspose.psd/font/) जिससे नया [Font](/psd/python-net/aspose.psd/font/) बनाया जाएगा। |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | नए [Font](/psd/python-net/aspose.psd/font/) पर लागू करने के लिए [FontStyle](/psd/python-net/aspose.psd/fontstyle/)। [FontStyle](/psd/python-net/aspose.psd/fontstyle/) enumeration के कई मानों को OR ऑपरेटर के साथ जोड़ा जा सकता है। |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

इस [Font](/psd/python-net/aspose.psd/font/) की एक सटीक डीप कॉपी बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | यह विधि द्वारा बनाया गया [Font](/psd/python-net/aspose.psd/font/)। |



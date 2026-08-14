---
title: "RawColor क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---

**Summary:** Raw Color Class helps to store colors with any channels count, any color mode and any bit depth<br/>            Please note, some internal classes can have issues with converting RawColor to its' native format,<br/>            so if API provides for you CMYK color, it's more reliable to use the provided format.<br/>            Also, there are can be some cases when Raw Color can be converted

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.RawColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [RawColor(components)](#RawColor_components_1) | नया उदाहरण प्रारंभ करता है [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) क्लास का। |
| [RawColor(pixel_data_format, color_mode)](#RawColor_pixel_data_format_color_mode_2) | पिक्सेल डेटा फ़ॉर्मेट से पूर्वनिर्धारित रंग मोड का उपयोग करके [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) क्लास का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| color_mode | short | r/w | रंग के अनुसरण के लिए मोड। |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | r | रंग के घटकों को प्राप्त करता है। प्रत्येक घटक एक अलग चैनल है, और यदि आप कम लोकप्रिय<br/>            रंग योजना का उपयोग करते हैं, तो प्रत्येक चैनल को अलग से काम करना बेहतर है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_as_int()](#get_as_int__1) | यदि संभव हो तो रंग को int के रूप में प्राप्त करता है। |
| [get_as_long()](#get_as_long__2) | यदि संभव हो तो रंग को long के रूप में प्राप्त करता है। |
| [get_bit_depth()](#get_bit_depth__3) | Raw Color की बिट गहराई प्राप्त करता है। <br/>            उदाहरण के लिए ARGB रंग के लिए प्रत्येक चैनल/घटक में 8 बिट होने पर कुल 32 बिट होते हैं<br/>            पूर्ण ARGB रंग के लिए प्रत्येक चैनल/घटक में 16 बिट होने पर कुल 64 बिट होते हैं।<br/>            बिट गहराई चैनलों की बिट गहराइयों के योग से प्राप्त होती है। <br/>            यह संभव है यदि विभिन्न चैनलों की बिट गहराइयाँ अलग-अलग हों। |
| [get_color_mode_name()](#get_color_mode_name__4) | रंग मोड का नाम प्राप्त करता है। रंग मोड का नाम चैनलों/घटकों के नामों से संकलित होता है। |
| [set_as_int(value)](#set_as_int_value_5) | यदि संभव हो तो int तर्क से सभी चैनलों में डेटा सेट करता है। |
| [set_as_long(value)](#set_as_long_value_6) | यदि संभव हो तो int तर्क से सभी चैनलों में डेटा सेट करता है। |


### Constructor: RawColor(components) {#RawColor_components_1}


```
 RawColor(components) 
```

नया उदाहरण प्रारंभ करता है [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| components | [ColorComponent[]](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent) | कस्टम रंग घटक। |

### Constructor: RawColor(pixel_data_format, color_mode) {#RawColor_pixel_data_format_color_mode_2}


```
 RawColor(pixel_data_format, color_mode) 
```

पिक्सेल डेटा फ़ॉर्मेट से पूर्वनिर्धारित रंग मोड का उपयोग करके [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixel_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | पिक्सेल डेटा फ़ॉर्मेट। |
| color_mode | short | रंग के अनुसरण के लिए मोड। |

### Method: get_as_int() {#get_as_int__1}


```
 get_as_int() 
```

यदि संभव हो तो रंग को int के रूप में प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | Int में संग्रहीत चैनल डेटा |


### Method: get_as_long() {#get_as_long__2}


```
 get_as_long() 
```

यदि संभव हो तो रंग को long के रूप में प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| long | Int में संग्रहीत चैनल डेटा |


### Method: get_bit_depth() {#get_bit_depth__3}


```
 get_bit_depth() 
```

Raw Color की बिट गहराई प्राप्त करता है। <br/>            उदाहरण के लिए ARGB रंग के लिए प्रत्येक चैनल/घटक में 8 बिट होने पर कुल 32 बिट होते हैं<br/>            पूर्ण ARGB रंग के लिए प्रत्येक चैनल/घटक में 16 बिट होने पर कुल 64 बिट होते हैं।<br/>            बिट गहराई चैनलों की बिट गहराइयों के योग से प्राप्त होती है। <br/>            यह संभव है यदि विभिन्न चैनलों की बिट गहराइयाँ अलग-अलग हों।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | सभी चैनलों की बिट गहराइयों का योग |


### Method: get_color_mode_name() {#get_color_mode_name__4}


```
 get_color_mode_name() 
```

रंग मोड का नाम प्राप्त करता है। रंग मोड का नाम चैनलों/घटकों के नामों से संकलित होता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | रंग मोड नाम वाली स्ट्रिंग |


### Method: set_as_int(value) {#set_as_int_value_5}


```
 set_as_int(value) 
```

यदि संभव हो तो int तर्क से सभी चैनलों में डेटा सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | int | घटक डेटा रखने वाला int मान |

### Method: set_as_long(value) {#set_as_long_value_6}


```
 set_as_long(value) 
```

यदि संभव हो तो int तर्क से सभी चैनलों में डेटा सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| value | long | घटक डेटा रखने वाला int मान |


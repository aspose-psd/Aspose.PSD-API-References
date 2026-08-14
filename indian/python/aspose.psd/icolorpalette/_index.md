---
title: "IColorPalette क्लास"
type: docs
weight: 1710
url: /hi/python-net/aspose.psd/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32-बिट ARGB संरचनाओं की एक एरे प्राप्त करता है। |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) संरचनाओं की एक एरे प्राप्त करता है। |
| entries_count | int | r | एंट्रीज़ की गिनती प्राप्त करता है। |
| is_compact_palette | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि कॉम्पैक्ट पैलेट उपयोग किया गया है या नहीं। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है। |
| [get_color(index)](#get_color_index_2) | इंडेक्स द्वारा पैलेट रंग प्राप्त करता है। |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | निकटतम 32-बिट ARGB रंग का सूचकांक प्राप्त करता है। |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | निकटतम 32-बिट ARGB रंग का सूचकांक प्राप्त करता है। |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | int | 32-बिट ARGB पैलेट रंग सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | रंग पैलेट प्रविष्टि जो <paramref name="index" /> द्वारा निर्दिष्ट है। |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

इंडेक्स द्वारा पैलेट रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | int | पैलेट रंग सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | रंग पैलेट प्रविष्टि जो <paramref name="index" /> द्वारा निर्दिष्ट है। |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

निकटतम 32-बिट ARGB रंग का सूचकांक प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_32_color | int | 32-बिट ARGB रंग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | निकटतम रंग का सूचकांक। |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

निकटतम 32-बिट ARGB रंग का सूचकांक प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | निकटतम रंग का सूचकांक। |



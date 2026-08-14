---
title: "PsdColorPalette क्लास"
type: docs
weight: 1750
url: /hi/python-net/aspose.psd.fileformats.psd/psdcolorpalette/
---

**Summary:** The PSD color palette.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdColorPalette

**Inheritance:** IPsdColorPalette, IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PsdColorPalette(color_palette)](#PsdColorPalette_color_palette_1) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का। |
| [PsdColorPalette(color_palette, transparent_index)](#PsdColorPalette_color_palette_transparent_index_2) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का। |
| [PsdColorPalette(color_palette_argb_32_entries, is_compact_palette)](#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का। |
| [PsdColorPalette(color_palette_entries)](#PsdColorPalette_color_palette_entries_4) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है। |
| [PsdColorPalette(color_palette_entries, is_compact_palette)](#PsdColorPalette_color_palette_entries_is_compact_palette_5) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का। |
| [PsdColorPalette(color_palette_entries, transparent_index)](#PsdColorPalette_color_palette_entries_transparent_index_6) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है। |
| [PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette)](#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का। |
| [PsdColorPalette(raw_entries_data)](#PsdColorPalette_raw_entries_data_8) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है। |
| [PsdColorPalette(raw_entries_data, is_compact_palette)](#PsdColorPalette_raw_entries_data_is_compact_palette_9) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का। |
| [PsdColorPalette(raw_entries_data, transparent_index)](#PsdColorPalette_raw_entries_data_transparent_index_10) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है। |
| [PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette)](#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11) | नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32-बिट ARGB रंगों की एक एरे प्राप्त करता है। |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) संरचनाओं की एक एरे प्राप्त करता है। |
| entries_count | int | r | एंट्रीज़ की गिनती प्राप्त करता है। |
| has_transparent_color | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि पारदर्शी रंग मौजूद है या नहीं। |
| is_compact_palette | bool | r | पैलेट को कॉम्पैक्ट है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| raw_entries | byte | r | कच्चे रंग पैलेट एंट्री डेटा प्राप्त करता है। |
| raw_entries_count | int | r | कच्चे रंग पैलेट एंट्री की गिनती प्राप्त करता है। |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r | पारदर्शी रंग प्राप्त करता है। |
| transparent_index | short | r | पारदर्शी रंग का इंडेक्स प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | पैलेट की प्रतिलिपि बनाता है। |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | पैलेट की प्रतिलिपि बनाता है। |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है। |
| [get_color(index)](#get_color_index_4) | इंडेक्स द्वारा पैलेट रंग प्राप्त करता है। |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | निकटतम रंग का इंडेक्स प्राप्त करता है। |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | निकटतम रंग का इंडेक्स प्राप्त करता है। |


### Constructor: PsdColorPalette(color_palette) {#PsdColorPalette_color_palette_1}


```
 PsdColorPalette(color_palette) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट। |

### Constructor: PsdColorPalette(color_palette, transparent_index) {#PsdColorPalette_color_palette_transparent_index_2}


```
 PsdColorPalette(color_palette, transparent_index) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट। |
| transparent_index | short | पारदर्शी रंग सूचकांक। |

### Constructor: PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) {#PsdColorPalette_color_palette_argb_32_entries_is_compact_palette_3}


```
 PsdColorPalette(color_palette_argb_32_entries, is_compact_palette) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette_argb_32_entries | int | रंग पैलेट 32-बिट ARGB प्रविष्टियाँ। |
| is_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

### Constructor: PsdColorPalette(color_palette_entries) {#PsdColorPalette_color_palette_entries_4}


```
 PsdColorPalette(color_palette_entries) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | रंग पैलेट प्रविष्टियाँ। |

### Constructor: PsdColorPalette(color_palette_entries, is_compact_palette) {#PsdColorPalette_color_palette_entries_is_compact_palette_5}


```
 PsdColorPalette(color_palette_entries, is_compact_palette) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | रंग पैलेट प्रविष्टियाँ। |
| is_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index) {#PsdColorPalette_color_palette_entries_transparent_index_6}


```
 PsdColorPalette(color_palette_entries, transparent_index) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | रंग पैलेट प्रविष्टियाँ। |
| transparent_index | short | पारदर्शी रंग सूचकांक। |

### Constructor: PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) {#PsdColorPalette_color_palette_entries_transparent_index_use_compact_palette_7}


```
 PsdColorPalette(color_palette_entries, transparent_index, use_compact_palette) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette_entries | [Color[]](/psd/python-net/aspose.psd/color) | रंग पैलेट प्रविष्टियाँ। |
| transparent_index | short | पारदर्शी रंग सूचकांक। |
| use_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

### Constructor: PsdColorPalette(raw_entries_data) {#PsdColorPalette_raw_entries_data_8}


```
 PsdColorPalette(raw_entries_data) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raw_entries_data | byte | कच्ची प्रविष्टियों का डेटा। |

### Constructor: PsdColorPalette(raw_entries_data, is_compact_palette) {#PsdColorPalette_raw_entries_data_is_compact_palette_9}


```
 PsdColorPalette(raw_entries_data, is_compact_palette) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raw_entries_data | byte | कच्ची प्रविष्टियों का डेटा। |
| is_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index) {#PsdColorPalette_raw_entries_data_transparent_index_10}


```
 PsdColorPalette(raw_entries_data, transparent_index) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का और IsCompactPalette false है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raw_entries_data | byte | कच्ची प्रविष्टियों का डेटा। |
| transparent_index | short | पारदर्शी रंग सूचकांक। नोट: यह सूचकांक कच्ची प्रविष्टियों का सूचकांक नहीं है, बल्कि परिवर्तित रंग सरणी के लिए है। |

### Constructor: PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) {#PsdColorPalette_raw_entries_data_transparent_index_use_compact_palette_11}


```
 PsdColorPalette(raw_entries_data, transparent_index, use_compact_palette) 
```

नया इंस्टेंस प्रारंभ करता है [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raw_entries_data | byte | कच्ची प्रविष्टियों का डेटा। |
| transparent_index | short | पारदर्शी रंग सूचकांक। नोट: यह सूचकांक कच्ची प्रविष्टियों का सूचकांक नहीं है, बल्कि परिवर्तित रंग सरणी के लिए है। |
| use_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

पैलेट की प्रतिलिपि बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | नया बनाया गया और कॉपी किया गया पैलेट, या यदि नल पैलेट पास किया गया हो तो नल। |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

पैलेट की प्रतिलिपि बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट। |
| use_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PsdColorPalette](/psd/python-net/aspose.psd.fileformats.psd/psdcolorpalette) | नया बनाया गया और कॉपी किया गया पैलेट, या यदि नल पैलेट पास किया गया हो तो नल। |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_3}


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


### Method: get_color(index) {#get_color_index_4}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_5}


```
 get_nearest_color_index(argb_32_color) 
```

निकटतम रंग का इंडेक्स प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_32_color | int | 32-बिट ARGB रंग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | निकटतम रंग का सूचकांक। |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_6}


```
 get_nearest_color_index(color) 
```

निकटतम रंग का इंडेक्स प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | निकटतम रंग का सूचकांक। |



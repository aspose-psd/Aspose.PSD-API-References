---
title: "ColorPalette Class"
type: docs
weight: 800
url: /hi/python-net/aspose.psd/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPalette

**Inheritance:** IColorPalette

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है और IsCompactPalette गलत है। |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [ColorPalette(entries)](#ColorPalette_entries_3) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है और IsCompactPalette गलत है। |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| argb_32_entries | int | r | 32-बिट ARGB संरचनाओं की एक एरे प्राप्त करता है। |
| entries | [Color[]](/psd/python-net/aspose.psd/color) | r | [Color](/psd/python-net/aspose.psd/color/) संरचनाओं की एक एरे प्राप्त करता है। |
| entries_count | int | r | एंट्रीज़ की गिनती प्राप्त करता है। |
| is_compact_palette | bool | r | कम्पैक्ट पैलेट उपयोग किया जाता है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | पैलेट की प्रतिलिपि बनाता है। |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | पैलेट की प्रतिलिपि बनाता है। |
| [get_argb_32_color(index)](#get_argb_32_color_index_3) | इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है। |
| [get_color(index)](#get_color_index_4) | इंडेक्स द्वारा पैलेट रंग प्राप्त करता है। |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_5) | निकटतम रंग का इंडेक्स प्राप्त करता है। |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_6) | निकटतम रंग का इंडेक्स प्राप्त करता है। |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है और IsCompactPalette गलत है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_32_entries | int | 32-बिट ARGB रंग पैलेट प्रविष्टियाँ। |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_32_entries | int | 32-बिट ARGB रंग पैलेट प्रविष्टियाँ। |
| is_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है और IsCompactPalette गलत है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

[ColorPalette](/psd/python-net/aspose.psd/colorpalette/) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| entries | [Color[]](/psd/python-net/aspose.psd/color) |  |
| is_compact_palette | bool | यह दर्शाता है कि पैलेट कॉम्पैक्ट है या नहीं। |

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
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | नया बनाया गया और कॉपी किया गया पैलेट, या यदि नल पैलेट पास किया गया हो तो नल। |


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
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | नया बनाया गया और कॉपी किया गया पैलेट, या यदि नल पैलेट पास किया गया हो तो नल। |


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



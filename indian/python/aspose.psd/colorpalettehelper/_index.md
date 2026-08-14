---
title: "ColorPaletteHelper क्लास"
type: docs
weight: 810
url: /hi/python-net/aspose.psd/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorPaletteHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | 4 बिट रंग पैलेट बनाता है। |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | 4 बिट ग्रेस्केल पैलेट बनाता है। |
| [create_8_bit()](#create_8_bit__3) | 8 बिट रंग पैलेट बनाता है। |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | 8 बिट ग्रेस्केल पैलेट बनाता है। |
| [create_monochrome()](#create_monochrome__5) | केवल 2 रंगों वाला मोनोक्रोम रंग पैलेट बनाता है। |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_6) | रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा। |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7) | रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा। |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_8) | रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा। |
| [get_downscale_palette(image)](#get_downscale_palette_image_9) | प्रारंभिक इमेज रंग मानों के ऊपरी बिट्स से निर्मित 256 रंग पैलेट प्राप्त करें। |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_10) | समान 256 रंग पैलेट प्राप्त करें। |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_11) | निर्धारित करता है कि निर्दिष्ट पैलेट में पारदर्शी रंग हैं या नहीं। |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

4 बिट रंग पैलेट बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4 बिट रंग पैलेट। |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

4 बिट ग्रेस्केल पैलेट बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| min_is_white | bool | यदि सेट किया गया है <c>true</c> तो पैलेट सफेद रंग से शुरू होता है, अन्यथा यह काले रंग से शुरू होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 4 बिट ग्रेस्केल पैलेट। |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

8 बिट रंग पैलेट बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 बिट रंग पैलेट। |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

8 बिट ग्रेस्केल पैलेट बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| min_is_white | bool | यदि सेट किया गया है <c>true</c> तो पैलेट सफेद रंग से शुरू होता है, अन्यथा यह काले रंग से शुरू होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 8 बिट ग्रेस्केल पैलेट। |


### Method: create_monochrome()  [static] {#create_monochrome__5}


```
 create_monochrome() 
```

केवल 2 रंगों वाला मोनोक्रोम रंग पैलेट बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | एकरंगीय छवियों के लिए रंग पैलेट। |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_6}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | रास्टर इमेज। |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य छवि की सीमाएँ। |
| entries_count | int | वांछित प्रविष्टियों की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट जो <paramref name="image" /> से सबसे अधिक बार आने वाले रंगों से शुरू होता है और इसमें <paramref name="entriesCount" /> प्रविष्टियाँ होती हैं। |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_7}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | रास्टर इमेज। |
| dest_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य छवि की सीमाएँ। |
| entries_count | int | वांछित प्रविष्टियों की संख्या। |
| use_image_palette | bool | यदि सेट किया गया है, तो यह उपलब्ध होने पर अपना स्वयं का इमेज पैलेट उपयोग करेगा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट जो <paramref name="image" /> से सबसे अधिक बार आने वाले रंगों से शुरू होता है और इसमें <paramref name="entriesCount" /> प्रविष्टियाँ होती हैं। |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_8}


```
 get_close_image_palette(image, entries_count) 
```

रास्टर इमेज से रंग पैलेट प्राप्त करता है (इमेज को पैलेटाइज़ करता है) यदि इमेज में पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | रास्टर इमेज। |
| entries_count | int | वांछित प्रविष्टियों की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट जो <paramref name="image" /> से सबसे अधिक बार आने वाले रंगों से शुरू होता है और इसमें <paramref name="entriesCount" /> प्रविष्टियाँ होती हैं। |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_9}


```
 get_downscale_palette(image) 
```

प्रारंभिक इमेज रंग मानों के ऊपरी बिट्स से निर्मित 256 रंग पैलेट प्राप्त करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | छवि। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | यह [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_10}


```
 get_uniform_color_palette(image) 
```

समान 256 रंग पैलेट प्राप्त करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | छवि। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette) | यह [ColorPalette](/psd/python-net/aspose.psd/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_11}


```
 has_transparent_colors(palette) 
```

निर्धारित करता है कि निर्दिष्ट पैलेट में पारदर्शी रंग हैं या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | पैलेट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि निर्दिष्ट पैलेट में पारदर्शी रंग हैं; अन्यथा, <c>false</c>। |



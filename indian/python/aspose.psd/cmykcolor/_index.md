---
title: "CmykColor क्लास"
type: docs
weight: 630
url: /hi/python-net/aspose.psd/cmykcolor/
---

**Summary:** The CMYK color of pixel.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColor

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [CmykColor()](#CmykColor__1) | CmykColor क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| c | byte | r | इस [Color](/psd/python-net/aspose.psd/color/) संरचना का सियान घटक मान प्राप्त करता है। |
| empty [static] | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | r | खाली प्राप्त करता है। |
| is_empty | bool | r | इस [Color](/psd/python-net/aspose.psd/color/) संरचना का अनइनिशियलाइज़्ड है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| k | byte | r | इस [Color](/psd/python-net/aspose.psd/color/) संरचना का काला घटक मान प्राप्त करता है। |
| m | byte | r | इस [Color](/psd/python-net/aspose.psd/color/) संरचना का मैजेंटा घटक मान प्राप्त करता है। |
| y | byte | r | इस [Color](/psd/python-net/aspose.psd/color/) संरचना का पीला घटक मान प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [from_params(cyan, magenta, yellow, black)](#from_params_cyan_magenta_yellow_black_1) | एक 32-बिट सियान, मैजेंटा, पीला और काला मानों से एक [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) संरचना बनाता है।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_2) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से 32-बिट ARGB Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_3) | 32-बिट ARGB रंग से CMYKColor में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_4) | 32-बिट ARGB रंग से CMYKColor में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_color(cmyk_pixel)](#to_color_cmyk_pixel_5) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_color(cmyk_pixels)](#to_color_cmyk_pixels_6) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_color_icc(cmyk_pixel)](#to_color_icc_cmyk_pixel_7) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) का उपयोग करें। |
| [to_color_icc(cmyk_pixels)](#to_color_icc_cmyk_pixels_9) | डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें। |
| [to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10) | icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) का उपयोग करें। |
| [to_value()](#to_value__11) | to मान। |


### Constructor: CmykColor() {#CmykColor__1}


```
 CmykColor() 
```

CmykColor क्लास का नया उदाहरण प्रारंभ करता है

### Method: from_params(cyan, magenta, yellow, black)  [static] {#from_params_cyan_magenta_yellow_black_1}


```
 from_params(cyan, magenta, yellow, black) 
```

एक 32-बिट सियान, मैजेंटा, पीला और काला मानों से एक [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) संरचना बनाता है।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.from_components(cyan, magenta, yellow, black)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| सियान | int | सियान घटक। मान्य मान 0 से 255 तक हैं। |
| मैजेंटा | int | मैजेंटा घटक। मान्य मान 0 से 255 तक हैं। |
| पीला | int | पीला घटक। मान्य मान 0 से 255 तक हैं। |
| काला | int | काला घटक। मान्य मान 0 से 255 तक हैं। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | यह [CmykColor](/psd/python-net/aspose.psd/cmykcolor/)। |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_2}


```
 to_argb32(cmyk_pixels) 
```

डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से 32-बिट ARGB Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb32(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK स्वरूप में CMYKColor प्रकार के पिक्सेल। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | 32-बिट ARGB रंग की सरणी। |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_3}


```
 to_cmyk(argb_pixel) 
```

32-बिट ARGB रंग से CMYKColor में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor) | यह <see cref="T:Aspose:PSD:CmykColor[]" />। |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_4}


```
 to_cmyk(argb_pixels) 
```

32-बिट ARGB रंग से CMYKColor में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_cmyk(argb_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_pixels | int | 32-बिट ARGB स्वरूप के पिक्सेल। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | यह <see cref="T:Aspose:PSD:CmykColor[]" />। |


### Method: to_color(cmyk_pixel)  [static] {#to_color_cmyk_pixel_5}


```
 to_color(cmyk_pixel) 
```

डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB रंगों की सरणी। |


### Method: to_color(cmyk_pixels)  [static] {#to_color_cmyk_pixels_6}


```
 to_color(cmyk_pixels) 
```

डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK स्वरूप में CMYKColor प्रकार के पिक्सेल। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB रंगों की सरणी। |


### Method: to_color_icc(cmyk_pixel)  [static] {#to_color_icc_cmyk_pixel_7}


```
 to_color_icc(cmyk_pixel) 
```

डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | यह [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_8}


```
 to_color_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixel | [CmykColor](/psd/python-net/aspose.psd/cmykcolor) |  |
| cmyk_icc_stream | _io.BufferedRandom | icc cmyk प्रोफ़ाइल युक्त स्ट्रीम। |
| rgb_icc_stream | _io.BufferedRandom | icc rgb प्रोफ़ाइल युक्त स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | यह [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels)  [static] {#to_color_icc_cmyk_pixels_9}


```
 to_color_icc(cmyk_pixels) 
```

डिफ़ॉल्ट प्रोफ़ाइल के साथ icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी [CmykColorHelper.to_argb_icc(cmyk_pixels)](/psd/python-net/aspose.psd/cmykcolorhelper/) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK स्वरूप में CMYKColor प्रकार के पिक्सेल। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | यह [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_color_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_color_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

icc रूपांतरण का उपयोग करके CMYKColor से Color में रूपांतरण।<br/>            यह विधि अप्रचलित है। कृपया अधिक प्रभावी Aspose.PSD.CmykColorHelper.ToArgbIcc(int[],_io.BufferedRandom,_io.BufferedRandom) का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | CMYK स्वरूप में CMYKColor प्रकार के पिक्सेल। |
| cmyk_icc_stream | _io.BufferedRandom | icc cmyk प्रोफ़ाइल युक्त स्ट्रीम। |
| rgb_icc_stream | _io.BufferedRandom | icc rgb प्रोफ़ाइल युक्त स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | यह [Color[]](/psd/python-net/aspose.psd/color/). |


### Method: to_value() {#to_value__11}


```
 to_value() 
```

to मान।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| long | int। |



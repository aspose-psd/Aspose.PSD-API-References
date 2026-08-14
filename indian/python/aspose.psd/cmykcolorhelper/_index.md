---
title: "CmykColorHelper क्लास"
type: docs
weight: 640
url: /hi/python-net/aspose.psd/cmykcolorhelper/
---

**Summary:** Helper methods to work with CMYK color presented as a signed 32-bit integer value.<br/>            Provides the similar API as the [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.<br/>            It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields.<br/>            Please prefer to use static methods of this class when possible instead of the deprecated<br/>            [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) struct.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CmykColorHelper

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [from_components(cyan, magenta, yellow, black)](#from_components_cyan_magenta_yellow_black_1) | 32-बिट सियान, मैजेंटा, येलो और ब्लैक मानों से CMYK बनाता है। |
| [get_c(cmyk)](#get_c_cmyk_2) | सियान घटक मान प्राप्त करता है। |
| [get_k(cmyk)](#get_k_cmyk_3) | ब्लैक घटक मान प्राप्त करता है। |
| [get_m(cmyk)](#get_m_cmyk_4) | मैजेंटा घटक मान प्राप्त करता है। |
| [get_y(cmyk)](#get_y_cmyk_5) | येलो घटक मान प्राप्त करता है। |
| [to_argb(cmyk_pixel)](#to_argb_cmyk_pixel_6) | CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [to_argb(cmyk_pixels)](#to_argb_cmyk_pixels_7) | CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [to_argb32(cmyk_pixels)](#to_argb32_cmyk_pixels_8) | CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [to_argb_icc(cmyk_pixel)](#to_argb_icc_cmyk_pixel_9) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10) | कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [to_argb_icc(cmyk_pixels)](#to_argb_icc_cmyk_pixels_11) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)](#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12) | कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण। |
| [to_cmyk(argb_pixel)](#to_cmyk_argb_pixel_13) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk(argb_pixels)](#to_cmyk_argb_pixels_14) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk(pixel)](#to_cmyk_pixel_15) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk(pixels)](#to_cmyk_pixels_16) | ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk_bytes(argb_pixels, start_index, length)](#to_cmyk_bytes_argb_pixels_start_index_length_17) | RGB को CMYK में परिवर्तित करता है। |
| [to_cmyk_icc(pixel)](#to_cmyk_icc_pixel_18) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19) | कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk_icc(pixels)](#to_cmyk_icc_pixels_20) | डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21) | कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण। |
| [to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)](#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22) | कस्टम ICC प्रोफ़ाइलों का उपयोग करके RGB को CMYK में परिवर्तित करता है। |


### Method: from_components(cyan, magenta, yellow, black)  [static] {#from_components_cyan_magenta_yellow_black_1}


```
 from_components(cyan, magenta, yellow, black) 
```

32-बिट सियान, मैजेंटा, येलो और ब्लैक मानों से CMYK बनाता है।

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
| int | CMYK रंग को 32-बिट पूर्णांक मान के रूप में प्रस्तुत किया गया है। |


### Method: get_c(cmyk)  [static] {#get_c_cmyk_2}


```
 get_c(cmyk) 
```

सियान घटक मान प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk | int | CMYK रंग को 32-बिट पूर्णांक मान के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | सियान घटक मान। |


### Method: get_k(cmyk)  [static] {#get_k_cmyk_3}


```
 get_k(cmyk) 
```

ब्लैक घटक मान प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk | int | CMYK रंग को 32-बिट पूर्णांक मान के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | काले घटक मान। |


### Method: get_m(cmyk)  [static] {#get_m_cmyk_4}


```
 get_m(cmyk) 
```

मैजेंटा घटक मान प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk | int | CMYK रंग को 32-बिट पूर्णांक मान के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | मैजेंटा घटक मान। |


### Method: get_y(cmyk)  [static] {#get_y_cmyk_5}


```
 get_y(cmyk) 
```

येलो घटक मान प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk | int | CMYK रंग को 32-बिट पूर्णांक मान के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | पीला घटक मान। |


### Method: to_argb(cmyk_pixel)  [static] {#to_argb_cmyk_pixel_6}


```
 to_argb(cmyk_pixel) 
```

CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB रंग। |


### Method: to_argb(cmyk_pixels)  [static] {#to_argb_cmyk_pixels_7}


```
 to_argb(cmyk_pixels) 
```

CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB रंग। |


### Method: to_argb32(cmyk_pixels)  [static] {#to_argb32_cmyk_pixels_8}


```
 to_argb32(cmyk_pixels) 
```

CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | ARGB रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_argb_icc(cmyk_pixel)  [static] {#to_argb_icc_cmyk_pixel_9}


```
 to_argb_icc(cmyk_pixel) 
```

डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixel | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB रंग। |


### Method: to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixel_cmyk_icc_stream_rgb_icc_stream_10}


```
 to_argb_icc(cmyk_pixel, cmyk_icc_stream, rgb_icc_stream) 
```

कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixel | int |  |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | ARGB रंग। |


### Method: to_argb_icc(cmyk_pixels)  [static] {#to_argb_icc_cmyk_pixels_11}


```
 to_argb_icc(cmyk_pixels) 
```

डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | int | CMYK पिक्सेल को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB रंग। |


### Method: to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream)  [static] {#to_argb_icc_cmyk_pixels_cmyk_icc_stream_rgb_icc_stream_12}


```
 to_argb_icc(cmyk_pixels, cmyk_icc_stream, rgb_icc_stream) 
```

कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके CMYK रंगों से ARGB रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cmyk_pixels | int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | ARGB रंग। |


### Method: to_cmyk(argb_pixel)  [static] {#to_cmyk_argb_pixel_13}


```
 to_cmyk(argb_pixel) 
```

ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_pixel | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk(argb_pixels)  [static] {#to_cmyk_argb_pixels_14}


```
 to_cmyk(argb_pixels) 
```

ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_pixels | int | ARGB रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk(pixel)  [static] {#to_cmyk_pixel_15}


```
 to_cmyk(pixel) 
```

ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk(pixels)  [static] {#to_cmyk_pixels_16}


```
 to_cmyk(pixels) 
```

ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk_bytes(argb_pixels, start_index, length)  [static] {#to_cmyk_bytes_argb_pixels_start_index_length_17}


```
 to_cmyk_bytes(argb_pixels, start_index, length) 
```

RGB को CMYK में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| argb_pixels | int | RGB रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |
| start_index | int | RGB रंग का प्रारंभिक सूचकांक। |
| लंबाई | int | परिवर्तित करने के लिए RGB पिक्सेल की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | CMYK रंगों को बाइट ऐरे के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk_icc(pixel)  [static] {#to_cmyk_icc_pixel_18}


```
 to_cmyk_icc(pixel) 
```

डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixel_rgb_icc_stream_cmyk_icc_stream_19}


```
 to_cmyk_icc(pixel, rgb_icc_stream, cmyk_icc_stream) 
```

कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixel | [Color](/psd/python-net/aspose.psd/color) |  |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk_icc(pixels)  [static] {#to_cmyk_icc_pixels_20}


```
 to_cmyk_icc(pixels) 
```

डिफ़ॉल्ट प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB रंग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_pixels_rgb_icc_stream_cmyk_icc_stream_21}


```
 to_cmyk_icc(pixels, rgb_icc_stream, cmyk_icc_stream) 
```

कस्टम प्रोफ़ाइलों के साथ Icc रूपांतरण का उपयोग करके ARGB रंगों से CMYK रंगों में रूपांतरण।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | ARGB रंग। |
| rgb_icc_stream | _io.BufferedRandom | RGB Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |
| cmyk_icc_stream | _io.BufferedRandom | CMYK Icc प्रोफ़ाइल को शामिल करने वाली स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | CMYK रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |


### Method: to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream)  [static] {#to_cmyk_icc_bytes_pixels_start_index_length_rgb_icc_stream_cmyk_icc_stream_22}


```
 to_cmyk_icc_bytes(pixels, start_index, length, rgb_icc_stream, cmyk_icc_stream) 
```

कस्टम ICC प्रोफ़ाइलों का उपयोग करके RGB को CMYK में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pixels | int | RGB रंगों को 32-बिट पूर्णांक मानों के रूप में प्रस्तुत किया गया है। |
| start_index | int | RGB रंग का प्रारंभिक सूचकांक। |
| लंबाई | int | परिवर्तित करने के लिए RGB पिक्सेल की संख्या। |
| rgb_icc_stream | _io.BufferedRandom | RGB प्रोफ़ाइल स्ट्रीम। |
| cmyk_icc_stream | _io.BufferedRandom | CMYK प्रोफ़ाइल स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | CMYK रंगों को बाइट ऐरे के रूप में प्रस्तुत किया गया है। |



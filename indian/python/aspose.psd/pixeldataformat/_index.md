---
title: "PixelDataFormat क्लास"
type: docs
weight: 3450
url: /hi/python-net/aspose.psd/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PixelDataFormat

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| बिट्स_प्रति_पिक्सेल | int | r | पिक्सेल प्रति बिट प्राप्त करता है। |
| कैप्शन | string | r | पिक्सेल डेटा फ़ॉर्मेट का कैप्शन प्राप्त करता है। |
| channel_bits | int | r | प्रत्येक चैनल के लिए बिट्स की गिनती प्राप्त करता है। |
| चैनल्स_गणना | int | r | चैनलों की गिनती प्राप्त करता है। |
| cmyk [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 32 बिट्स के लिए परिभाषित है, जिसमें सियान, मैजेंटा, येल्लो और ब्लैक के प्रत्येक के लिए 8 बिट्स होते हैं। |
| cmyka [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | acmyk प्राप्त करता है। |
| grayscale [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 8 बिट्स के लिए परिभाषित है, जिसमें 0‑255 अंतराल में ग्रेस्केल तीव्रता को दर्शाने के लिए 8 बिट्स होते हैं। |
| grayscale_alpha [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 16 बिट्स के लिए परिभाषित है, जिसमें 0‑255 अंतराल में ग्रेस्केल तीव्रता को दर्शाने के लिए 8 बिट्स और अतिरिक्त 8‑बिट अल्फा घटक होते हैं। |
| pixel_format | [PixelFormat](/psd/python-net/aspose.psd/pixelformat) | r | पिक्सेल फ़ॉर्मेट प्राप्त करता है। |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 16 बिट्स के लिए परिभाषित है, जिसमें लाल, हरा और नीला प्रत्येक के लिए 5 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 16 बिट्स के लिए परिभाषित है, जिसमें लाल के लिए 5 बिट्स, हरे के लिए 6 बिट्स और नीले के लिए 5 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| rgb_24_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 24 बिट्स के लिए परिभाषित है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| rgb_24_bpp_png [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 24 बिट्स के लिए परिभाषित है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| rgb_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 32 बिट्स के लिए परिभाषित है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं। |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति रंग 1 बिट के इंडेक्स्ड के लिए परिभाषित है।<br/>            इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा स्टोरेज और पुनः प्राप्ति को सक्षम करना है जहाँ भी रंग पैलेट उपयोग किया जाता है।<br/>            सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट में या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो 2 बिट प्रति रंग के इंडेक्स्ड के लिए परिभाषित है।<br/>            इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा संग्रह और पुनर्प्राप्ति को सक्षम करना है जहाँ भी रंग पैलेट का उपयोग किया जाता है।<br/>            सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो 4 बिट प्रति रंग के इंडेक्स्ड के लिए परिभाषित है।<br/>            इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा संग्रह और पुनर्प्राप्ति को सक्षम करना है जहाँ भी रंग पैलेट का उपयोग किया जाता है।<br/>            सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो 8 बिट प्रति रंग के इंडेक्स्ड के लिए परिभाषित है।<br/>            इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा संग्रह और पुनर्प्राप्ति को सक्षम करना है जहाँ भी रंग पैलेट का उपयोग किया जाता है।<br/>            सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है। |
| rgba_32_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो प्रति पिक्सेल 32 बिट्स के लिए परिभाषित है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं। |
| rgba_64_bpp [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो 64 बिट प्रति पिक्सेल के लिए परिभाषित है, जिसमें अल्फा, लाल, हरा और नीले के प्रत्येक के लिए 16 बिट होते हैं। |
| y_cb_cr [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो 24 बिट प्रति पिक्सेल के लिए परिभाषित है, जिसमें ल्यूमा, ब्लू-डिफरेंस और रेड-डिफरेंस क्रोमा घटकों के प्रत्येक के लिए 8 बिट होते हैं। |
| ycck [static] | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | प्राप्त करता है [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) जो 32 बिट प्रति पिक्सेल के लिए परिभाषित है, जिसमें ल्यूमा, ब्लू-डिफरेंस, रेड-डिफरेंस और ब्लैक क्रोमा घटकों के प्रत्येक के लिए 8 बिट होते हैं। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA रंग प्राप्त करता है। |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA रंग प्राप्त करता है। |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CIE Lab रंग प्राप्त करता है। |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYK रंग प्राप्त करता है। |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYK रंग प्राप्त करता है। |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYKA रंग प्राप्त करता है। |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | निर्दिष्ट नमूना बिट्स की संख्या के साथ ग्रेस्केल रंग प्राप्त करता है। |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | निर्दिष्ट नमूना बिट्स की संख्या के साथ GrayscaleAlpha रंग प्राप्त करता है। |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | निर्दिष्ट नमूना बिट्स की संख्या के साथ GrayscaleAlpha रंग प्राप्त करता है। |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGB रंग प्राप्त करता है। |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGB रंग प्राप्त करता है। |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA इंडेक्स्ड रंग प्राप्त करता है। |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGBA रंग प्राप्त करता है। |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | निर्दिष्ट नमूना बिट्स की संख्या के साथ RGBA रंग प्राप्त करता है। |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | निर्दिष्ट नमूना बिट्स की संख्या के साथ YCbCr रंग प्राप्त करता है। |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | निर्दिष्ट नमूना बिट्स की संख्या के साथ YCbCr रंग प्राप्त करता है। |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | निर्दिष्ट नमूना बिट्स की संख्या के साथ YCCK रंग प्राप्त करता है। |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA रंग। |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA रंग। |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ CIE Lab रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_l | int | L चैनल प्रति बिट की संख्या। |
| bits_per_a | int | A चैनल प्रति बिट की संख्या। |
| bits_per_b | int | B चैनल प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CIE Lab रंग। |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYK रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan चैनल के प्रति बिट्स की संख्या। |
| bits_per_magenta_channel | int | Magenta चैनल के प्रति बिट्स की संख्या। |
| bits_per_yellow_channel | int | Yellow चैनल के प्रति बिट्स की संख्या। |
| bits_per_key_channel | int | Key चैनल के प्रति बिट्स की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK रंग। |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYK रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK रंग। |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ CMYKA रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_cyan_channel | int | Cyan चैनल के प्रति बिट्स की संख्या। |
| bits_per_magenta_channel | int | Magenta चैनल के प्रति बिट्स की संख्या। |
| bits_per_yellow_channel | int | Yellow चैनल के प्रति बिट्स की संख्या। |
| bits_per_key_channel | int | Key चैनल के प्रति बिट्स की संख्या। |
| bits_per_alpha_channel | int | Alpha चैनल के प्रति बिट्स की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | CMYK रंग। |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ ग्रेस्केल रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Grayscale रंग। |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ GrayscaleAlpha रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha रंग। |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ GrayscaleAlpha रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |
| alpha_channel_bits | int | Alpha चैनल में सैंपल के प्रति बिट्स की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | GrayscaleAlpha रंग। |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ RGB रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_red_channel | int | Red चैनल के प्रति बिट्स की संख्या। |
| bits_per_green_channel | int | Green चैनल के प्रति बिट्स की संख्या। |
| bits_per_blue_channel | int | Blue चैनल के प्रति बिट्स की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB रंग। |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ RGB रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGB रंग। |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ BGRA इंडेक्स्ड रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | BGRA रंग। |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ RGBA रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_red_channel | int | Red चैनल के प्रति बिट्स की संख्या। |
| bits_per_green_channel | int | Green चैनल के प्रति बिट्स की संख्या। |
| bits_per_blue_channel | int | Blue चैनल के प्रति बिट्स की संख्या। |
| bits_per_alpha_channel | int | Alpha चैनल के प्रति बिट्स की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA रंग। |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ RGBA रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | RGBA रंग। |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ YCbCr रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr रंग। |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ YCbCr रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_y | int | Y चैनल प्रति बिट्स की संख्या। |
| bits_per_cb | int | Cb चैनल प्रति बिट्स की संख्या। |
| bits_per_cr | int | Cr चैनल प्रति बिट्स की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCbCr रंग। |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

निर्दिष्ट नमूना बिट्स की संख्या के साथ YCCK रंग प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bits_per_sample | int | नमूना प्रति बिट की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | YCCK रंग। |



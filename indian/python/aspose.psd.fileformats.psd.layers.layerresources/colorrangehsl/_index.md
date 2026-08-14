---
title: "ColorRangeHsl क्लास"
type: docs
weight: 180
url: /hi/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | नए [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है। |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | नए [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| hue | short | r/w | hue को प्राप्त करता है या सेट करता है। |
| left_border | short | r/w | बाएँ सीमा को प्राप्त करता है या सेट करता है। |
| lightness | short | r/w | lightness को प्राप्त करता है या सेट करता है। |
| most_left_border | short | r/w | सबसे बाएँ सीमा को प्राप्त करता है या सेट करता है। |
| most_right_border | short | r/w | सबसे दाएँ सीमा को प्राप्त करता है या सेट करता है। |
| right_border | short | r/w | दाएँ सीमा को प्राप्त करता है या सेट करता है। |
| संतृप्ति | short | r/w | संतृप्ति प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | रेंज गुणांक को प्राप्त करता है। |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | निर्धारित करता है कि क्या ह्यू बड़े रेंज में है। |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | निर्धारित करता है कि ह्यू छोटे रेंज में है या नहीं। |
| [save(stream_container)](#save_stream_container_4) | डेटा को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

नए [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

नए [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | रंग रेंज डेटा। |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

रेंज गुणांक को प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| hue | डबल | ह्यू मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| डबल | सैचुरेशन रेंज गुणांक। |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

निर्धारित करता है कि क्या ह्यू बड़े रेंज में है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| hue | डबल | ह्यू मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि ह्यू बड़े रेंज में है; अन्यथा, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

निर्धारित करता है कि ह्यू छोटे रेंज में है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| hue | डबल | ह्यू मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि hue छोटे रेंज में हो; अन्यथा, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

डेटा को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |


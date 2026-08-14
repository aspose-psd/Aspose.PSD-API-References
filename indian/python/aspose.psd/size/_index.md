---
title: "Size क्लास"
type: docs
weight: 4080
url: /hi/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Size()](#Size__1) | Size क्लास का नया उदाहरण प्रारंभ करता है |
| [Size(point)](#Size_point_2) | निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) से [Size](/psd/python-net/aspose.psd/size/) संरचना का नया उदाहरण प्रारंभ करता है। |
| [Size(width, height)](#Size_width_height_3) | निर्दिष्ट आयामों से [Size](/psd/python-net/aspose.psd/size/) संरचना का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | ऐसा नया [Size](/psd/python-net/aspose.psd/size/) संरचना प्राप्त करता है जिसमें [Size.width](/psd/python-net/aspose.psd/size/) और [Size.height](/psd/python-net/aspose.psd/size/) मान शून्य पर सेट हों। |
| height | int | r/w | इस [Size](/psd/python-net/aspose.psd/size/) का लंबवत घटक प्राप्त करता है या सेट करता है। |
| is_empty | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह [Size](/psd/python-net/aspose.psd/size/) की चौड़ाई और ऊँचाई 0 है या नहीं। |
| width | int | r/w | इस [Size](/psd/python-net/aspose.psd/size/) का क्षैतिज घटक प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | एक [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई में जोड़ता है। |
| [ceiling(size)](#ceiling_size_2) | निर्दिष्ट [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना को [Size](/psd/python-net/aspose.psd/size/) संरचना में परिवर्तित करता है, [Size](/psd/python-net/aspose.psd/size/) संरचना के मानों को अगले बड़े पूर्णांक मान तक गोल करके। |
| [round(size)](#round_size_3) | निर्दिष्ट [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना को निकटतम पूर्णांक मानों तक गोल करके एक [Size](/psd/python-net/aspose.psd/size/) संरचना में परिवर्तित करता है। |
| [subtract(size1, size2)](#subtract_size1_size2_4) | एक [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई से घटाता है। |
| [truncate(size)](#truncate_size_5) | निर्दिष्ट [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना को अगले निचले पूर्णांक मान तक ट्रंकेट करके एक [Size](/psd/python-net/aspose.psd/size/) संरचना में परिवर्तित करता है। |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Size क्लास का नया उदाहरण प्रारंभ करता है

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) से [Size](/psd/python-net/aspose.psd/size/) संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | वह [Point](/psd/python-net/aspose.psd/point/) जिससे यह [Size](/psd/python-net/aspose.psd/size/) आरंभ किया जाता है। |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

निर्दिष्ट आयामों से [Size](/psd/python-net/aspose.psd/size/) संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | int | नए [Size](/psd/python-net/aspose.psd/size/) का चौड़ाई घटक। |
| height | int | नए [Size](/psd/python-net/aspose.psd/size/) का ऊँचाई घटक। |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

एक [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई में जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | पहला जोड़ने के लिए [Size](/psd/python-net/aspose.psd/size/)। |
| size2 | [Size](/psd/python-net/aspose.psd/size) | दूसरा जोड़ने के लिए [Size](/psd/python-net/aspose.psd/size/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | एक [Size](/psd/python-net/aspose.psd/size/) संरचना जो जोड़ ऑपरेशन का परिणाम है। |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

निर्दिष्ट [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना को [Size](/psd/python-net/aspose.psd/size/) संरचना में परिवर्तित करता है, [Size](/psd/python-net/aspose.psd/size/) संरचना के मानों को अगले बड़े पूर्णांक मान तक गोल करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | परिवर्तित करने के लिए [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | वह [Size](/psd/python-net/aspose.psd/size/) संरचना जिसे यह विधि परिवर्तित करती है। |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

निर्दिष्ट [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना को निकटतम पूर्णांक मानों तक गोल करके एक [Size](/psd/python-net/aspose.psd/size/) संरचना में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | परिवर्तित करने के लिए [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | वह [Size](/psd/python-net/aspose.psd/size/) संरचना जिसे यह विधि परिवर्तित करती है। |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

एक [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई को दूसरी [Size](/psd/python-net/aspose.psd/size/) संरचना की चौड़ाई और ऊँचाई से घटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | घटाव ऑपरेटर के बाएँ पक्ष में स्थित [Size](/psd/python-net/aspose.psd/size/) संरचना। |
| size2 | [Size](/psd/python-net/aspose.psd/size) | घटाव ऑपरेटर के दाएँ पक्ष में स्थित [Size](/psd/python-net/aspose.psd/size/) संरचना। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | घटाव ऑपरेशन का परिणामस्वरूप प्राप्त [Size](/psd/python-net/aspose.psd/size/)। |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

निर्दिष्ट [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना को अगले निचले पूर्णांक मान तक ट्रंकेट करके एक [Size](/psd/python-net/aspose.psd/size/) संरचना में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | परिवर्तित करने के लिए [SizeF](/psd/python-net/aspose.psd/sizef/) संरचना। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | वह [Size](/psd/python-net/aspose.psd/size/) संरचना जिसे यह विधि परिवर्तित करती है। |



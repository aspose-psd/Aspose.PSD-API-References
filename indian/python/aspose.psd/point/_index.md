---
title: "Point क्लास"
type: docs
weight: 3530
url: /hi/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Point()](#Point__1) | Point क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Point(dw)](#Point_dw_2) | निर्दिष्ट पूर्णांक मान द्वारा निर्दिष्ट कोऑर्डिनेट्स का उपयोग करके [Point](/psd/python-net/aspose.psd/point/) संरचना का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Point(size)](#Point_size_3) | [Size](/psd/python-net/aspose.psd/size/) संरचना से [Point](/psd/python-net/aspose.psd/point/) संरचना का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Point(x, y)](#Point_x_y_4) | निर्दिष्ट कोऑर्डिनेट्स के साथ [Point](/psd/python-net/aspose.psd/point/) संरचना का नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | [Point.x](/psd/python-net/aspose.psd/point/) और [Point.y](/psd/python-net/aspose.psd/point/) मान शून्य पर सेट किए हुए [Point](/psd/python-net/aspose.psd/point/) संरचना का नया इंस्टेंस प्राप्त करता है। |
| is_empty | bool | r | यह [Point](/psd/python-net/aspose.psd/point/) खाली है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| x | int | r/w | इस [Point](/psd/python-net/aspose.psd/point/) का x-कोऑर्डिनेट प्राप्त करता है या सेट करता है। |
| y | int | r/w | इस [Point](/psd/python-net/aspose.psd/point/) का y-कोऑर्डिनेट प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | निर्दिष्ट [Size](/psd/python-net/aspose.psd/size/) को निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) में जोड़ता है। |
| [ceiling(point)](#ceiling_point_2) | निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) को एक [Point](/psd/python-net/aspose.psd/point/) में परिवर्तित करता है, [PointF](/psd/python-net/aspose.psd/pointf/) के मानों को अगले बड़े पूर्णांक मान तक गोल करके। |
| [offset(dx, dy)](#offset_dx_dy_3) | इस [Point](/psd/python-net/aspose.psd/point/) को निर्दिष्ट मात्रा द्वारा स्थानांतरित करता है। |
| [offset(point)](#offset_point_4) | इस [Point](/psd/python-net/aspose.psd/point/) को निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) द्वारा स्थानांतरित करता है। |
| [round(point)](#round_point_5) | निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) को एक [Point](/psd/python-net/aspose.psd/point/) ऑब्जेक्ट में परिवर्तित करता है, [Point](/psd/python-net/aspose.psd/point/) के मानों को निकटतम पूर्णांक तक गोल करके। |
| [subtract(point, size)](#subtract_point_size_6) | निर्दिष्ट [Size](/psd/python-net/aspose.psd/size/) को निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) से घटाने के परिणाम को लौटाता है। |
| [truncate(point)](#truncate_point_7) | निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) को एक [Point](/psd/python-net/aspose.psd/point/) में परिवर्तित करता है, [Point](/psd/python-net/aspose.psd/point/) के मानों को काटकर। |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Point क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

निर्दिष्ट पूर्णांक मान द्वारा निर्दिष्ट कोऑर्डिनेट्स का उपयोग करके [Point](/psd/python-net/aspose.psd/point/) संरचना का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dw | int | एक 32-बिट पूर्णांक जो नए बिंदु के निर्देशांक निर्दिष्ट करता है। |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

[Size](/psd/python-net/aspose.psd/size/) संरचना से [Point](/psd/python-net/aspose.psd/point/) संरचना का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | नए बिंदु के निर्देशांक शामिल करता है। |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

निर्दिष्ट कोऑर्डिनेट्स के साथ [Point](/psd/python-net/aspose.psd/point/) संरचना का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | बिंदु की क्षैतिज स्थिति। |
| y | int | बिंदु की लंबवत स्थिति। |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

निर्दिष्ट [Size](/psd/python-net/aspose.psd/size/) को निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) में जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | जिस [Point](/psd/python-net/aspose.psd/point/) में जोड़ना है। |
| size | [Size](/psd/python-net/aspose.psd/size) | <paramref name="point" /> में जोड़ने के लिए [Size](/psd/python-net/aspose.psd/size/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | जोड़ संचालन का परिणाम होने वाला [Point](/psd/python-net/aspose.psd/point/)। |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) को एक [Point](/psd/python-net/aspose.psd/point/) में परिवर्तित करता है, [PointF](/psd/python-net/aspose.psd/pointf/) के मानों को अगले बड़े पूर्णांक मान तक गोल करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | परिवर्तित करने के लिए [PointF](/psd/python-net/aspose.psd/pointf/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | यह विधि जिस [Point](/psd/python-net/aspose.psd/point/) में परिवर्तित करती है। |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

इस [Point](/psd/python-net/aspose.psd/point/) को निर्दिष्ट मात्रा द्वारा स्थानांतरित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dx | int | x-निर्देशांक को ऑफ़सेट करने की मात्रा। |
| dy | int | y-निर्देशांक को ऑफ़सेट करने की मात्रा। |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

इस [Point](/psd/python-net/aspose.psd/point/) को निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) द्वारा स्थानांतरित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | इस [Point](/psd/python-net/aspose.psd/point/) को ऑफ़सेट करने के लिए उपयोग किया गया [Point](/psd/python-net/aspose.psd/point/)। |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) को एक [Point](/psd/python-net/aspose.psd/point/) ऑब्जेक्ट में परिवर्तित करता है, [Point](/psd/python-net/aspose.psd/point/) के मानों को निकटतम पूर्णांक तक गोल करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | परिवर्तित करने के लिए [PointF](/psd/python-net/aspose.psd/pointf/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | यह विधि जिस [Point](/psd/python-net/aspose.psd/point/) में परिवर्तित करती है। |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

निर्दिष्ट [Size](/psd/python-net/aspose.psd/size/) को निर्दिष्ट [Point](/psd/python-net/aspose.psd/point/) से घटाने के परिणाम को लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | जिस [Point](/psd/python-net/aspose.psd/point/) से घटाया जाना है। |
| size | [Size](/psd/python-net/aspose.psd/size) | <paramref name="point" /> से घटाने के लिए [Size](/psd/python-net/aspose.psd/size/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | घटाव संचालन का परिणाम होने वाला [Point](/psd/python-net/aspose.psd/point/)। |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

निर्दिष्ट [PointF](/psd/python-net/aspose.psd/pointf/) को एक [Point](/psd/python-net/aspose.psd/point/) में परिवर्तित करता है, [Point](/psd/python-net/aspose.psd/point/) के मानों को काटकर।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | परिवर्तित करने के लिए [PointF](/psd/python-net/aspose.psd/pointf/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | यह विधि जिस [Point](/psd/python-net/aspose.psd/point/) में परिवर्तित करती है। |



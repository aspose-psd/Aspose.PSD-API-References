---
title: "Figure क्लास"
type: docs
weight: 1220
url: /hi/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Figure()](#Figure__1) | Figure क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | ऑब्जेक्ट की सीमाओं को प्राप्त करता है या सेट करता है। |
| is_closed | bool | r/w | इस आकृति के बंद होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। एक बंद आकृति केवल तब अंतर पैदा करेगी जब<br/>            पहली और अंतिम आकृति के आकार सतत आकार हों। ऐसे मामले में पहली आकृति के पहले बिंदु को<br/>            अंतिम आकृति के अंतिम बिंदु से एक सीधी रेखा द्वारा जोड़ा जाएगा। |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | पूरे आकृति खंडों को प्राप्त करता है। |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | आकृति के आकारों को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | आकृति में एक आकार जोड़ता है। |
| [add_shapes(shapes)](#add_shapes_shapes_2) | आकृति में आकारों की एक श्रृंखला जोड़ता है। |
| [get_bounds(matrix)](#get_bounds_matrix_3) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [remove_shape(shape)](#remove_shape_shape_5) | आकृति से एक आकार हटाता है। |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | आकृति से आकारों की एक श्रृंखला हटाता है। |
| reverse() | इस आकृति के आकार क्रम और आकार बिंदु क्रम को उलटता है। |
| [transform(transform)](#transform_transform_7) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Figure क्लास का एक नया इंस्टेंस प्रारंभ करता है।

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

आकृति में एक आकार जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | जोड़ने के लिए आकार। |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

आकृति में आकारों की एक श्रृंखला जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | जोड़ने के लिए आकार। |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | सीमाओं से पहले लागू करने के लिए मैट्रिक्स की गणना की जाएगी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | अनुमानित ऑब्जेक्ट की सीमाएँ। |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | सीमाओं से पहले लागू करने के लिए मैट्रिक्स की गणना की जाएगी। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | ऑब्जेक्ट के लिए उपयोग करने वाला पेन। यह ऑब्जेक्ट की सीमाओं के आकार को प्रभावित कर सकता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | अनुमानित ऑब्जेक्ट की सीमाएँ। |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

आकृति से एक आकार हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | हटाने के लिए आकार। |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

आकृति से आकारों की एक श्रृंखला हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | हटाने के लिए आकारों की सीमा। |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

निर्दिष्ट परिवर्तन को आकार पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | लागू करने के लिए परिवर्तन। |


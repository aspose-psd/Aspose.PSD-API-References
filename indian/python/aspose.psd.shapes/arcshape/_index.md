---
title: "ArcShape क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | नए [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | नए [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | नए [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | आकार के केंद्र को प्राप्त करता है। |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | समाप्ति आकार बिंदु को प्राप्त करता है। |
| has_segments | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि आकार में सेगमेंट हैं या नहीं। |
| is_closed | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्रमबद्ध आकार बंद है या नहीं। जब बंद क्रमबद्ध आकार को प्रोसेस किया जाता है तो प्रारंभ और समाप्ति बिंदुओं का कोई अर्थ नहीं रहता। |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | बाएँ नीचे आयत बिंदु को प्राप्त करता है। |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | बाएँ ऊपर आयत बिंदु को प्राप्त करता है। |
| rectangle_height | डबल | r | आयत की ऊँचाई प्राप्त करता है। |
| rectangle_width | डबल | r | आयत की चौड़ाई प्राप्त करता है। |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | दाएँ नीचे आयत बिंदु को प्राप्त करता है। |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | दाएँ ऊपर आयत बिंदु को प्राप्त करता है। |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | आकार के सेगमेंट प्राप्त करता है। |
| start_angle | float | r/w | शुरुआती कोण को प्राप्त करता है या सेट करता है। |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | प्रारंभिक आकार बिंदु को प्राप्त करता है। |
| sweep_angle | float | r/w | स्वीप कोण को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| reverse() | इस आकार के लिए बिंदुओं के क्रम को उलटता है। |
| [transform(transform)](#transform_transform_3) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

नए [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

नए [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | आयत। |
| start_angle | float | शुरुआती कोण। |
| sweep_angle | float | स्वीप कोण। |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

नए [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | आयत। |
| start_angle | float | शुरुआती कोण। |
| sweep_angle | float | स्वीप कोण। |
| is_closed | bool | यदि <c>true</c> पर सेट किया जाता है तो आर्क बंद हो जाता है। बंद आर्क वास्तव में एक दीर्घवृत्त में बदल जाता है। |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

निर्दिष्ट परिवर्तन को आकार पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | लागू करने के लिए परिवर्तन। |


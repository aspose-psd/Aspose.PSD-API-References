---
title: "BezierShape क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.psd.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | नए [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BezierShape(points)](#BezierShape_points_2) | नए [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | नए [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | आकार के केंद्र को प्राप्त करता है। |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | समाप्ति आकार बिंदु को प्राप्त करता है। |
| has_segments | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि आकार में सेगमेंट हैं या नहीं। |
| is_closed | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि आकार बंद है या नहीं। |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | वक्र बिंदुओं को प्राप्त करता है या सेट करता है। |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | आकार के सेगमेंट प्राप्त करता है। |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | प्रारंभिक आकार बिंदु को प्राप्त करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| reverse() | इस आकार के लिए बिंदुओं के क्रम को उलटता है। |
| [transform(transform)](#transform_transform_3) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

नए [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

नए [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | बिंदुओं की सरणी। |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

नए [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | बिंदुओं की सरणी। |
| is_closed | bool | यदि <c>true</c> पर सेट किया जाता है तो बेज़ियर स्पलाइन बंद हो जाता है। |

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


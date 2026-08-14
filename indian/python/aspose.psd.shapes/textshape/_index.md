---
title: "TextShape क्लास"
type: docs
weight: 90
url: /hi/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [TextShape()](#TextShape__1) | नया उदाहरण प्रारंभ करता है [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) क्लास का। |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | नया उदाहरण प्रारंभ करता है [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | आकार के केंद्र को प्राप्त करता है। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | पाठ को ड्रॉ करने के लिए उपयोग किए जाने वाले फ़ॉन्ट को प्राप्त करता है या सेट करता है। |
| has_segments | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि आकार में सेगमेंट हैं या नहीं। |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | बाएँ नीचे आयत बिंदु को प्राप्त करता है। |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | बाएँ ऊपर आयत बिंदु को प्राप्त करता है। |
| rectangle_height | डबल | r | आयत की ऊँचाई प्राप्त करता है। |
| rectangle_width | डबल | r | आयत की चौड़ाई प्राप्त करता है। |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | दाएँ नीचे आयत बिंदु को प्राप्त करता है। |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | दाएँ ऊपर आयत बिंदु को प्राप्त करता है। |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | आकार के सेगमेंट प्राप्त करता है। |
| text | string | r/w | ड्रॉ किया गया पाठ प्राप्त करता है या सेट करता है। |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | पाठ प्रारूप को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [transform(transform)](#transform_transform_3) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

नया उदाहरण प्रारंभ करता है [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) क्लास का।

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

नया उदाहरण प्रारंभ करता है [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | string | ड्रॉ करने के लिए पाठ। |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | पाठ आयत। |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | उपयोग करने के लिए फ़ॉन्ट। |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | स्ट्रिंग प्रारूप। |

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


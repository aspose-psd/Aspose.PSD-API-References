---
title: "LinearMulticolorGradientBrush क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/psd/python-net/aspose.psd/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | डिफ़ॉल्ट पैरामीटरों के साथ [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।<br/> प्रारंभिक रंग काला है, अंतिम रंग सफ़ेद है, कोण 45 डिग्री है और आयत (0,0) में स्थित है जिसका आकार (1,1) है। |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | निर्दिष्ट बिंदुओं के साथ [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | निर्दिष्ट बिंदुओं के साथ [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| कोण | float | r/w | ग्रेडिएंट कोण को प्राप्त करता है या सेट करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| gamma_correction | bool | r/w | इस [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) के लिए गामा सुधार सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | एक [ColorBlend](/psd/python-net/aspose.psd/colorblend/) प्राप्त करता है या सेट करता है जो बहुरंगी रैखिक ग्रेडिएंट को परिभाषित करता है। |
| is_angle_scalable | bool | r/w | इस [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) के साथ परिवर्तन के दौरान क्या [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) बदलता है, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| is_transform_changed | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि क्या परिवर्तन किसी न किसी तरीके से बदले गए हैं। उदाहरण के लिए परिवर्तन मैट्रिक्स सेट करना या<br/> परिवर्तन मैट्रिक्स को बदलने वाली किसी भी विधि को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पिछली संगतता के लिए प्रस्तुत की गई है। |
| opacity | float | r/w | ब्रश की अपारदर्शिता को प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है। |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | ग्रेडिएंट के प्रारंभ और समाप्त बिंदुओं को परिभाषित करने वाला आयताकार क्षेत्र प्राप्त करता है या सेट करता है। |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | इस [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) के लिए स्थानीय ज्यामितीय परिवर्तन को परिभाषित करने वाली एक कॉपी [Matrix](/psd/python-net/aspose.psd/matrix/) प्राप्त करता है या सेट करता है। |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | इस [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) के लिए रैप मोड दर्शाने वाला एक [WrapMode](/psd/python-net/aspose.psd/wrapmode/) एन्क्यूमरेशन प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | वर्तमान [Brush](/psd/python-net/aspose.psd/brush/) का एक नया डीप क्लोन बनाता है। |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) को इस [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) के स्थानीय ज्यामितीय परिवर्तन को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) से गुणा करता है, निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) को पहले जोड़कर। |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) को इस [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) के स्थानीय ज्यामितीय परिवर्तन को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) से गुणा करता है, निर्दिष्ट क्रम में। |
| reset_transform() | रीसेट करता है [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) प्रॉपर्टी को identity पर। |
| [rotate_transform(angle)](#rotate_transform_angle_4) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घुमाव को ट्रांसफ़ॉर्म के पहले जोड़ता है। |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से निर्दिष्ट क्रम में घुमाता है। |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म के पहले जोड़ता है। |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से निर्दिष्ट क्रम में स्केल करता है। |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्म के पहले जोड़ता है। |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से निर्दिष्ट क्रम में ट्रांसलेट करता है। |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

डिफ़ॉल्ट पैरामीटरों के साथ [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।<br/> प्रारंभिक रंग काला है, अंतिम रंग सफ़ेद है, कोण 45 डिग्री है और आयत (0,0) में स्थित है जिसका आकार (1,1) है।

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

निर्दिष्ट बिंदुओं के साथ [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के प्रारंभ बिंदु को दर्शाती है। |
| point2 | [Point](/psd/python-net/aspose.psd/point) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

निर्दिष्ट बिंदुओं के साथ [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के प्रारंभ बिंदु को दर्शाती है। |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |
| is_angle_scalable | bool | यदि <c>true</c> पर सेट किया गया है तो इस [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) के साथ ट्रांसफ़ॉर्मेशन के दौरान कोण बदल जाता है। |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

एक आयत और अभिविन्यास कोण के आधार पर [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |
| is_angle_scalable | bool | यदि <c>true</c> पर सेट किया गया है तो इस [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) के साथ ट्रांसफ़ॉर्मेशन के दौरान कोण बदल जाता है। |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

वर्तमान [Brush](/psd/python-net/aspose.psd/brush/) का एक नया डीप क्लोन बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | एक नया [Brush](/psd/python-net/aspose.psd/brush/) जो इस [Brush](/psd/python-net/aspose.psd/brush/) इंस्टेंस की गहरी क्लोन है। |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) को इस [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) के स्थानीय ज्यामितीय परिवर्तन को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) से गुणा करता है, निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) को पहले जोड़कर।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | वह [Matrix](/psd/python-net/aspose.psd/matrix/) जिससे ज्यामितीय ट्रांसफ़ॉर्म को गुणा किया जाता है। |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

निर्दिष्ट [Matrix](/psd/python-net/aspose.psd/matrix/) को इस [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) के स्थानीय ज्यामितीय परिवर्तन को दर्शाने वाले [Matrix](/psd/python-net/aspose.psd/matrix/) से गुणा करता है, निर्दिष्ट क्रम में।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | वह [Matrix](/psd/python-net/aspose.psd/matrix/) जिससे ज्यामितीय ट्रांसफ़ॉर्म को गुणा किया जाता है। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | एक [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) जो यह निर्दिष्ट करता है कि दो मैट्रिसेज़ को किस क्रम में गुणा किया जाए। |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से घुमाता है। यह मेथड घुमाव को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | घुमाव का कोण। |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मात्रा से निर्दिष्ट क्रम में घुमाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | घुमाव का कोण। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | एक [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) जो यह निर्दिष्ट करता है कि घुमाव मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से स्केल करता है। यह मेथड स्केलिंग मैट्रिक्स को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sx | float | x-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट मानों से निर्दिष्ट क्रम में स्केल करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sx | float | x-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में ट्रांसफ़ॉर्म को स्केल करने की मात्रा। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | एक [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) जो यह निर्दिष्ट करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dx | float | x में ट्रांसलेशन का मान। |
| dy | float | y में अनुवाद का मान। |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से निर्दिष्ट क्रम में ट्रांसलेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dx | float | x में ट्रांसलेशन का मान। |
| dy | float | y में अनुवाद का मान। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | अनुवाद लागू करने का क्रम (prepend या append)। |


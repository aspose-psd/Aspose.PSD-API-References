---
title: "PathMulticolorGradientBrush क्लास"
type: docs
weight: 70
url: /hi/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | निर्दिष्ट पाथ के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_2) | निर्दिष्ट पॉइंट्स के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_3) | निर्दिष्ट पॉइंट्स के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_4) | निर्दिष्ट पॉइंट्स और रैप मोड के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_5) | निर्दिष्ट पॉइंट्स और रैप मोड के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | पाथ ग्रेडिएंट का केंद्र बिंदु प्राप्त करता है या सेट करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | ग्रेडिएंट फ़ॉलऑफ़ के लिए फोकस बिंदु प्राप्त करता है या सेट करता है। |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | इस ब्रश के निर्मित ग्राफ़िक्स पाथ को प्राप्त करता है। |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | एक [ColorBlend](/psd/python-net/aspose.psd/colorblend/) प्राप्त करता है या सेट करता है जो बहुरंगी रैखिक ग्रेडिएंट को परिभाषित करता है। |
| is_transform_changed | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि क्या परिवर्तन किसी न किसी तरीके से बदले गए हैं। उदाहरण के लिए परिवर्तन मैट्रिक्स सेट करना या<br/> परिवर्तन मैट्रिक्स को बदलने वाली किसी भी विधि को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पिछली संगतता के लिए प्रस्तुत की गई है। |
| opacity | float | r/w | ब्रश की अपारदर्शिता को प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है। |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | इस ब्रश के निर्मित पाथ पॉइंट्स को प्राप्त करता है। |
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


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

निर्दिष्ट पाथ के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | यह [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) जो इस [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) द्वारा भरे गए क्षेत्र को परिभाषित करता है। |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_2}


```
 PathMulticolorGradientBrush(points) 
```

निर्दिष्ट पॉइंट्स के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | पाथ के वर्टिसेज़ बनाते हुए पॉइंट्स को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे। |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_3}


```
 PathMulticolorGradientBrush(points) 
```

निर्दिष्ट पॉइंट्स के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | पाथ के वर्टिसेज़ बनाते हुए पॉइंट्स को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे। |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

निर्दिष्ट पॉइंट्स और रैप मोड के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | पाथ के वर्टिसेज़ बनाते हुए पॉइंट्स को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे। |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | एक [WrapMode](/psd/python-net/aspose.psd/wrapmode/) जो यह निर्दिष्ट करता है कि इस [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) के साथ खींचे गए फ़िल्स कैसे टाइल किए जाते हैं। |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

निर्दिष्ट पॉइंट्स और रैप मोड के साथ [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | पाथ के वर्टिसेज़ बनाते हुए पॉइंट्स को दर्शाने वाली [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे। |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | एक [WrapMode](/psd/python-net/aspose.psd/wrapmode/) जो यह निर्दिष्ट करता है कि इस [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) के साथ खींचे गए फ़िल्स कैसे टाइल किए जाते हैं। |

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


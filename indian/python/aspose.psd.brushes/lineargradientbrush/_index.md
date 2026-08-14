---
title: "LinearGradientBrush क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | डिफ़ॉल्ट पैरामीटरों के साथ [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।<br/> प्रारंभिक रंग काला है, अंतिम रंग सफ़ेद है, कोण 45 डिग्री है और आयत (0,0) पर स्थित है जिसका आकार (1,1) है। |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| कोण | float | r/w | ग्रेडिएंट कोण को प्राप्त करता है या सेट करता है। |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | एक [Blend](/psd/python-net/aspose.psd/blend/) प्राप्त करता है या सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और कारकों को निर्दिष्ट करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | अंतिम ग्रेडिएंट रंग प्राप्त करता है या सेट करता है। |
| gamma_correction | bool | r/w | इस [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) के लिए गामा सुधार सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | एक [ColorBlend](/psd/python-net/aspose.psd/colorblend/) प्राप्त करता है या सेट करता है जो बहुरंगी रैखिक ग्रेडिएंट को परिभाषित करता है। |
| is_angle_scalable | bool | r/w | इस [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) के साथ परिवर्तन के दौरान क्या [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) बदलता है, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| is_transform_changed | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि क्या परिवर्तन किसी न किसी तरीके से बदले गए हैं। उदाहरण के लिए परिवर्तन मैट्रिक्स सेट करना या<br/> परिवर्तन मैट्रिक्स को बदलने वाली किसी भी विधि को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पिछली संगतता के लिए प्रस्तुत की गई है। |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | ग्रेडिएंट के प्रारंभिक और अंतिम रंग प्राप्त करता है या सेट करता है। |
| opacity | float | r/w | ब्रश की अपारदर्शिता को प्राप्त करता है या सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है। |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | ग्रेडिएंट के प्रारंभ और समाप्त बिंदुओं को परिभाषित करने वाला आयताकार क्षेत्र प्राप्त करता है या सेट करता है। |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | प्रारंभिक ग्रेडिएंट रंग प्राप्त करता है या सेट करता है। |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग तक रैखिक फॉलऑफ़ होता है। |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग तक रैखिक फॉलऑफ़ होता है। |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | घंटी के आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है। |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | घंटी के आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है। |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्म के पहले जोड़ता है। |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से निर्दिष्ट क्रम में ट्रांसलेट करता है। |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

डिफ़ॉल्ट पैरामीटरों के साथ [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।<br/> प्रारंभिक रंग काला है, अंतिम रंग सफ़ेद है, कोण 45 डिग्री है और आयत (0,0) पर स्थित है जिसका आकार (1,1) है।

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के प्रारंभ बिंदु को दर्शाती है। |
| point2 | [Point](/psd/python-net/aspose.psd/point) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |
| color1 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक रंग का प्रतिनिधित्व करती है। |
| color2 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो रैखिक ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

निर्दिष्ट बिंदुओं और रंगों के साथ [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के प्रारंभ बिंदु को दर्शाती है। |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | एक [Point](/psd/python-net/aspose.psd/point/) संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |
| color1 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक रंग का प्रतिनिधित्व करती है। |
| color2 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो रैखिक ग्रेडिएंट के अंतिम रंग का प्रतिनिधित्व करती है। |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के प्रारंभिक रंग का प्रतिनिधित्व करती है। |
| color2 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के अंत रंग का प्रतिनिधित्व करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के प्रारंभिक रंग का प्रतिनिधित्व करती है। |
| color2 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के अंत रंग का प्रतिनिधित्व करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के प्रारंभिक रंग का प्रतिनिधित्व करती है। |
| color2 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के अंत रंग का प्रतिनिधित्व करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |
| is_angle_scalable | bool | यदि इसे <c>true</c> पर सेट किया जाता है तो इस [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) के साथ रूपांतरण के दौरान कोण बदल जाता है। |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

एक आयत, प्रारंभिक और अंतिम रंग, तथा अभिविन्यास कोण के आधार पर [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के प्रारंभिक रंग का प्रतिनिधित्व करती है। |
| color2 | [Color](/psd/python-net/aspose.psd/color) | एक [Color](/psd/python-net/aspose.psd/color/) संरचना जो ग्रेडिएंट के अंत रंग का प्रतिनिधित्व करती है। |
| कोण | float | कोण, जो x-अक्ष से घड़ी की दिशा में डिग्री में मापा जाता है, ग्रेडिएंट की अभिविन्यास रेखा का। |
| is_angle_scalable | bool | यदि इसे <c>true</c> पर सेट किया जाता है तो इस [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) के साथ रूपांतरण के दौरान कोण बदल जाता है। |

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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग तक रैखिक फॉलऑफ़ होता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंत रंग से बना होता है)। |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

एक रैखिक ग्रेडिएंट बनाता है जिसमें मध्य रंग और दोनों सिरों पर एकल रंग तक रैखिक फॉलऑफ़ होता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंत रंग से बना होता है)। |
| scale | float | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि रंग प्रारंभिक रंग से <paramref name=\"focus\" /> (अंत रंग) तक कितनी तेज़ी से घटते हैं। |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

घंटी के आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ प्रारंभिक रंग और अंत रंग समान रूप से मिश्रित होते हैं)। |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

घंटी के आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंत रंग से बना होता है)। |
| scale | float | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि रंग <paramref name=\"focus\" /> से कितनी तेज़ी से घटते हैं। |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

स्थानीय ज्यामितीय ट्रांसफ़ॉर्म को निर्दिष्ट आयामों से ट्रांसलेट करता है। यह मेथड ट्रांसलेशन को ट्रांसफ़ॉर्म के पहले जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dx | float | x में ट्रांसलेशन का मान। |
| dy | float | y में अनुवाद का मान। |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


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


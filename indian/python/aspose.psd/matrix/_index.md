---
title: "Matrix क्लास"
type: docs
weight: 3000
url: /hi/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Matrix()](#Matrix__1) | Matrix क्लास का एक नया उदाहरण पहचान मैट्रिक्स के रूप में आरंभ करता है। |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | [Matrix](/psd/python-net/aspose.psd/matrix/) क्लास का एक नया उदाहरण आरंभ करता है। |
| [Matrix(origin)](#Matrix_origin_3) | [Matrix](/psd/python-net/aspose.psd/matrix/) क्लास की एक प्रति बनाता है। |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | [Matrix](/psd/python-net/aspose.psd/matrix/) क्लास का एक नया उदाहरण निर्दिष्ट आयत और बिंदुओं की श्रृंखला द्वारा परिभाषित ज्यामितीय रूपांतरण पर आरंभ करता है। |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | [Matrix](/psd/python-net/aspose.psd/matrix/) क्लास का एक नया उदाहरण निर्दिष्ट आयत और बिंदुओं की श्रृंखला द्वारा परिभाषित ज्यामितीय रूपांतरण पर आरंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म<br/>            कुछ अक्ष के बारे में एक मिरर इमेज फ़्लिप करता है जो सामान्यतः दाएँ हाथीय समन्वय प्रणाली को बाएँ हाथीय<br/>            प्रणाली में बदल देता है, साथ ही अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों के अतिरिक्त।<br/>            एक दाएँ हाथीय समन्वय प्रणाली वह है जहाँ सकारात्मक X<br/>            अक्ष प्रतिक्लॉकवाइज़ घुमता है ताकि सकारात्मक Y अक्ष के ऊपर ओवरले हो सके<br/>            जैसे आपके दाएँ हाथ की उंगलियों की दिशा जब आप अपने अंगूठे को सामने से देखते हैं।<br/>            एक बाएँ हाथीय समन्वय प्रणाली वह है जहाँ सकारात्मक X<br/>            अक्ष क्लॉकवाइज़ घुमता है ताकि सकारात्मक Y अक्ष के ऊपर ओवरले हो सके, जैसे आपके बाएँ हाथ की उंगलियों की दिशा।<br/>            मूल फ़्लिप या मिररिंग ट्रांसफ़ॉर्मेशन का कोण निर्धारित करने का कोई गणितीय तरीका नहीं है क्योंकि सभी फ़्लिप कोण समान होते हैं जब उचित समायोजन घूर्णन दिया जाता है।<br/>            नोट: TypeFlip को GENERAL_TRANSFORM के सार्वजनिक प्रसार के बाद जोड़ा गया था और फ़्लैग बिट्स को सुविधाजनक रूप से पुनः क्रमांकित नहीं किया जा सका बिना बाहरी कोड में बाइनरी असंगतता लाए। |
| TYPE_GENERAL_ROTATION [static] | int | r | यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म<br/>            एक मनमाने कोण द्वारा घूर्णन करता है, साथ ही अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों के अतिरिक्त।<br/>            घूर्णन वेक्टर के कोणों को समान मात्रा में बदलता है<br/>            वेक्टर की मूल दिशा की परवाह किए बिना और वेक्टर की लंबाई को बदले बिना।<br/>            यह फ़्लैग बिट इस के साथ आपसी रूप से अनन्य है। |
| TYPE_GENERAL_SCALE [static] | int | r | एक सामान्य स्केल वेक्टर की लंबाई को x और y दिशाओं में विभिन्न मात्रा से गुणा करता है, बिना लम्बवत वेक्टरों के बीच के कोण को बदले।<br/>            यह फ़्लैग बिट TypeUniformScale फ़्लैग के साथ आपसी रूप से अनन्य है। |
| TYPE_GENERAL_TRANSFORM [static] | int | r | यह स्थिरांक दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म<br/>            इनपुट समन्वयों का एक मनमाना रूपांतरण करता है।<br/>            यदि इस ट्रांसफ़ॉर्म को उपरोक्त किसी भी स्थिरांक द्वारा वर्गीकृत किया जा सकता है,<br/>            तो प्रकार या तो स्थिरांक TypeIdentity होगा या विभिन्न समन्वय<br/>            रूपांतरणों के लिए उपयुक्त फ़्लैग बिट्स का संयोजन होगा जो यह ट्रांसफ़ॉर्म करता है। |
| TYPE_IDENTITY [static] | int | r | एक पहचान ट्रांसफ़ॉर्म वह है जिसमें आउटपुट समन्वय हमेशा इनपुट समन्वयों के समान होते हैं।<br/>            यदि यह ट्रांसफ़ॉर्म पहचान ट्रांसफ़ॉर्म के अलावा कुछ भी है,<br/>            तो प्रकार या तो स्थिरांक GENERAL_TRANSFORM होगा या विभिन्न समन्वय<br/>            रूपांतरणों के लिए उपयुक्त फ़्लैग बिट्स का संयोजन होगा जो यह ट्रांसफ़ॉर्म करता है। |
| TYPE_MASK_ROTATION [static] | int | r | यह स्थिरांक किसी भी घूर्णन फ़्लैग बिट के लिए एक बिट मास्क है। |
| TYPE_MASK_SCALE [static] | int | r | यह स्थिरांक किसी भी स्केल फ़्लैग बिट के लिए एक बिट मास्क है। |
| TYPE_QUADRANT_ROTATION [static] | int | r | यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म<br/>            कुछ 90 डिग्री के गुणज द्वारा क्वाड्रेंट घूर्णन करता है, साथ ही अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों के अतिरिक्त।<br/>            घूर्णन वेक्टर के कोणों को समान मात्रा में बदलता है<br/>            वेक्टर की मूल दिशा की परवाह किए बिना और वेक्टर की लंबाई को बदले बिना।<br/>            यह फ़्लैग बिट TypeGeneralRotation फ़्लैग के साथ आपसी रूप से अनन्य है। |
| TYPE_TRANSLATION [static] | int | r | एक ट्रांसलेशन x और y में समन्वयों को एक स्थिर मात्रा से स्थानांतरित करता है, बिना वेक्टर की लंबाई या कोण को बदले। |
| TYPE_UNIFORM_SCALE [static] | int | r | एक समान स्केल वेक्टरों की लंबाई को समान मात्रा से गुणा करता है<br/>            दोनों x और y दिशाओं में बिना वेक्टरों के बीच के कोण को बदले<br/>            वेक्टरों की लंबाई को बदलता है।<br/>            यह फ़्लैग बिट TypeGeneralScale फ़्लैग के साथ परस्पर अनन्य है। |
| elements | float | r | इस [Matrix](/psd/python-net/aspose.psd/matrix/) के तत्वों का प्रतिनिधित्व करने वाले फ्लोटिंग-पॉइंट मानों की एक एरे प्राप्त करता है। |
| m11 | float | r | पहली पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। X अक्ष के साथ स्केल का प्रतिनिधित्व करता है। |
| m12 | float | r | पहली पंक्ति दूसरी कॉलम में मैट्रिक्स तत्व प्राप्त करता है। Y अक्ष के साथ शियर का प्रतिनिधित्व करता है। |
| m21 | float | r | दूसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। X अक्ष के साथ शियर का प्रतिनिधित्व करता है। |
| m22 | float | r | दूसरी पंक्ति दूसरी कॉलम में मैट्रिक्स तत्व प्राप्त करता है। Y अक्ष के साथ स्केल का प्रतिनिधित्व करता है। |
| m31 | float | r | तीसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। X अक्ष के साथ ट्रांसलेशन का प्रतिनिधित्व करता है। |
| m32 | float | r | तीसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। Y अक्ष के साथ ट्रांसलेशन का प्रतिनिधित्व करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [get_elements()](#get_elements__1) | मैट्रिक्स तत्वों की कॉपी प्राप्त करता है। |
| [multiply(tx)](#multiply_tx_2) | इस Matrix को matrix पैरामीटर में निर्दिष्ट मैट्रिक्स से (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके गुणा करता है। |
| [multiply(tx, order)](#multiply_tx_order_3) | इस Matrix को matrix पैरामीटर में निर्दिष्ट मैट्रिक्स से, और order पैरामीटर में निर्दिष्ट क्रम में गुणा करता है। |
| reset() | इस Matrix को पहचान (identity) मैट्रिक्स के तत्वों के साथ रीसेट करता है। |
| [rotate(angle)](#rotate_angle_4) | इस Matrix पर डिफ़ॉल्ट (Prepend) क्रम में, कोण पैरामीटर में निर्दिष्ट मात्रा के साथ, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर घड़ी की दिशा में घुमाव लागू करता है। |
| [rotate(angle, order)](#rotate_angle_order_5) | इस Matrix पर निर्दिष्ट क्रम में, कोण पैरामीटर में निर्दिष्ट मात्रा के साथ, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर घड़ी की दिशा में घुमाव लागू करता है। |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | निर्दिष्ट बिंदु के बारे में इस Matrix पर डिफ़ॉल्ट (Prepend) क्रम में घड़ी की दिशा में घुमाव लागू करता है। |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | निर्दिष्ट बिंदु के बारे में इस Matrix पर निर्दिष्ट क्रम में घड़ी की दिशा में घुमाव लागू करता है। |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | निर्दिष्ट क्रम का उपयोग करके इस [Matrix](/psd/python-net/aspose.psd/matrix/) पर निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) लागू करता है। |
| [scale(sx, sy)](#scale_sx_sy_9) | इस Matrix पर (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) लागू करता है। |
| [transform_points(points)](#transform_points_points_10) | इस [Matrix](/psd/python-net/aspose.psd/matrix/) द्वारा प्रतिनिधित्व किए गए ज्यामितीय रूपांतरण को बिंदुओं की निर्दिष्ट एरे पर लागू करता है। |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | निर्दिष्ट क्रम में इस मैट्रिक्स पर निर्दिष्ट ट्रांसलेशन वेक्टर लागू करता है। |
| [translate(tx, ty)](#translate_tx_ty_12) | डिफ़ॉल्ट (Prepend) क्रम का उपयोग करके इस [Matrix](/psd/python-net/aspose.psd/matrix/) पर निर्दिष्ट ट्रांसलेशन वेक्टर लागू करता है। |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Matrix क्लास का एक नया उदाहरण पहचान मैट्रिक्स के रूप में आरंभ करता है।

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| m11 | float | m00     M11     स्केल X |
| m12 | float | m10     M12     शियर Y |
| m21 | float | m01     M21     शियर X |
| m22 | float | m11     M22     स्केल Y |
| m31 | float | m02     M31     ट्रांसलेट X |
| m32 | float | m12     M32     ट्रांसलेट Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) क्लास की एक प्रति बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | कॉपींग के लिए एक बेस मैट्रिक्स। |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) क्लास का एक नया उदाहरण निर्दिष्ट आयत और बिंदुओं की श्रृंखला द्वारा परिभाषित ज्यामितीय रूपांतरण पर आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो परिवर्तित किए जाने वाले आयत को दर्शाती है। |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | तीन [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे जो एक पैरालेलोग्राम के बिंदुओं को दर्शाती है, जहाँ आयत के ऊपर-बाएँ, ऊपर-दाएँ, और नीचे-बाएँ कोने को परिवर्तित किया जाएगा। पैरालेलोग्राम का नीचे-दाएँ कोना पहले तीन कोनों से अनुमानित होता है। |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) क्लास का एक नया उदाहरण निर्दिष्ट आयत और बिंदुओं की श्रृंखला द्वारा परिभाषित ज्यामितीय रूपांतरण पर आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) संरचना जो परिवर्तित किए जाने वाले आयत को दर्शाती है। |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | तीन [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की एक एरे जो एक पैरालेलोग्राम के बिंदुओं को दर्शाती है, जहाँ आयत के ऊपर-बाएँ, ऊपर-दाएँ, और नीचे-बाएँ कोने को परिवर्तित किया जाएगा। पैरालेलोग्राम का नीचे-दाएँ कोना पहले तीन कोनों से अनुमानित होता है। |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

मैट्रिक्स तत्वों की कॉपी प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| float | एक मैट्रिक्स तत्वों की कॉपी। |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

इस Matrix को matrix पैरामीटर में निर्दिष्ट मैट्रिक्स से (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके गुणा करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | गुणा करने के लिए मैट्रिक्स। |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

इस Matrix को matrix पैरामीटर में निर्दिष्ट मैट्रिक्स से, और order पैरामीटर में निर्दिष्ट क्रम में गुणा करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | ट्रांसलेशन tx। ट्रांसलेशन tx। ट्रांसलेशन tx। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | क्रम। क्रम। क्रम। |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

इस Matrix पर डिफ़ॉल्ट (Prepend) क्रम में, कोण पैरामीटर में निर्दिष्ट मात्रा के साथ, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर घड़ी की दिशा में घुमाव लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | घुमाव कोण। |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

इस Matrix पर निर्दिष्ट क्रम में, कोण पैरामीटर में निर्दिष्ट मात्रा के साथ, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर घड़ी की दिशा में घुमाव लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | घुमाव कोण। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | मैट्रिक्स क्रम। |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

निर्दिष्ट बिंदु के बारे में इस Matrix पर डिफ़ॉल्ट (Prepend) क्रम में घड़ी की दिशा में घुमाव लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | कोण। |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | बिंदु। |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

निर्दिष्ट बिंदु के बारे में इस Matrix पर निर्दिष्ट क्रम में घड़ी की दिशा में घुमाव लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | कोण। |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | बिंदु। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | क्रम। |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

निर्दिष्ट क्रम का उपयोग करके इस [Matrix](/psd/python-net/aspose.psd/matrix/) पर निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scale_x | float | स्केल X। |
| scale_y | float | स्केल Y। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | क्रम। |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

इस Matrix पर (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sx | float | sx। sx। sx। |
| sy | float | sy। sy। sy। |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

इस [Matrix](/psd/python-net/aspose.psd/matrix/) द्वारा प्रतिनिधित्व किए गए ज्यामितीय रूपांतरण को बिंदुओं की निर्दिष्ट एरे पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | बिंदु। |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

निर्दिष्ट क्रम में इस मैट्रिक्स पर निर्दिष्ट ट्रांसलेशन वेक्टर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| offset_x | float | ऑफ़सेट X। |
| offset_y | float | ऑफ़सेट Y। |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | क्रम। |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

डिफ़ॉल्ट (Prepend) क्रम का उपयोग करके इस [Matrix](/psd/python-net/aspose.psd/matrix/) पर निर्दिष्ट ट्रांसलेशन वेक्टर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| tx | float | ट्रांसलेशन tx। ट्रांसलेशन tx। ट्रांसलेशन tx। |
| ty | float | टाइ। टाइ। टाइ। |


---
title: "Matrix"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "GDI मैट्रिक्स को प्रतिस्थापित करता है।"
type: docs
weight: 69
url: /hi/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

GDI+ मैट्रिक्स को बदलता है।

अधिकांश एल्गोरिदम Sun की AffineTransform.java से लिए गए हैं। मैट्रिक्स तत्वों के लिए जावा के आंतरिक उपयोग किए जाने वाले नाम। जावा नामों को .net नामों और उनके विवरण के साथ मानचित्र: m00 M11 स्केल X m10 M12 शीयर Y m01 M21 शीयर X m11 M22 स्केल Y m02 M31 ट्रांसलेट X m12 M32 ट्रांसलेट Y
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix क्लास का नया इंस्टेंस पहचान मैट्रिक्स के रूप में इनिशियलाइज़ करता है। |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Matrix क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Matrix क्लास की एक कॉपी बनाता है। |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Aspose.Imaging.Matrix क्लास का नया इंस्टेंस निर्दिष्ट आयत और बिंदुओं के एरे द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्म के लिए इनिशियलाइज़ करता है। |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Aspose.Imaging.Matrix क्लास का नया इंस्टेंस निर्दिष्ट आयत और बिंदुओं के एरे द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्म के लिए इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म कुछ अक्ष के बारे में मिरर इमेज फ़्लिप करता है, जो सामान्यतः दाएँ‑हाथ कोऑर्डिनेट सिस्टम को बाएँ‑हाथ सिस्टम में बदल देता है, साथ ही अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों को भी जोड़ता है। |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म एक मनमाने कोण द्वारा घूर्णन करता है, साथ ही अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों को भी जोड़ता है। |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | एक सामान्य स्केल वेक्टर की लंबाई को x और y दिशाओं में विभिन्न मात्रा से गुणा करता है, बिना लम्बवत वेक्टरों के बीच के कोण को बदले। |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | यह स्थिरांक दर्शाता है कि इस वस्तु द्वारा परिभाषित परिवर्तन इनपुट निर्देशांक का मनमाना रूपांतरण करता है। |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | एक पहचान परिवर्तन वह है जिसमें आउटपुट निर्देशांक हमेशा इनपुट निर्देशांक के समान होते हैं। |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | यह स्थिरांक किसी भी घूर्णन फ़्लैग बिट के लिए बिट मास्क है। |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | यह स्थिरांक किसी भी स्केल फ़्लैग बिट के लिए बिट मास्क है। |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | यह फ़्लैग बिट दर्शाता है कि इस वस्तु द्वारा परिभाषित परिवर्तन अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों के अतिरिक्त 90 डिग्री के किसी गुणक द्वारा क्वाड्रेंट घूर्णन करता है। |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | एक अनुवाद x और y में निर्देशांक को एक स्थिर मात्रा से स्थानांतरित करता है बिना वेक्टर की लंबाई या कोण बदले। |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | एक समान स्केल वेक्टर की लंबाई को x और y दोनों दिशाओं में समान मात्रा से गुणा करता है बिना वेक्टर के बीच के कोण को बदले। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट  System.Object  इस इंस्टेंस के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | मैट्रिक्स तत्वों की प्रतिलिपि प्राप्त करता है। |
| [getM11()](#getM11--) | पहली पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। |
| [getM12()](#getM12--) | पहली पंक्ति दूसरी कॉलम में मैट्रिक्स तत्व प्राप्त करता है। |
| [getM21()](#getM21--) | दूसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। |
| [getM22()](#getM22--) | दूसरी पंक्ति दूसरी कॉलम में मैट्रिक्स तत्व प्राप्त करता है। |
| [getM31()](#getM31--) | तीसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। |
| [getM32()](#getM32--) | तीसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | निर्धारित करता है कि दो मैट्रिक्स समान हैं या नहीं। |
| [isIdentity()](#isIdentity--) | `true` लौटाता है यदि यह `AffineTransform` एक पहचान परिवर्तन है। |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | इस मैट्रिक्स को पैरामीटर में निर्दिष्ट मैट्रिक्स से (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके गुणा करता है। |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | इस मैट्रिक्स को पैरामीटर में निर्दिष्ट मैट्रिक्स से, और order पैरामीटर में निर्दिष्ट क्रम में गुणा करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | इस मैट्रिक्स को पहचान मैट्रिक्स के तत्वों के साथ रीसेट करता है। |
| [rotate(float angle)](#rotate-float-) | इस मैट्रिक्स पर डिफ़ॉल्ट (Prepend) क्रम में कोण पैरामीटर में निर्दिष्ट मात्रा का घड़ी की दिशा में घूर्णन लागू करता है, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर। |
| [rotate(float angle, int order)](#rotate-float-int-) | इस मैट्रिक्स पर निर्दिष्ट क्रम में कोण पैरामीटर में निर्दिष्ट मात्रा का घड़ी की दिशा में घूर्णन लागू करता है, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर। |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | निर्दिष्ट बिंदु के बारे में घड़ी की दिशा में घूर्णन इस मैट्रिक्स पर डिफ़ॉल्ट (Prepend) क्रम में लागू करता है। |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | निर्दिष्ट बिंदु के बारे में घड़ी की दिशा में घूर्णन इस मैट्रिक्स पर निर्दिष्ट क्रम में लागू करता है। |
| [scale(float sx, float sy)](#scale-float-float-) | निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) को इस मैट्रिक्स पर (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके लागू करता है। |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) को इस  Matrix  पर निर्दिष्ट क्रम का उपयोग करके लागू करता है। |
| [toString()](#toString--) | एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | इस  Matrix  द्वारा प्रतिनिधित्व किए गए ज्यामितीय परिवर्तन को बिंदुओं की निर्दिष्ट सरणी पर लागू करता है। |
| [translate(float tx, float ty)](#translate-float-float-) | निर्दिष्ट अनुवाद वेक्टर को इस  Matrix  पर (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके लागू करता है। |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | निर्दिष्ट अनुवाद वेक्टर को इस Matrix पर निर्दिष्ट क्रम में लागू करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix क्लास का नया इंस्टेंस पहचान मैट्रिक्स के रूप में इनिशियलाइज़ करता है।

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Matrix क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| m11 | float | m00 M11 स्केल X |
| m12 | float | m10 M12 शियर Y |
| m21 | float | m01 M21 शियर X |
| m22 | float | m11 M22 स्केल Y |
| m31 | float | m02 M31 ट्रांसलेट X |
| m32 | float | m12 M32 ट्रांसलेट Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Matrix क्लास की एक कॉपी बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | कोपिंग के लिए बेस मैट्रिक्स |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Aspose.Imaging.Matrix क्लास का नया इंस्टेंस निर्दिष्ट आयत और बिंदुओं के एरे द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्म के लिए इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  Aspose.Imaging.RectangleF  संरचना जो परिवर्तित किए जाने वाले आयत को दर्शाती है। |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | तीन  Aspose.Imaging.PointF  संरचनाओं की एक सरणी जो उस समानांतर चतुर्भुज के बिंदुओं को दर्शाती है, जिसमें आयत के ऊपर-बाएँ, ऊपर-दाएँ और नीचे-बाएँ कोने परिवर्तित किए जाएंगे। समानांतर चतुर्भुज का नीचे-दाएँ कोना पहले तीन कोनों से अनुमानित होता है। |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Aspose.Imaging.Matrix क्लास का नया इंस्टेंस निर्दिष्ट आयत और बिंदुओं के एरे द्वारा परिभाषित ज्यामितीय ट्रांसफ़ॉर्म के लिए इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | एक  Aspose.Imaging.Rectangle  संरचना जो परिवर्तित किए जाने वाले आयत को दर्शाती है। |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | तीन  Aspose.Imaging.Point  संरचनाओं की एक सरणी जो उस समानांतर चतुर्भुज के बिंदुओं को दर्शाती है, जिसमें आयत के ऊपर-बाएँ, ऊपर-दाएँ और नीचे-बाएँ कोने परिवर्तित किए जाएंगे। समानांतर चतुर्भुज का नीचे-दाएँ कोना पहले तीन कोनों से अनुमानित होता है। |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म कुछ अक्ष के बारे में मिरर इमेज फ़्लिप करता है, जो सामान्यतः दाएँ‑हाथ कोऑर्डिनेट सिस्टम को बाएँ‑हाथ सिस्टम में बदल देता है, साथ ही अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों को भी लागू करता है। दाएँ‑हाथ कोऑर्डिनेट सिस्टम वह है जहाँ सकारात्मक X अक्ष प्रतिक्लॉकवाइज़ घुमता है ताकि वह सकारात्मक Y अक्ष के ऊपर ओवरले हो, जैसे आपके दाएँ हाथ की उंगलियों का मुड़ना जब आप अपने अंगूठे को सीधे देखते हैं। बाएँ‑हाथ कोऑर्डिनेट सिस्टम वह है जहाँ सकारात्मक X अक्ष क्लॉकवाइज़ घुमता है ताकि वह सकारात्मक Y अक्ष के ऊपर ओवरले हो, जैसे आपके बाएँ हाथ की उंगलियों का मुड़ना। मूल फ़्लिप या मिररिंग ट्रांसफ़ॉर्म का कोण निर्धारित करने का कोई गणितीय तरीका नहीं है क्योंकि सभी फ़्लिप कोण समान होते हैं जब उपयुक्त समायोजित घूर्णन लागू किया जाता है। नोट: TypeFlip को GENERAL_TRANSFORM के सार्वजनिक उपयोग के बाद जोड़ा गया था और फ़्लैग बिट्स को बिना बाइनरी असंगतता लाए पुनः क्रमांकित नहीं किया जा सकता।

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों के अतिरिक्त एक मनमाना कोण द्वारा घूर्णन करता है। घूर्णन वेक्टर के कोण को समान मात्रा में बदलता है, चाहे वेक्टर की मूल दिशा कुछ भी हो, और वेक्टर की लंबाई को नहीं बदलता। यह फ़्लैग बिट इसके साथ परस्पर अनन्य है।

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


एक सामान्य स्केल वेक्टर की लंबाई को x और y दिशाओं में अलग-अलग मात्राओं से गुणा करता है, बिना लम्बवत वेक्टरों के बीच के कोण को बदले। यह फ़्लैग बिट TypeUniformScale फ़्लैग के साथ परस्पर अनन्य है।

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


यह स्थिरांक दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म इनपुट कोऑर्डिनेट्स का मनमाना रूपांतरण करता है। यदि इस ट्रांसफ़ॉर्म को ऊपर दिए गए किसी भी स्थिरांक द्वारा वर्गीकृत किया जा सकता है, तो प्रकार या तो स्थिरांक TypeIdentity होगा या विभिन्न कोऑर्डिनेट रूपांतरणों के लिए उपयुक्त फ़्लैग बिट्स का संयोजन होगा जो यह ट्रांसफ़ॉर्म करता है।

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


एक आइडेंटिटी ट्रांसफ़ॉर्म वह है जिसमें आउटपुट कोऑर्डिनेट्स हमेशा इनपुट कोऑर्डिनेट्स के समान होते हैं। यदि यह ट्रांसफ़ॉर्म आइडेंटिटी ट्रांसफ़ॉर्म नहीं है, तो प्रकार या तो स्थिरांक GENERAL_TRANSFORM होगा या विभिन्न कोऑर्डिनेट रूपांतरणों के लिए उपयुक्त फ़्लैग बिट्स का संयोजन होगा जो यह ट्रांसफ़ॉर्म करता है।

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


यह स्थिरांक किसी भी घूर्णन फ़्लैग बिट के लिए बिट मास्क है।

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


यह स्थिरांक किसी भी स्केल फ़्लैग बिट के लिए बिट मास्क है।

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


यह फ़्लैग बिट दर्शाता है कि इस ऑब्जेक्ट द्वारा परिभाषित ट्रांसफ़ॉर्म अन्य फ़्लैग बिट्स द्वारा संकेतित रूपांतरणों के अतिरिक्त 90 डिग्री के किसी गुणक द्वारा क्वाड्रेंट घूर्णन करता है। घूर्णन वेक्टर के कोण को समान मात्रा में बदलता है, चाहे वेक्टर की मूल दिशा कुछ भी हो, और वेक्टर की लंबाई को नहीं बदलता। यह फ़्लैग बिट TypeGeneralRotation फ़्लैग के साथ परस्पर अनन्य है।

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


एक अनुवाद x और y में निर्देशांक को एक स्थिर मात्रा से स्थानांतरित करता है बिना वेक्टर की लंबाई या कोण बदले।

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


एक समान स्केल वेक्टरों की लंबाई को x और y दोनों दिशाओं में समान मात्रा से गुणा करता है, बिना वेक्टरों के बीच के कोण को बदले। यह फ़्लैग बिट TypeGeneralScale फ़्लैग के साथ आपस में अनन्य है।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट  System.Object  इस इंस्टेंस के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण से तुलना करने के लिए  **System.Object**  । |

**Returns:**
boolean - true यदि निर्दिष्ट System.Object इस उदाहरण के बराबर है; अन्यथा false।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


मैट्रिक्स तत्वों की प्रतिलिपि प्राप्त करता है।

**Returns:**
float[] - एक मैट्रिक्स तत्वों की प्रतिलिपि।
### getM11() {#getM11--}
```
public float getM11()
```


पहली पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। X अक्ष के साथ स्केल को दर्शाता है।

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


पहली पंक्ति दूसरी कॉलम में मैट्रिक्स तत्व प्राप्त करता है। Y अक्ष के साथ शियर को दर्शाता है।

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


दूसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। X अक्ष के साथ शियर को दर्शाता है।

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


दूसरी पंक्ति दूसरी कॉलम में मैट्रिक्स तत्व प्राप्त करता है। Y अक्ष के साथ स्केल को दर्शाता है।

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


तीसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। X अक्ष के साथ अनुवाद को दर्शाता है।

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


तीसरी पंक्ति पहली कॉलम में मैट्रिक्स तत्व प्राप्त करता है। Y अक्ष के साथ अनुवाद को दर्शाता है।

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


निर्धारित करता है कि दो मैट्रिक्स समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | पहला मैट्रिक्स तुलना के लिए। |
| b | [Matrix](../../com.aspose.psd/matrix) | दूसरा मैट्रिक्स तुलना के लिए। |

**Returns:**
boolean - यदि मैट्रिक्स समान हैं तो True।
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


`true` लौटाता है यदि यह `AffineTransform` एक पहचान परिवर्तन है।

**Returns:**
boolean - यदि यह `AffineTransform` एक पहचान परिवर्तन है तो `true`; अन्यथा `false`।
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


इस मैट्रिक्स को पैरामीटर में निर्दिष्ट मैट्रिक्स से (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | गुणा करने के लिए मैट्रिक्स। |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


इस मैट्रिक्स को पैरामीटर में निर्दिष्ट मैट्रिक्स से, और order पैरामीटर में निर्दिष्ट क्रम में गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | tx। tx। tx। |
| order | int | क्रम। क्रम। क्रम। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


इस मैट्रिक्स को पहचान मैट्रिक्स के तत्वों के साथ रीसेट करता है।

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


इस मैट्रिक्स पर डिफ़ॉल्ट (Prepend) क्रम में कोण पैरामीटर में निर्दिष्ट मात्रा का घड़ी की दिशा में घूर्णन लागू करता है, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव कोण। |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


इस मैट्रिक्स पर निर्दिष्ट क्रम में कोण पैरामीटर में निर्दिष्ट मात्रा का घड़ी की दिशा में घूर्णन लागू करता है, मूल बिंदु (शून्य x और y निर्देशांक) के चारों ओर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव कोण। |
| order | int | मैट्रिक्स क्रम। |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


निर्दिष्ट बिंदु के बारे में घड़ी की दिशा में घूर्णन इस मैट्रिक्स पर डिफ़ॉल्ट (Prepend) क्रम में लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | कोण। |
| point | [PointF](../../com.aspose.psd/pointf) | बिंदु। |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


निर्दिष्ट बिंदु के बारे में घड़ी की दिशा में घूर्णन इस मैट्रिक्स पर निर्दिष्ट क्रम में लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | कोण। |
| point | [PointF](../../com.aspose.psd/pointf) | बिंदु। |
| order | int | क्रम। |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) को इस मैट्रिक्स पर (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | sx। sx। sx। |
| sy | float | sy। sy। sy। |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


निर्दिष्ट स्केल वेक्टर (scaleX और scaleY) को इस  Matrix  पर निर्दिष्ट क्रम का उपयोग करके लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | float | स्केल X। |
| scaleY | float | स्केल Y। |
| order | int | क्रम। |

### toString() {#toString--}
```
public String toString()
```


एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है।

**Returns:**
java.lang.String - एक  System.String  जो इस उदाहरण का प्रतिनिधित्व करता है।
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


इस  Matrix  द्वारा प्रतिनिधित्व किए गए ज्यामितीय परिवर्तन को बिंदुओं की निर्दिष्ट सरणी पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | बिंदु। |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


निर्दिष्ट अनुवाद वेक्टर को इस  Matrix  पर (डिफ़ॉल्ट) Prepend क्रम का उपयोग करके लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tx | float | tx। tx। tx। |
| ty | float | ty। ty। ty। |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


निर्दिष्ट अनुवाद वेक्टर को इस Matrix पर निर्दिष्ट क्रम में लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| offsetX | float | ऑफ़सेट X। |
| offsetY | float | ऑफ़सेट Y। |
| order | int | क्रम। |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


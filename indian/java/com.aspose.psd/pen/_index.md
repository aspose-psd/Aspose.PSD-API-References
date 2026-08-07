---
title: "Pen"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक वस्तु को परिभाषित करता है जिसका उपयोग रेखाएँ, वक्र और आकृतियों को खींचने के लिए किया जाता है।"
type: docs
weight: 77
url: /hi/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

लाइन, कर्व और फ़िगर ड्रॉ करने के लिए उपयोग किए जाने वाले ऑब्जेक्ट को परिभाषित करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | निर्दिष्ट रंग के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | निर्दिष्ट Color और Pen.Width गुणों के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | निर्दिष्ट Brush के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | निर्दिष्ट Brush और Pen.Width के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | इस Pen के लिए संरेखण प्राप्त करता है। |
| [getBrush()](#getBrush--) | इस Pen के गुणों को निर्धारित करने वाले Brush को प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | इस Pen का रंग प्राप्त करता है। |
| [getCompoundArray()](#getCompoundArray--) | एक मानों का एरे प्राप्त करता है जो एक संयुक्त पेन को निर्दिष्ट करता है। |
| [getCustomEndCap()](#getCustomEndCap--) | इस Pen के साथ खींची गई रेखाओं के अंत में उपयोग करने के लिए एक कस्टम कैप प्राप्त करता है। |
| [getCustomStartCap()](#getCustomStartCap--) | इस Pen के साथ खींची गई रेखाओं की शुरुआत में उपयोग करने के लिए एक कस्टम कैप प्राप्त करता है। |
| [getDashCap()](#getDashCap--) | इस Pen के साथ खींची गई डैश्ड रेखाओं को बनाने वाले डैश के अंत में उपयोग किया जाने वाला कैप शैली प्राप्त करता है। |
| [getDashOffset()](#getDashOffset--) | एक रेखा की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी प्राप्त करता है। |
| [getDashPattern()](#getDashPattern--) | कस्टम डैश और स्पेस का एरे प्राप्त करता है। |
| [getDashStyle()](#getDashStyle--) | इस Pen के साथ खींची गई डैश्ड रेखाओं के लिए उपयोग की गई शैली प्राप्त करता है। |
| [getEndCap()](#getEndCap--) | इस Pen के साथ खींची गई रेखाओं के अंत में उपयोग किया गया कैप शैली प्राप्त करता है। |
| [getLineJoin()](#getLineJoin--) | इस Pen के साथ खींची गई दो क्रमिक रेखाओं के अंतों के लिए जॉइन शैली प्राप्त करता है। |
| [getMiterLimit()](#getMiterLimit--) | एक मिटर कोने पर जॉइन की मोटाई की सीमा प्राप्त करता है। |
| [getOpacity()](#getOpacity--) | ऑब्जेक्ट की अपारदर्शिता प्राप्त करता है। |
| [getPenType()](#getPenType--) | इस Pen के साथ खींची गई रेखाओं की शैली प्राप्त करता है। |
| [getStartCap()](#getStartCap--) | इस Pen के साथ खींची गई रेखाओं की शुरुआत में उपयोग किया गया कैप शैली प्राप्त करता है। |
| [getTransform()](#getTransform--) | इस Pen के लिए ज्यामितीय रूपांतरण की एक प्रति प्राप्त करता है। |
| [getWidth()](#getWidth--) | ड्रॉइंग के लिए उपयोग किए गए Graphics वस्तु की इकाइयों में इस Pen की चौड़ाई प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | इस Pen के रूपांतरण मैट्रिक्स को निर्दिष्ट Matrix द्वारा गुणा करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | इस Pen के रूपांतरण मैट्रिक्स को निर्दिष्ट क्रम में निर्दिष्ट Matrix द्वारा गुणा करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | इस  Pen  के लिए ज्यामितीय परिवर्तन मैट्रिक्स को पहचान पर रीसेट करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | निर्दिष्ट कोण द्वारा स्थानीय ज्यामितीय परिवर्तन को घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट कोण द्वारा स्थानीय ज्यामितीय परिवर्तन को घुमाता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | निर्दिष्ट गुणकों द्वारा स्थानीय ज्यामितीय परिवर्तन को स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट गुणकों द्वारा स्थानीय ज्यामितीय परिवर्तन को स्केल करता है। |
| [setAlignment(int value)](#setAlignment-int-) | इस  Pen  के लिए संरेखण सेट करता है। |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | इस  Pen  के गुणों को निर्धारित करने वाले  Brush  को सेट करता है। |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | इस  Pen  का रंग सेट करता है। |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | एक संयोजन पेन को निर्दिष्ट करने वाले मानों की एक सरणी सेट करता है। |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | इस  Pen  से खींची गई लाइनों के अंत में उपयोग करने के लिए एक कस्टम कैप सेट करता है। |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | इस  Pen  से खींची गई लाइनों की शुरुआत में उपयोग करने के लिए एक कस्टम कैप सेट करता है। |
| [setDashCap(int value)](#setDashCap-int-) | इस  Pen  से खींची गई डैश्ड लाइनों को बनाने वाले डैश के अंत में उपयोग किए जाने वाले कैप शैली को सेट करता है। |
| [setDashOffset(float value)](#setDashOffset-float-) | एक लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी सेट करता है। |
| [setDashPattern(float[] value)](#setDashPattern-float---) | कस्टम डैश और स्पेस की एक सरणी सेट करता है। |
| [setDashStyle(int value)](#setDashStyle-int-) | इस  Pen  से खींची गई डैश्ड लाइनों के लिए उपयोग की जाने वाली शैली सेट करता है। |
| [setEndCap(int value)](#setEndCap-int-) | इस  Pen  से खींची गई लाइनों के अंत में उपयोग की जाने वाली कैप शैली सेट करता है। |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | इस  Pen  द्वारा खींची गई लाइनों को समाप्त करने के लिए उपयोग किए जाने वाले कैप शैली को निर्धारित करने वाले मान सेट करता है। |
| [setLineJoin(int value)](#setLineJoin-int-) | इस  Pen  से खींची गई दो क्रमिक लाइनों के अंत के लिए जॉइन शैली सेट करता है। |
| [setMiterLimit(float value)](#setMiterLimit-float-) | एक मिटर कोने पर जॉइन की मोटाई की सीमा सेट करता है। |
| [setOpacity(float value)](#setOpacity-float-) | ऑब्जेक्ट की अपारदर्शिता सेट करता है। |
| [setStartCap(int value)](#setStartCap-int-) | इस  Pen  से खींची गई लाइनों की शुरुआत में उपयोग की जाने वाली कैप शैली सेट करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | इस  Pen  के लिए ज्यामितीय परिवर्तन की एक प्रति सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | ड्रॉइंग के लिए उपयोग किए गए Graphics ऑब्जेक्ट की इकाइयों में इस  Pen  की चौड़ाई सेट करता है। |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन को ट्रांसलेट करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन को ट्रांसलेट करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


निर्दिष्ट रंग के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | एक  Color  संरचना जो इस  Pen  का रंग दर्शाती है। |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


निर्दिष्ट Color और Pen.Width गुणों के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | एक  Color  संरचना जो इस  Pen  का रंग दर्शाती है। |
| width | float | इस Pen की चौड़ाई दर्शाने वाला मान। |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


निर्दिष्ट Brush के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | एक Brush जो इस Pen की भराव गुणों को निर्धारित करता है। |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


निर्दिष्ट Brush और Pen.Width के साथ Pen वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | एक Brush जो इस Pen की विशेषताओं को निर्धारित करता है। |
| width | float | नए Pen की चौड़ाई। |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


इस Pen के लिए संरेखण प्राप्त करता है।

**Returns:**
int - एक PenAlignment जो इस Pen के संरेखण को दर्शाता है।
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


इस Pen के गुणों को निर्धारित करने वाले Brush को प्राप्त करता है।

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


इस Pen का रंग प्राप्त करता है।

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


एक मानों की सरणी प्राप्त करता है जो एक compound pen को निर्दिष्ट करती है। एक compound pen समानांतर रेखाओं और अंतरालों से बनी एक संयुक्त रेखा बनाता है।

**Returns:**
float[] - वास्तविक संख्याओं की एक सरणी जो compound array को निर्दिष्ट करती है। सरणी के तत्व बढ़ते क्रम में होने चाहिए, 0 से कम नहीं और 1 से अधिक नहीं।
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


इस Pen के साथ खींची गई रेखाओं के अंत में उपयोग करने के लिए एक कस्टम कैप प्राप्त करता है।

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


इस Pen के साथ खींची गई रेखाओं की शुरुआत में उपयोग करने के लिए एक कस्टम कैप प्राप्त करता है।

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


इस Pen के साथ खींची गई डैश्ड रेखाओं को बनाने वाले डैश के अंत में उपयोग किया जाने वाला कैप शैली प्राप्त करता है।

**Returns:**
int - DashCap मानों में से एक जो इस Pen द्वारा खींची गई डैश्ड लाइनों के डैश की शुरुआत और अंत में उपयोग किए जाने वाले कैप शैली को दर्शाता है।
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


एक रेखा की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी प्राप्त करता है।

**Returns:**
float - एक रेखा की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी।
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


कस्टम डैश और स्पेस का एरे प्राप्त करता है।

**Returns:**
float[] - वास्तविक संख्याओं की एक सरणी जो डैश्ड लाइनों में वैकल्पिक डैश और स्पेस की लंबाइयों को निर्दिष्ट करती है।
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


इस Pen के साथ खींची गई डैश्ड रेखाओं के लिए उपयोग की गई शैली प्राप्त करता है।

**Returns:**
int - एक DashStyle जो इस Pen द्वारा खींची गई डैश्ड लाइनों के लिए उपयोग की गई शैली को दर्शाता है।
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


इस Pen के साथ खींची गई रेखाओं के अंत में उपयोग किया गया कैप शैली प्राप्त करता है।

**Returns:**
int - LineCap मानों में से एक जो इस Pen द्वारा खींची गई लाइनों के अंत में उपयोग किए जाने वाले कैप शैली को दर्शाता है।
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


इस Pen के साथ खींची गई दो क्रमिक रेखाओं के अंतों के लिए जॉइन शैली प्राप्त करता है।

**Returns:**
int - एक LineJoin जो इस Pen द्वारा खींची गई दो क्रमिक लाइनों के अंतों के जुड़ाव शैली को दर्शाता है।
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


एक मिटर कोने पर जॉइन की मोटाई की सीमा प्राप्त करता है।

**Returns:**
float - मिटर कोने पर जुड़ाव की मोटाई की सीमा।
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


ऑब्जेक्ट की अपारदर्शिता प्राप्त करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान दर्शाता है कि ऑब्जेक्ट पूरी तरह दृश्यमान है, 1 का मान दर्शाता है कि ऑब्जेक्ट पूरी तरह अपारदर्शी है।

**Returns:**
float - अपारदर्शिता मान।
### getPenType() {#getPenType--}
```
public int getPenType()
```


इस Pen के साथ खींची गई रेखाओं की शैली प्राप्त करता है।

**Returns:**
int - एक PenType enumeration जो इस Pen द्वारा खींची गई लाइनों की शैली को निर्दिष्ट करता है।
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


इस Pen के साथ खींची गई रेखाओं की शुरुआत में उपयोग किया गया कैप शैली प्राप्त करता है।

**Returns:**
int - LineCap मानों में से एक जो इस Pen द्वारा खींची गई लाइनों की शुरुआत में उपयोग किए जाने वाले कैप शैली को दर्शाता है।
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


इस Pen के लिए ज्यामितीय रूपांतरण की एक प्रति प्राप्त करता है।

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


ड्रॉइंग के लिए उपयोग किए गए Graphics वस्तु की इकाइयों में इस Pen की चौड़ाई प्राप्त करता है।

**Returns:**
float - इस Pen की चौड़ाई।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


इस Pen के रूपांतरण मैट्रिक्स को निर्दिष्ट Matrix द्वारा गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | परिवर्तन मैट्रिक्स को गुणा करने के लिए Matrix ऑब्जेक्ट। |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


इस Pen के रूपांतरण मैट्रिक्स को निर्दिष्ट क्रम में निर्दिष्ट Matrix द्वारा गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | परिवर्तन मैट्रिक्स को गुणा करने के लिए Matrix। |
| order | int | गुणा ऑपरेशन को करने का क्रम। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


इस  Pen  के लिए ज्यामितीय परिवर्तन मैट्रिक्स को पहचान पर रीसेट करता है।

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


स्थानीय ज्यामितीय परिवर्तन को निर्दिष्ट कोण से घुमाता है। यह विधि घूर्णन को परिवर्तन के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट कोण द्वारा स्थानीय ज्यामितीय परिवर्तन को घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |
| order | int | एक MatrixOrder जो यह निर्दिष्ट करता है कि घूर्णन मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


स्थानीय ज्यामितीय परिवर्तन को निर्दिष्ट गुणकों से स्केल करता है। यह विधि स्केलिंग मैट्रिक्स को परिवर्तन के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में परिवर्तन को स्केल करने का गुणक। |
| sy | float | y-अक्ष दिशा में परिवर्तन को स्केल करने का गुणक। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट गुणकों द्वारा स्थानीय ज्यामितीय परिवर्तन को स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में परिवर्तन को स्केल करने का गुणक। |
| sy | float | y-अक्ष दिशा में परिवर्तन को स्केल करने का गुणक। |
| order | int | एक MatrixOrder जो यह निर्दिष्ट करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले लगाना है। |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


इस  Pen  के लिए संरेखण सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | एक PenAlignment जो इस Pen की संरेखण को दर्शाता है। |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


इस  Pen  के गुणों को निर्धारित करने वाले  Brush  को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | एक Brush जो इस Pen के गुणों को निर्धारित करता है। |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


इस  Pen  का रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | एक Color संरचना जो इस Pen का रंग दर्शाती है। |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


एक मानों की सरणी सेट करता है जो एक compound pen को निर्दिष्ट करती है। एक compound pen समानांतर रेखाओं और अंतरालों से बनी एक संयुक्त रेखा बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float[] | वास्तविक संख्याओं की एक सरणी जो compound array को निर्दिष्ट करती है। सरणी के तत्व बढ़ते क्रम में होने चाहिए, 0 से कम नहीं और 1 से अधिक नहीं। |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


इस  Pen  से खींची गई लाइनों के अंत में उपयोग करने के लिए एक कस्टम कैप सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | एक CustomLineCap जो इस Pen से खींची गई रेखाओं के अंत में उपयोग किए जाने वाले कैप को दर्शाता है। |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


इस  Pen  से खींची गई लाइनों की शुरुआत में उपयोग करने के लिए एक कस्टम कैप सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | एक CustomLineCap जो इस Pen से खींची गई रेखाओं की शुरुआत में उपयोग किए जाने वाले कैप को दर्शाता है। |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


इस  Pen  से खींची गई डैश्ड लाइनों को बनाने वाले डैश के अंत में उपयोग किए जाने वाले कैप शैली को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | DashCap मानों में से एक जो इस Pen से खींची गई डैश्ड लाइनों में डैश की शुरुआत और अंत में उपयोग किए जाने वाले कैप शैली को दर्शाता है। |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


एक लाइन की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | एक रेखा की शुरुआत से डैश पैटर्न की शुरुआत तक की दूरी। |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


कस्टम डैश और स्पेस की एक सरणी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float[] | वास्तविक संख्याओं की एक सरणी जो डैश्ड लाइनों में वैकल्पिक डैश और स्पेस की लंबाई को निर्दिष्ट करती है। |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


इस  Pen  से खींची गई डैश्ड लाइनों के लिए उपयोग की जाने वाली शैली सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | एक DashStyle जो इस Pen से खींची गई डैश्ड लाइनों के लिए उपयोग की जाने वाली शैली को दर्शाता है। |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


इस  Pen  से खींची गई लाइनों के अंत में उपयोग की जाने वाली कैप शैली सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | LineCap मानों में से एक जो इस Pen से खींची गई रेखाओं के अंत में उपयोग किए जाने वाले कैप शैली को दर्शाता है। |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


इस  Pen  द्वारा खींची गई लाइनों को समाप्त करने के लिए उपयोग किए जाने वाले कैप शैली को निर्धारित करने वाले मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startCap | int | एक LineCap जो इस Pen से खींची गई रेखाओं की शुरुआत में उपयोग किए जाने वाले कैप शैली को दर्शाता है। |
| endCap | int | एक LineCap जो इस Pen से खींची गई रेखाओं के अंत में उपयोग किए जाने वाले कैप शैली को दर्शाता है। |
| dashCap | int | एक LineCap जो इस Pen से खींची गई डैश्ड लाइनों की शुरुआत या अंत में उपयोग किए जाने वाले कैप शैली को दर्शाता है। |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


इस  Pen  से खींची गई दो क्रमिक लाइनों के अंत के लिए जॉइन शैली सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | एक LineJoin जो इस Pen से खींची गई दो क्रमिक रेखाओं के अंतों के लिए जॉइन शैली को दर्शाता है। |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


एक मिटर कोने पर जॉइन की मोटाई की सीमा सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | मिटर्ड कोने पर जॉइन की मोटाई की सीमा। |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


ऑब्जेक्ट की अपारदर्शिता सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान दर्शाता है कि ऑब्जेक्ट पूरी तरह दृश्यमान है, 1 का मान दर्शाता है कि ऑब्जेक्ट पूरी तरह अपारदर्शी है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | अपारदर्शिता मान। |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


इस  Pen  से खींची गई लाइनों की शुरुआत में उपयोग की जाने वाली कैप शैली सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | LineCap मानों में से एक जो इस Pen से खींची गई रेखाओं की शुरुआत में उपयोग किए जाने वाले कैप शैली को दर्शाता है। |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


इस  Pen  के लिए ज्यामितीय परिवर्तन की एक प्रति सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | एक Matrix की प्रतिलिपि जो इस Pen के लिए ज्यामितीय परिवर्तन को दर्शाती है। |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


ड्रॉइंग के लिए उपयोग किए गए Graphics ऑब्जेक्ट की इकाइयों में इस  Pen  की चौड़ाई सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | इस Pen की चौड़ाई। |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन को अनुवादित करता है। यह विधि अनुवाद को परिवर्तन के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | x में अनुवाद का मान। |
| dy | float | y में अनुवाद का मान। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय परिवर्तन को ट्रांसलेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | x में अनुवाद का मान। |
| dy | float | y में अनुवाद का मान। |
| order | int | अनुवाद लागू करने का क्रम (पहले जोड़ना या बाद में जोड़ना)। |

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


---
title: "RectangleF"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक आयत के स्थान और आकार को दर्शाने वाले चार फ़्लोटिंग‑पॉइंट संख्याओं का सेट संग्रहीत करता है।"
type: docs
weight: 89
url: /hi/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

एक आयत के स्थान और आकार को दर्शाने वाले चार फ़्लोटिंग‑पॉइंट संख्याओं का सेट संग्रहीत करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | निर्दिष्ट स्थान और आकार के साथ  com.aspose.psd.RectangleF  संरचना का नया उदाहरण आरंभ करता है। |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | निर्दिष्ट स्थान और आकार के साथ  com.aspose.psd.RectangleF  संरचना का नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस  com.aspose.psd.RectangleF  संरचना में सम्मिलित है। |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | निर्धारित करता है कि क्या  rect  द्वारा दर्शाया गया आयताकार क्षेत्र पूरी तरह से इस  com.aspose.psd.RectangleF  संरचना में सम्मिलित है। |
| [contains(float x, float y)](#contains-float-float-) | निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस  com.aspose.psd.RectangleF  संरचना में सम्मिलित है। |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | वर्तमान आयत मानों को विभाजित करके मैट्रिक्स के लंबवत और क्षैतिज स्केल मानों को परिवर्तित करता है और परिणाम मानों के साथ एक नया [RectangleF](../../com.aspose.psd/rectanglef) उदाहरण लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | परीक्षण करता है कि क्या  obj  इस  com.aspose.psd.RectangleF  के समान स्थान और आकार वाला  com.aspose.psd.RectangleF  है। |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | निर्दिष्ट स्थानों पर ऊपरी-बाएँ और निचले-दाएँ कोने के साथ एक  com.aspose.psd.RectangleF  संरचना बनाता है। |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | निर्दिष्ट दो बिंदुओं से एक नया  Rectangle  बनाता है। |
| [getBottom()](#getBottom--) | इस  com.aspose.psd.RectangleF  संरचना के  com.aspose.psd.RectangleF.Y  और  com.aspose.psd.RectangleF.Height  के योग के रूप में y-निर्देशांक प्राप्त करता या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | एक नया  com.aspose.psd.RectangleF  संरचना प्राप्त करता है जिसमें  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  और  com.aspose.psd.RectangleF.Height  मान शून्य पर सेट होते हैं। |
| [getHeight()](#getHeight--) | इस  com.aspose.psd.RectangleF  संरचना की ऊँचाई प्राप्त करता या सेट करता है। |
| [getLeft()](#getLeft--) | इस  com.aspose.psd.RectangleF  संरचना के बाएँ किनारे के x-निर्देशांक को प्राप्त करता या सेट करता है। |
| [getLocation()](#getLocation--) | इस  com.aspose.psd.RectangleF  संरचना के ऊपरी-बाएँ कोने के निर्देशांक को प्राप्त करता या सेट करता है। |
| [getRight()](#getRight--) | इस com.aspose.psd.RectangleF संरचना के com.aspose.psd.RectangleF.X और com.aspose.psd.RectangleF.Width का योग होने वाला x-निर्देशांक प्राप्त करता है या सेट करता है। |
| [getSize()](#getSize--) | इस com.aspose.psd.RectangleF का आकार प्राप्त करता है या सेट करता है। |
| [getTop()](#getTop--) | इस com.aspose.psd.RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है या सेट करता है। |
| [getWidth()](#getWidth--) | इस com.aspose.psd.RectangleF संरचना की चौड़ाई प्राप्त करता है या सेट करता है। |
| [getX()](#getX--) | इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता है या सेट करता है। |
| [getY()](#getY--) | इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) | इस com.aspose.psd.RectangleF संरचना के लिए हैश कोड प्राप्त करता है। |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | निर्दिष्ट com.aspose.psd.RectangleF संरचना की विस्तारित प्रति बनाता है और लौटाता है। |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | इस com.aspose.psd.RectangleF को निर्दिष्ट मात्रा से विस्तारित करता है। |
| [inflate(float x, float y)](#inflate-float-float-) | इस com.aspose.psd.RectangleF संरचना को निर्दिष्ट मात्रा से विस्तारित करता है। |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | इस com.aspose.psd.RectangleF संरचना को स्वयं और निर्दिष्ट com.aspose.psd.RectangleF संरचना के प्रतिच्छेदन से बदलता है। |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | दो आयतों के प्रतिच्छेदन को दर्शाने वाली एक com.aspose.psd.RectangleF संरचना लौटाता है। |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | निर्धारित करता है कि यह आयत rect के साथ प्रतिच्छेद करती है या नहीं। |
| [isEmpty()](#isEmpty--) | यह प्राप्त करता है कि इस com.aspose.psd.RectangleF की com.aspose.psd.RectangleF.Width या com.aspose.psd.RectangleF.Height गुण का मान शून्य है या नहीं। |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | वर्तमान आयत मानों को गुणा करके मैट्रिक्स के लंबवत और क्षैतिज स्केल मानों को रूपांतरित करता है और परिणाम मानों के साथ एक नया [RectangleF](../../com.aspose.psd/rectanglef) इंस्टेंस लौटाता है। |
| [normalize()](#normalize--) | आयत को सामान्यीकृत करता है, इसकी चौड़ाई और ऊँचाई को सकारात्मक बनाकर, बायें को दायें से कम और ऊपर को नीचे से कम करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है। |
| [offset(float x, float y)](#offset-float-float-) | इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है। |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | / ऑपरेटर को लागू करता है। |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | परीक्षण करता है कि दो com.aspose.psd.RectangleF संरचनाओं का स्थान और आकार समान है या नहीं। |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | परीक्षण करता है कि दो com.aspose.psd.RectangleF संरचनाओं का स्थान या आकार अलग है या नहीं। |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | \* ऑपरेटर को लागू करता है। |
| [setBottom(float value)](#setBottom-float-) | इस  com.aspose.psd.RectangleF  संरचना के  com.aspose.psd.RectangleF.Y  और  com.aspose.psd.RectangleF.Height  के योग के रूप में y-निर्देशांक प्राप्त करता या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | इस  com.aspose.psd.RectangleF  संरचना की ऊँचाई प्राप्त करता या सेट करता है। |
| [setLeft(float value)](#setLeft-float-) | इस  com.aspose.psd.RectangleF  संरचना के बाएँ किनारे के x-निर्देशांक को प्राप्त करता या सेट करता है। |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | इस  com.aspose.psd.RectangleF  संरचना के ऊपरी-बाएँ कोने के निर्देशांक को प्राप्त करता या सेट करता है। |
| [setRight(float value)](#setRight-float-) | इस com.aspose.psd.RectangleF संरचना के com.aspose.psd.RectangleF.X और com.aspose.psd.RectangleF.Width का योग होने वाला x-निर्देशांक प्राप्त करता है या सेट करता है। |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | इस com.aspose.psd.RectangleF का आकार प्राप्त करता है या सेट करता है। |
| [setTop(float value)](#setTop-float-) | इस com.aspose.psd.RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | इस com.aspose.psd.RectangleF संरचना की चौड़ाई प्राप्त करता है या सेट करता है। |
| [setX(float value)](#setX-float-) | इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता है या सेट करता है। |
| [setY(float value)](#setY-float-) | इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता है या सेट करता है। |
| [toRectangle_internalized()](#toRectangle-internalized--) | [RectangleF](../../com.aspose.psd/rectanglef) को [Rectangle](../../com.aspose.psd/rectangle) संरचना में कटे हुए आयत मानों के साथ परिवर्तित करता है। |
| [toString()](#toString--) | इस com.aspose.psd.RectangleF के गुणों को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | निर्दिष्ट com.aspose.psd.Rectangle संरचना को एक com.aspose.psd.RectangleF संरचना में परिवर्तित करता है। |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | दो आयतों के संघ को समाहित करने वाली सबसे छोटी संभव तृतीय आयत बनाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


निर्दिष्ट स्थान और आकार के साथ  com.aspose.psd.RectangleF  संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | आयत के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| y | float | आयत के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| width | float | आयत की चौड़ाई। |
| height | float | आयत की ऊँचाई। |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


निर्दिष्ट स्थान और आकार के साथ  com.aspose.psd.RectangleF  संरचना का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | एक  com.aspose.psd.PointF  जो आयताकार क्षेत्र के ऊपरी-बाएँ कोने को दर्शाता है। |
| size | [SizeF](../../com.aspose.psd/sizef) | एक  com.aspose.psd.SizeF  जो आयताकार क्षेत्र की चौड़ाई और ऊँचाई को दर्शाता है। |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस  com.aspose.psd.RectangleF  संरचना में सम्मिलित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | परीक्षण के लिए  com.aspose.psd.PointF । |

**Returns:**
boolean - यह विधि true लौटाती है यदि  point  पैरामीटर द्वारा दर्शाया गया बिंदु इस  com.aspose.psd.RectangleF  संरचना के भीतर शामिल है; अन्यथा false।
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


निर्धारित करता है कि क्या  rect  द्वारा दर्शाया गया आयताकार क्षेत्र पूरी तरह से इस  com.aspose.psd.RectangleF  संरचना में सम्मिलित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | परीक्षण के लिए  com.aspose.psd.RectangleF । |

**Returns:**
boolean - यह विधि true लौटाती है यदि  rect  द्वारा दर्शाया गया आयताकार क्षेत्र पूरी तरह से इस  com.aspose.psd.RectangleF  द्वारा दर्शाए गए आयताकार क्षेत्र के भीतर शामिल है; अन्यथा false।
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


निर्धारित करता है कि क्या निर्दिष्ट बिंदु इस  com.aspose.psd.RectangleF  संरचना में सम्मिलित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |

**Returns:**
boolean - यह विधि true लौटाती है यदि  x  और  y  द्वारा परिभाषित बिंदु इस  com.aspose.psd.RectangleF  संरचना के भीतर शामिल है; अन्यथा false।
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


वर्तमान आयत मानों को विभाजित करके मैट्रिक्स के लंबवत और क्षैतिज स्केल मानों को परिवर्तित करता है और परिणाम मानों के साथ एक नया [RectangleF](../../com.aspose.psd/rectanglef) उदाहरण लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| transformMatrix | double[] | लेयर ट्रांसफ़ॉर्म मैट्रिक्स। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


परीक्षण करता है कि क्या  obj  इस  com.aspose.psd.RectangleF  के समान स्थान और आकार वाला  com.aspose.psd.RectangleF  है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण के लिए  System.Object । |

**Returns:**
boolean - यह विधि true लौटाती है यदि  obj  एक  com.aspose.psd.RectangleF  है और उसके X, Y, Width, और Height गुण इस  com.aspose.psd.RectangleF  के संबंधित गुणों के बराबर हैं; अन्यथा false।
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


निर्दिष्ट स्थानों पर ऊपरी-बाएँ और निचले-दाएँ कोने के साथ एक  com.aspose.psd.RectangleF  संरचना बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बायाँ | float | आयताकार क्षेत्र के ऊपरी-बाएँ कोने का x-निर्देशांक। |
| ऊपर | float | आयताकार क्षेत्र के ऊपरी-बाएँ कोने का y-निर्देशांक। |
| दाएँ | float | आयताकार क्षेत्र के निचले-दाएँ कोने का x-निर्देशांक। |
| नीचे | float | आयताकार क्षेत्र के निचले-दाएँ कोने का y-निर्देशांक। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


निर्दिष्ट दो बिंदुओं से एक नया Rectangle बनाता है। बनाए गए Rectangle के दो शीर्ष बिंदु पास किए गए point1 और point2 के बराबर होंगे। ये सामान्यतः विपरीत शीर्ष बिंदु होते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | नए rectangle के लिए पहला Point। |
| point2 | [PointF](../../com.aspose.psd/pointf) | नए rectangle के लिए दूसरा Point। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


इस  com.aspose.psd.RectangleF  संरचना के  com.aspose.psd.RectangleF.Y  और  com.aspose.psd.RectangleF.Height  के योग के रूप में y-निर्देशांक प्राप्त करता या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना के com.aspose.psd.RectangleF.Y और com.aspose.psd.RectangleF.Height का योग होने वाला y-निर्देशांक।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


एक नया  com.aspose.psd.RectangleF  संरचना प्राप्त करता है जिसमें  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  और  com.aspose.psd.RectangleF.Height  मान शून्य पर सेट होते हैं।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


इस  com.aspose.psd.RectangleF  संरचना की ऊँचाई प्राप्त करता या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना की ऊँचाई।
### getLeft() {#getLeft--}
```
public float getLeft()
```


इस  com.aspose.psd.RectangleF  संरचना के बाएँ किनारे के x-निर्देशांक को प्राप्त करता या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना के बाएँ किनारे का x-निर्देशांक।
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


इस  com.aspose.psd.RectangleF  संरचना के ऊपरी-बाएँ कोने के निर्देशांक को प्राप्त करता या सेट करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


इस com.aspose.psd.RectangleF संरचना के com.aspose.psd.RectangleF.X और com.aspose.psd.RectangleF.Width का योग होने वाला x-निर्देशांक प्राप्त करता है या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना के com.aspose.psd.RectangleF.X और com.aspose.psd.RectangleF.Width का योग होने वाला x-निर्देशांक।
### getSize() {#getSize--}
```
public SizeF getSize()
```


इस com.aspose.psd.RectangleF का आकार प्राप्त करता है या सेट करता है।

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


इस com.aspose.psd.RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक।
### getWidth() {#getWidth--}
```
public float getWidth()
```


इस com.aspose.psd.RectangleF संरचना की चौड़ाई प्राप्त करता है या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना की चौड़ाई।
### getX() {#getX--}
```
public float getX()
```


इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता है या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक।
### getY() {#getY--}
```
public float getY()
```


इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता है या सेट करता है।

**Returns:**
float - इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का y-निर्देशांक।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस com.aspose.psd.RectangleF संरचना के लिए हैश कोड प्राप्त करता है।

**Returns:**
int - इस com.aspose.psd.RectangleF का हैश कोड।
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


निर्दिष्ट com.aspose.psd.RectangleF संरचना की एक विस्तारित प्रति बनाता है और लौटाता है। प्रति को निर्दिष्ट मात्रा से विस्तारित किया जाता है। मूल rectangle अपरिवर्तित रहता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | कॉपी की जाने वाली com.aspose.psd.RectangleF। यह rectangle संशोधित नहीं किया जाता। |
| x | float | rectangle की प्रति को क्षैतिज रूप से विस्तारित करने की मात्रा। |
| y | float | rectangle की प्रति को लंबवत रूप से विस्तारित करने की मात्रा। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


इस com.aspose.psd.RectangleF को निर्दिष्ट मात्रा से विस्तारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | इस rectangle को विस्तारित करने की मात्रा। |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


इस com.aspose.psd.RectangleF संरचना को निर्दिष्ट मात्रा से विस्तारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | इस com.aspose.psd.RectangleF संरचना को क्षैतिज रूप से विस्तारित करने की मात्रा। |
| y | float | इस com.aspose.psd.RectangleF संरचना को लंबवत रूप से विस्तारित करने की मात्रा। |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


इस com.aspose.psd.RectangleF संरचना को स्वयं और निर्दिष्ट com.aspose.psd.RectangleF संरचना के प्रतिच्छेदन से बदलता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | इंटरसेक्ट करने के लिए rectangle। |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


दो rectangles के इंटरसेक्शन को दर्शाने वाली com.aspose.psd.RectangleF संरचना लौटाता है। यदि कोई इंटरसेक्शन नहीं है, तो एक खाली com.aspose.psd.RectangleF लौटाया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | इंटरसेक्ट करने के लिए पहला rectangle। |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | इंटरसेक्ट करने के लिए दूसरा rectangle। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


निर्धारित करता है कि यह आयत rect के साथ प्रतिच्छेद करती है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | परीक्षण करने के लिए rectangle। |

**Returns:**
boolean - यदि कोई भी इंटरसेक्शन हो तो यह मेथड true लौटाता है।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


यह प्राप्त करता है कि इस com.aspose.psd.RectangleF की com.aspose.psd.RectangleF.Width या com.aspose.psd.RectangleF.Height गुण का मान शून्य है या नहीं।

**Returns:**
boolean - यह प्रॉपर्टी true लौटाती है यदि इस com.aspose.psd.RectangleF की com.aspose.psd.RectangleF.Width या com.aspose.psd.RectangleF.Height प्रॉपर्टी का मान शून्य हो; अन्यथा false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


वर्तमान आयत मानों को गुणा करके मैट्रिक्स के लंबवत और क्षैतिज स्केल मानों को रूपांतरित करता है और परिणाम मानों के साथ एक नया [RectangleF](../../com.aspose.psd/rectanglef) इंस्टेंस लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| transformMatrix | double[] | लेयर ट्रांसफ़ॉर्म मैट्रिक्स। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


आयत को सामान्यीकृत करता है, इसकी चौड़ाई और ऊँचाई को सकारात्मक बनाकर, बायें को दायें से कम और ऊपर को नीचे से कम करता है।

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | स्थान को ऑफसेट करने की मात्रा। |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


इस आयत का स्थान निर्दिष्ट मात्रा से समायोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | float | क्षैतिज रूप से स्थान को ऑफसेट करने की मात्रा। |
| y | float | ऊर्ध्वाधर रूप से स्थान को ऑफसेट करने की मात्रा। |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


/ ऑपरेटर को लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | आयत। |
| डिवाइडर | float | डिवाइडर। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


परीक्षण करता है कि दो com.aspose.psd.RectangleF संरचनाओं का स्थान और आकार समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | समानता ऑपरेटर के बाएँ स्थित com.aspose.psd.RectangleF संरचना। |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | समानता ऑपरेटर के दाएँ स्थित com.aspose.psd.RectangleF संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि दो निर्दिष्ट com.aspose.psd.RectangleF संरचनाओं की com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width और com.aspose.psd.RectangleF.Height प्रॉपर्टी समान हों।
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


परीक्षण करता है कि दो com.aspose.psd.RectangleF संरचनाओं का स्थान या आकार अलग है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | असमानता ऑपरेटर के बाएँ स्थित com.aspose.psd.RectangleF संरचना। |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | असमानता ऑपरेटर के दाएँ स्थित com.aspose.psd.RectangleF संरचना। |

**Returns:**
boolean - यह ऑपरेटर true लौटाता है यदि दो com.aspose.psd.RectangleF संरचनाओं की com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width या com.aspose.psd.RectangleF.Height प्रॉपर्टी में से कोई भी असमान हो; अन्यथा false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


\* ऑपरेटर को लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | आयत। |
| मल्टिप्लायर | float | मल्टिप्लायर। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


इस  com.aspose.psd.RectangleF  संरचना के  com.aspose.psd.RectangleF.Y  और  com.aspose.psd.RectangleF.Height  के योग के रूप में y-निर्देशांक प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


इस  com.aspose.psd.RectangleF  संरचना की ऊँचाई प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


इस  com.aspose.psd.RectangleF  संरचना के बाएँ किनारे के x-निर्देशांक को प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


इस  com.aspose.psd.RectangleF  संरचना के ऊपरी-बाएँ कोने के निर्देशांक को प्राप्त करता या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


इस com.aspose.psd.RectangleF संरचना के com.aspose.psd.RectangleF.X और com.aspose.psd.RectangleF.Width का योग होने वाला x-निर्देशांक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


इस com.aspose.psd.RectangleF का आकार प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


इस com.aspose.psd.RectangleF संरचना के शीर्ष किनारे का y-निर्देशांक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


इस com.aspose.psd.RectangleF संरचना की चौड़ाई प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का x-निर्देशांक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


इस com.aspose.psd.RectangleF संरचना के ऊपर-बाएँ कोने का y-निर्देशांक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


[RectangleF](../../com.aspose.psd/rectanglef) को [Rectangle](../../com.aspose.psd/rectangle) संरचना में कटे हुए आयत मानों के साथ परिवर्तित करता है।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


इस com.aspose.psd.RectangleF के गुणों को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस com.aspose.psd.RectangleF संरचना की स्थिति, चौड़ाई और ऊँचाई को समाहित करती है।
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


निर्दिष्ट com.aspose.psd.Rectangle संरचना को एक com.aspose.psd.RectangleF संरचना में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | परिवर्तित करने के लिए com.aspose.psd.Rectangle संरचना। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


दो आयतों के संघ को समाहित करने वाली सबसे छोटी संभव तृतीय आयत बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | संघ करने के लिए पहला आयत। |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | संघ करने के लिए दूसरा आयत। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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


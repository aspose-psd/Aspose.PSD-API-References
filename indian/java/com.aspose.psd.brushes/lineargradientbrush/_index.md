---
title: "LinearGradientBrush"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Aspose.Imaging.Brush को एक रैखिक ग्रेडिएंट के साथ संलग्न करता है।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Aspose.Imaging.Brush को एक रैखिक ग्रेडिएंट के साथ संलग्न करता है। इस क्लास को विरासत में नहीं लिया जा सकता।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | LinearGradientBrush क्लास का एक नया इंस्टेंस डिफ़ॉल्ट पैरामीटरों के साथ इनिशियलाइज़ करता है। |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | LinearGradientBrush क्लास का एक नया इंस्टेंस निर्दिष्ट बिंदुओं और रंगों के साथ इनिशियलाइज़ करता है। |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | LinearGradientBrush क्लास का एक नया इंस्टेंस निर्दिष्ट बिंदुओं और रंगों के साथ इनिशियलाइज़ करता है। |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | वर्तमान Brush की एक नई गहरी क्लोन बनाता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | ग्रेडिएंट कोण प्राप्त करता है। |
| [getBlend()](#getBlend--) | Aspose.Imaging.Blend प्राप्त करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और फैक्टर्स को निर्दिष्ट करता है। |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getEndColor()](#getEndColor--) | अंतिम ग्रेडिएंट रंग प्राप्त करता है। |
| [getGammaCorrection()](#getGammaCorrection--) | यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं। |
| [getInterpolationColors()](#getInterpolationColors--) | एक com.aspose.psd.ColorBlend प्राप्त करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [getLinearColors()](#getLinearColors--) | ग्रेडिएंट के प्रारंभिक और अंतिम रंग प्राप्त करता है। |
| [getOpacity()](#getOpacity--) | ब्रश की अपारदर्शिता प्राप्त करता है। |
| [getRectangle()](#getRectangle--) | एक आयताकार क्षेत्र प्राप्त करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है। |
| [getStartColor()](#getStartColor--) | प्रारंभिक ग्रेडिएंट रंग प्राप्त करता है। |
| [getTransform()](#getTransform--) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [getWrapMode()](#getWrapMode--) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं। |
| [isTransformChanged()](#isTransformChanged--) | यह दर्शाने वाला मान प्राप्त करता है कि रूपांतरण किसी न किसी तरह बदले गए थे या नहीं। |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | निर्दिष्ट Aspose.Imaging.Matrix को पहले जोड़कर, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है। |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | निर्दिष्ट क्रम में, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | TransformBrush.Transform गुण को पहचान (identity) पर रीसेट करता है। |
| [rotateTransform(float angle)](#rotateTransform-float-) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है। |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है। |
| [setAngle(float value)](#setAngle-float-) | ग्रेडिएंट कोण सेट करता है। |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं। |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Aspose.Imaging.Blend सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और फैक्टर्स को निर्दिष्ट करता है। |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | एक रैखिक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और दोनों सिरों पर एकल रंग की ओर रैखिक फॉलऑफ़ होता है। |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | एक रैखिक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और दोनों सिरों पर एकल रंग की ओर रैखिक फॉलऑफ़ होता है। |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | अंतिम ग्रेडिएंट रंग सेट करता है। |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं। |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | एक com.aspose.psd.ColorBlend सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | ग्रेडिएंट के प्रारंभिक और अंतिम रंग सेट करता है। |
| [setOpacity(float value)](#setOpacity-float-) | ब्रश की अपारदर्शिता सेट करता है। |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | एक आयताकार क्षेत्र सेट करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है। |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है। |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है। |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | प्रारंभिक ग्रेडिएंट रंग सेट करता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [setWrapMode(int value)](#setWrapMode-int-) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


डिफ़ॉल्ट पैरामीटरों के साथ  LinearGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। प्रारंभिक रंग काला है, अंतिम रंग सफ़ेद है, कोण 45 डिग्री है और आयत (0,0) में स्थित है जिसका आकार (1,1) है।

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


LinearGradientBrush क्लास का एक नया इंस्टेंस निर्दिष्ट बिंदुओं और रंगों के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | एक  Aspose.Imaging.Point  संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक बिंदु को दर्शाती है। |
| point2 | [Point](../../com.aspose.psd/point) | एक  Aspose.Imaging.Point  संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |
| color1 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो रैखिक ग्रेडिएंट के अंतिम रंग को दर्शाती है। |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


LinearGradientBrush क्लास का एक नया इंस्टेंस निर्दिष्ट बिंदुओं और रंगों के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | एक  Aspose.Imaging.PointF  संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक बिंदु को दर्शाती है। |
| point2 | [PointF](../../com.aspose.psd/pointf) | एक  Aspose.Imaging.PointF  संरचना जो रैखिक ग्रेडिएंट के अंत बिंदु को दर्शाती है। |
| color1 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो रैखिक ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो रैखिक ग्रेडिएंट के अंतिम रंग को दर्शाती है। |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | एक  Aspose.Imaging.RectangleF  संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के अंतिम रंग को दर्शाती है। |
| angle | float | कोण, डिग्री में x-अक्ष से घड़ी की दिशा में मापा गया, ग्रेडिएंट की अभिविन्यास रेखा का। |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  Aspose.Imaging.RectangleF  संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के अंतिम रंग को दर्शाती है। |
| angle | float | कोण, डिग्री में x-अक्ष से घड़ी की दिशा में मापा गया, ग्रेडिएंट की अभिविन्यास रेखा का। |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | एक  Aspose.Imaging.RectangleF  संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के अंतिम रंग को दर्शाती है। |
| angle | float | कोण, डिग्री में x-अक्ष से घड़ी की दिशा में मापा गया, ग्रेडिएंट की अभिविन्यास रेखा का। |
| isAngleScalable | boolean | यदि इसे  true  पर सेट किया जाता है तो इस  LinearGradientBrush  के साथ रूपांतरण के दौरान कोण बदल जाता है। |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


LinearGradientBrush क्लास का एक नया इंस्टेंस आयत, प्रारंभिक और अंतिम रंग, और अभिविन्यास कोण के आधार पर इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | एक  Aspose.Imaging.RectangleF  संरचना जो रैखिक ग्रेडिएंट की सीमाओं को निर्दिष्ट करती है। |
| color1 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के प्रारंभिक रंग को दर्शाती है। |
| color2 | [Color](../../com.aspose.psd/color) | एक  com.aspose.psd.Color  संरचना जो ग्रेडिएंट के अंतिम रंग को दर्शाती है। |
| angle | float | कोण, डिग्री में x-अक्ष से घड़ी की दिशा में मापा गया, ग्रेडिएंट की अभिविन्यास रेखा का। |
| isAngleScalable | boolean | यदि इसे  true  पर सेट किया जाता है तो इस  LinearGradientBrush  के साथ रूपांतरण के दौरान कोण बदल जाता है। |

### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


वर्तमान Brush की एक नई गहरी क्लोन बनाता है।

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

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
### getAngle() {#getAngle--}
```
public float getAngle()
```


ग्रेडिएंट कोण प्राप्त करता है।

**Returns:**
float - ग्रेडिएंट का कोण।
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Aspose.Imaging.Blend प्राप्त करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और फैक्टर्स को निर्दिष्ट करता है।

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


अंतिम ग्रेडिएंट रंग प्राप्त करता है।

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं।

**Returns:**
boolean - मान true है यदि इस  LinearGradientBrushBase  के लिए गामा सुधार सक्षम है; अन्यथा false।
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


एक com.aspose.psd.ColorBlend प्राप्त करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है।

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


ग्रेडिएंट के प्रारंभिक और अंतिम रंग प्राप्त करता है।

**Returns:**
com.aspose.psd.Color[] - दो  Color  संरचनाओं की एक एरे जो ग्रेडिएंट के प्रारंभिक और अंतिम रंगों को दर्शाती है।
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


ब्रश की अपारदर्शिता प्राप्त करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Returns:**
float - ब्रश की अपारदर्शिता मान।
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


एक आयताकार क्षेत्र प्राप्त करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


प्रारंभिक ग्रेडिएंट रंग प्राप्त करता है।

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है।

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है।

**Returns:**
int - एक  Aspose.Imaging.WrapMode  जो निर्दिष्ट करता है कि इस  TransformBrush  से बने भराव कैसे टाइल किए जाते हैं।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


यह दर्शाने वाला मान प्राप्त करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं।

**Returns:**
boolean -  true  यदि  LinearGradientBrushBase.Angle  इस  LinearGradientBrushBase  के साथ रूपांतरणों के दौरान बदलता है; अन्यथा,  false ।
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


एक मान प्राप्त करता है जो दर्शाता है कि रूपांतरण किसी न किसी तरह बदले गए थे या नहीं। उदाहरण के लिए रूपांतरण मैट्रिक्स सेट करना या रूपांतरण मैट्रिक्स को बदलने वाली किसी भी विधि को कॉल करना। यह प्रॉपर्टी GDI+ के साथ पिछली संगतता के लिए पेश की गई है।

मान:  True  यदि रूपांतरण बदला गया; अन्यथा,  false ।

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


निर्दिष्ट Aspose.Imaging.Matrix को पहले जोड़कर, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ज्यामितीय रूपांतरण को गुणा करने के लिए  Aspose.Imaging.Matrix । |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


निर्दिष्ट क्रम में, इस LinearGradientBrush के स्थानीय ज्यामितीय रूपांतरण को दर्शाने वाले Aspose.Imaging.Matrix को निर्दिष्ट Aspose.Imaging.Matrix से गुणा करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | ज्यामितीय रूपांतरण को गुणा करने के लिए  Aspose.Imaging.Matrix । |
| order | int | एक  Aspose.Imaging.MatrixOrder  जो निर्दिष्ट करता है कि दो मैट्रिक्स को किस क्रम में गुणा किया जाए। |

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


TransformBrush.Transform गुण को पहचान (identity) पर रीसेट करता है।

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को घुमाता है। यह विधि घुमाव को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्रा से घुमाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| angle | float | घुमाव का कोण। |
| order | int | एक  Aspose.Imaging.MatrixOrder  जो निर्दिष्ट करता है कि घुमाव मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


निर्दिष्ट मात्रा द्वारा स्थानीय ज्यामितीय रूपांतरण को स्केल करता है। यह विधि स्केलिंग मैट्रिक्स को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


निर्दिष्ट क्रम में, स्थानीय ज्यामितीय रूपांतरण को निर्दिष्ट मात्राओं से स्केल करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sx | float | x-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| sy | float | y-अक्ष दिशा में रूपांतरण को स्केल करने की मात्रा। |
| order | int | एक  Aspose.Imaging.MatrixOrder  जो निर्धारित करता है कि स्केलिंग मैट्रिक्स को जोड़ना है या पहले जोड़ना है। |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


ग्रेडिएंट कोण सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | ग्रेडिएंट कोण। |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के साथ रूपांतरणों के दौरान LinearGradientBrushBase.Angle बदला गया है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | सही यदि  LinearGradientBrushBase.Angle  इस  LinearGradientBrushBase  के साथ रूपांतरण के दौरान बदलता है; अन्यथा, गलत। |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Aspose.Imaging.Blend सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और फैक्टर्स को निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | एक  Aspose.Imaging.Blend  जो ग्रेडिएंट के लिए कस्टम फ़ॉलऑफ़ को दर्शाता है। |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


एक रैखिक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और दोनों सिरों पर एकल रंग की ओर रैखिक फॉलऑफ़ होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का एक मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंतिम रंग से बना होता है)। |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


एक रैखिक ग्रेडिएंट बनाता है जिसमें केंद्र रंग और दोनों सिरों पर एकल रंग की ओर रैखिक फॉलऑफ़ होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का एक मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंतिम रंग से बना होता है)। |
| स्केल | float | 0 से 1 के बीच का एक मान जो यह निर्धारित करता है कि रंग प्रारंभिक रंग से  फ़ोकस  (अंतिम रंग) तक कितनी तेज़ी से फ़ॉलऑफ़ होते हैं। |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


अंतिम ग्रेडिएंट रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | अंतिम ग्रेडिएंट रंग। |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


यह दर्शाने वाला मान सेट करता है कि इस LinearGradientBrushBase के लिए गामा सुधार सक्षम है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | यह मान सही है यदि इस  LinearGradientBrushBase  के लिए गामा सुधार सक्षम है; अन्यथा, गलत। |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


एक com.aspose.psd.ColorBlend सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | एक  com.aspose.psd.ColorBlend  जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


ग्रेडिएंट के प्रारंभिक और अंतिम रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | दो  Color  संरचनाओं की एक एरे जो ग्रेडिएंट के प्रारंभिक और अंतिम रंगों को दर्शाती है। |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


ब्रश की अपारदर्शिता सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | ब्रश अपारदर्शिता मान। |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


एक आयताकार क्षेत्र सेट करता है जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को परिभाषित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | एक  com.aspose.psd.RectangleF  संरचना जो ग्रेडिएंट के प्रारंभ और समाप्ति बिंदुओं को निर्दिष्ट करती है। |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का एक मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ प्रारंभिक रंग और अंतिम रंग समान रूप से मिश्रित होते हैं)। |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


घंटी-आकार की वक्र पर आधारित ग्रेडिएंट फॉलऑफ़ बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का एक मान जो ग्रेडिएंट के केंद्र को निर्दिष्ट करता है (वह बिंदु जहाँ ग्रेडिएंट केवल अंतिम रंग से बना होता है)। |
| स्केल | float | 0 से 1 के बीच का एक मान जो यह निर्दिष्ट करता है कि रंग  फ़ोकस  से कितनी तेज़ी से फ़ॉलऑफ़ होते हैं। |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


प्रारंभिक ग्रेडिएंट रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | प्रारंभिक ग्रेडिएंट रंग। |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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


निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। यह विधि अनुवाद को रूपांतरण के पहले जोड़ती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dx | float | x में अनुवाद का मान। |
| dy | float | y में अनुवाद का मान। |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है।

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


---
title: "PathGradientBrush"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक ग्रेडिएंट के साथ Aspose.Imaging.Brush ऑब्जेक्ट को संलग्न करता है।"
type: docs
weight: 14
url: /hi/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

एक ग्रेडिएंट के साथ Aspose.Imaging.Brush ऑब्जेक्ट को संलग्न करता है। इस क्लास को विरासत में नहीं लिया जा सकता।

डिफ़ॉल्ट रूप से केंद्र रंग सफ़ेद है। उपयोगकर्ता बाद में कभी भी इस मान को बदल सकता है।

सुराउंड रंगों की एरे डिफ़ॉल्ट रूप से सफ़ेद रंग वाले एकल तत्व से इनिशियलाइज़ की जाती है। बाद में सुराउंड रंगों को बदला जा सकता है, लेकिन सुराउंड रंग सेट करते समय कम से कम एक तत्व आवश्यक है।

इसके इनिशियलाइज़ेशन के बारे में अधिक विवरण के लिए  Blend  देखें।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | निर्दिष्ट बिंदुओं के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | निर्दिष्ट बिंदुओं और रैप मोड के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | निर्दिष्ट बिंदुओं के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | निर्दिष्ट बिंदुओं और रैप मोड के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | निर्दिष्ट पथ के साथ PathGradientBrush वर्ग का एक नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | वर्तमान Brush की एक नई गहरी क्लोन बनाता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Aspose.Imaging.Blend प्राप्त करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और फैक्टर्स को निर्दिष्ट करता है। |
| [getCenterColor()](#getCenterColor--) | पथ ग्रेडिएंट के केंद्र पर रंग प्राप्त करता है। |
| [getCenterPoint()](#getCenterPoint--) | पाथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getFocusScales()](#getFocusScales--) | ग्रेडिएंट फॉलऑफ़ के लिए फोकस बिंदु प्राप्त करता है। |
| [getGraphicsPath()](#getGraphicsPath--) | इस ब्रश पर निर्मित ग्राफ़िक्स पथ प्राप्त करता है। |
| [getInterpolationColors()](#getInterpolationColors--) | एक com.aspose.psd.ColorBlend प्राप्त करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [getOpacity()](#getOpacity--) | ब्रश की अपारदर्शिता प्राप्त करता है। |
| [getPathPoints()](#getPathPoints--) | इस ब्रश पर निर्मित पथ बिंदु प्राप्त करता है। |
| [getSurroundColors()](#getSurroundColors--) | उस पथ में बिंदुओं के अनुरूप रंगों की एक सरणी प्राप्त करता है जिसे यह PathGradientBrush भरता है। |
| [getTransform()](#getTransform--) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [getWrapMode()](#getWrapMode--) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Aspose.Imaging.Blend सेट करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और फैक्टर्स को निर्दिष्ट करता है। |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | एक केंद्र रंग और एक आसपास के रंग तक रैखिक गिरावट के साथ ग्रेडिएंट बनाता है। |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | एक केंद्र रंग और प्रत्येक आसपास के रंग तक रैखिक गिरावट के साथ ग्रेडिएंट बनाता है। |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | पथ ग्रेडिएंट के केंद्र पर रंग सेट करता है। |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | पाथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है। |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | ग्रेडिएंट फ़ॉलऑफ़ के लिए फोकस बिंदु प्राप्त करता है या सेट करता है। |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | एक com.aspose.psd.ColorBlend सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |
| [setOpacity(float value)](#setOpacity-float-) | ब्रश की अपारदर्शिता सेट करता है। |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | उस पथ में बिंदुओं के अनुरूप रंगों की एक सरणी सेट करता है जिसे यह PathGradientBrush भरता है। |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | इस TransformBrush के लिए स्थानीय ज्यामितीय रूपांतरण को परिभाषित करने वाले Aspose.Imaging.Matrix की एक प्रति प्राप्त करता है या सेट करता है। |
| [setWrapMode(int value)](#setWrapMode-int-) | इस TransformBrush के लिए रैप मोड को दर्शाने वाले Aspose.Imaging.WrapMode enumeration को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | निर्दिष्ट क्रम में निर्दिष्ट आयामों द्वारा स्थानीय ज्यामितीय रूपांतरण को अनुवादित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


निर्दिष्ट बिंदुओं के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Aspose.Imaging.PointF संरचनाओं की एक सरणी जो पथ के शीर्ष बिंदुओं को बनाते हैं। |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


निर्दिष्ट बिंदुओं और रैप मोड के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Aspose.Imaging.PointF संरचनाओं की एक सरणी जो पथ के शीर्ष बिंदुओं को बनाते हैं। |
| wrapMode | int | एक Aspose.Imaging.WrapMode जो निर्दिष्ट करता है कि इस PathGradientBrush के साथ खींचे गए भराव कैसे टाइल किए जाते हैं। |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


निर्दिष्ट बिंदुओं के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Aspose.Imaging.Point संरचनाओं की एक सरणी जो पथ के शीर्ष बिंदुओं को बनाते हैं। |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


निर्दिष्ट बिंदुओं और रैप मोड के साथ  PathGradientBrush  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Aspose.Imaging.Point संरचनाओं की एक सरणी जो पथ के शीर्ष बिंदुओं को बनाते हैं। |
| wrapMode | int | एक Aspose.Imaging.WrapMode जो निर्दिष्ट करता है कि इस PathGradientBrush के साथ खींचे गए भराव कैसे टाइल किए जाते हैं। |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


निर्दिष्ट पथ के साथ PathGradientBrush वर्ग का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | GraphicsPath जो इस PathGradientBrush द्वारा भरे गए क्षेत्र को परिभाषित करता है। |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Aspose.Imaging.Blend प्राप्त करता है जो ग्रेडिएंट के लिए कस्टम फॉलऑफ़ को परिभाषित करने वाले स्थितियों और फैक्टर्स को निर्दिष्ट करता है।

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


पथ ग्रेडिएंट के केंद्र पर रंग प्राप्त करता है।

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


पाथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


ग्रेडिएंट फॉलऑफ़ के लिए फोकस बिंदु प्राप्त करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


इस ब्रश पर निर्मित ग्राफ़िक्स पथ प्राप्त करता है।

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


एक com.aspose.psd.ColorBlend प्राप्त करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है।

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


ब्रश की अपारदर्शिता प्राप्त करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Returns:**
float - ब्रश की अपारदर्शिता मान।
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


इस ब्रश पर निर्मित पथ बिंदु प्राप्त करता है।

**Returns:**
com.aspose.psd.PointF[] - पथ बिंदु।
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


उस पथ में बिंदुओं के अनुरूप रंगों की एक सरणी प्राप्त करता है जिसे यह PathGradientBrush भरता है।

**Returns:**
com.aspose.psd.Color[] - एक सरणी जिसमें com.aspose.psd.Color संरचनाएँ होती हैं जो इस PathGradientBrush द्वारा भरे गए पथ के प्रत्येक बिंदु से जुड़े रंगों का प्रतिनिधित्व करती हैं।
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


एक केंद्र रंग और एक आसपास के रंग तक रैखिक गिरावट के साथ ग्रेडिएंट बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो निर्दिष्ट करता है कि पथ के केंद्र से पथ की सीमा तक किसी भी रेडियल पर केंद्र रंग सबसे अधिक तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) पथ के केंद्र पर सबसे अधिक तीव्रता रखता है। |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


एक केंद्र रंग और प्रत्येक आसपास के रंग तक रैखिक गिरावट के साथ ग्रेडिएंट बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो निर्दिष्ट करता है कि पथ के केंद्र से पथ की सीमा तक किसी भी रेडियल पर केंद्र रंग सबसे अधिक तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) पथ के केंद्र पर सबसे अधिक तीव्रता रखता है। |
| स्केल | float | 0 से 1 के बीच का मान जो सीमा रंग के साथ मिश्रित होने वाले केंद्र रंग की अधिकतम तीव्रता को निर्दिष्ट करता है। 1 का मान केंद्र रंग की सबसे अधिक संभावित तीव्रता देता है, और यह डिफ़ॉल्ट मान है। |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


पथ ग्रेडिएंट के केंद्र पर रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | एक com.aspose.psd.Color जो पथ ग्रेडिएंट के केंद्र पर रंग का प्रतिनिधित्व करता है। |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


पाथ ग्रेडिएंट के केंद्र बिंदु को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | एक Aspose.Imaging.PointF जो पथ ग्रेडिएंट के केंद्र बिंदु को दर्शाता है। |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


ग्रेडिएंट फ़ॉलऑफ़ के लिए फोकस बिंदु प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | एक Aspose.Imaging.PointF जो ग्रेडिएंट फ़ॉलऑफ़ के फोकस बिंदु को दर्शाता है। |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


एक com.aspose.psd.ColorBlend सेट करता है जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | एक  com.aspose.psd.ColorBlend  जो बहु-रंगीय रैखिक ग्रेडिएंट को परिभाषित करता है। |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


ब्रश की अपारदर्शिता सेट करता है। मान 0 और 1 के बीच होना चाहिए। 0 का मान मतलब ब्रश पूरी तरह दृश्यमान है, 1 का मान मतलब ब्रश पूरी तरह अपारदर्शी है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | ब्रश अपारदर्शिता मान। |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। एक रंग से दूसरे रंग में परिवर्तन बेल-आकार की वक्र पर आधारित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो निर्दिष्ट करता है कि पथ के केंद्र से पथ की सीमा तक किसी भी रेडियल पर केंद्र रंग सबसे अधिक तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) पथ के केंद्र पर सबसे अधिक तीव्रता रखता है। |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


एक ग्रेडिएंट ब्रश बनाता है जो पथ के केंद्र से शुरू होकर पथ की सीमा तक रंग बदलता है। एक रंग से दूसरे रंग में परिवर्तन बेल-आकार की वक्र पर आधारित होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ोकस | float | 0 से 1 के बीच का मान जो निर्दिष्ट करता है कि पथ के केंद्र से पथ की सीमा तक किसी भी रेडियल पर केंद्र रंग सबसे अधिक तीव्रता पर कब होगा। 1 का मान (डिफ़ॉल्ट) पथ के केंद्र पर सबसे अधिक तीव्रता रखता है। |
| स्केल | float | 0 से 1 के बीच का मान जो सीमा रंग के साथ मिश्रित होने वाले केंद्र रंग की अधिकतम तीव्रता को निर्दिष्ट करता है। 1 का मान केंद्र रंग की सबसे अधिक संभावित तीव्रता देता है, और यह डिफ़ॉल्ट मान है। |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


उस पथ में बिंदुओं के अनुरूप रंगों की एक सरणी सेट करता है जिसे यह PathGradientBrush भरता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | com.aspose.psd.Color संरचनाओं की एक सरणी जो इस PathGradientBrush द्वारा भरे गए पथ के प्रत्येक बिंदु से जुड़े रंगों का प्रतिनिधित्व करती है। |

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


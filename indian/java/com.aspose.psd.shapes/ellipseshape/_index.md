---
title: "EllipseShape"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक दीर्घवृत्त आकार का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.shapes/ellipseshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

एक दीर्घवृत्त आकार का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | EllipseShape वर्ग की नई इंस्टेंस को प्रारंभ करता है। |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.psd.RectangleF-) | EllipseShape वर्ग की नई इंस्टेंस को प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getCenter()](#getCenter--) | आकार का केंद्र प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | बाएँ नीचे आयत बिंदु को प्राप्त करता है। |
| [getLeftTop()](#getLeftTop--) | बाएँ ऊपर आयत बिंदु को प्राप्त करता है। |
| [getRectangleHeight()](#getRectangleHeight--) | आयत की ऊँचाई को प्राप्त करता है। |
| [getRectangleWidth()](#getRectangleWidth--) | आयत की चौड़ाई को प्राप्त करता है। |
| [getRightBottom()](#getRightBottom--) | दाएँ नीचे आयत बिंदु को प्राप्त करता है। |
| [getRightTop()](#getRightTop--) | दाएँ ऊपर आयत बिंदु को प्राप्त करता है। |
| [getSegments()](#getSegments--) | आकार के खंड प्राप्त करता है। |
| [hasSegments()](#hasSegments--) | एक मान प्राप्त करता है जो दर्शाता है कि आकार में खंड हैं या नहीं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


EllipseShape वर्ग की नई इंस्टेंस को प्रारंभ करता है।

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.psd.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


EllipseShape वर्ग की नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | आयत। |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

मान: वस्तु की सीमाएँ।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | सीमाएँ गणना होने से पहले लागू करने के लिए मैट्रिक्स। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | सीमाएँ गणना होने से पहले लागू करने के लिए मैट्रिक्स। |
| pen | [Pen](../../com.aspose.psd/pen) | ऑब्जेक्ट के लिए उपयोग करने वाला पेन। यह ऑब्जेक्ट की सीमाओं के आकार को प्रभावित कर सकता है। |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


आकार का केंद्र प्राप्त करता है।

मान: आकार का केंद्र।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


बाएँ नीचे आयत बिंदु को प्राप्त करता है।

मान: बाएँ नीचे आयत बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


बाएँ ऊपर आयत बिंदु को प्राप्त करता है।

मान: बाएँ ऊपर आयत बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


आयत की ऊँचाई को प्राप्त करता है।

मान: आयत की ऊँचाई।

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


आयत की चौड़ाई को प्राप्त करता है।

मान: आयत की चौड़ाई।

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


दाएँ नीचे आयत बिंदु को प्राप्त करता है।

मान: आयत के दाएँ नीचे बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


दाएँ ऊपर आयत बिंदु को प्राप्त करता है।

मान: आयत के दाएँ ऊपर बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


आकार के खंड प्राप्त करता है।

मान: आकार खंड।

**Returns:**
com.aspose.psd.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


एक मान प्राप्त करता है जो दर्शाता है कि आकार में खंड हैं या नहीं।

मान: यदि आकार में खंड हैं तो सत्य; अन्यथा, असत्य।

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


निर्दिष्ट परिवर्तन को आकार पर लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | लागू करने के लिए परिवर्तन। |

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


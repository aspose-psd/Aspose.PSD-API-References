---
title: "CurveShape"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक वक्र स्प्लाइन आकार का प्रतिनिधित्व करता है।"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

एक वक्र स्प्लाइन आकार का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [CurveShape()](#CurveShape--) | CurveShape वर्ग का नया उदाहरण आरंभ करता है। |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | CurveShape वर्ग का नया उदाहरण आरंभ करता है। |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | CurveShape वर्ग का नया उदाहरण आरंभ करता है। |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | CurveShape वर्ग का नया उदाहरण आरंभ करता है। |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | CurveShape वर्ग का नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [getCenter()](#getCenter--) | आकार का केंद्र प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | समाप्ति आकार बिंदु प्राप्त करता है। |
| [getPoints()](#getPoints--) | वक्र बिंदुओं को प्राप्त करता है या सेट करता है। |
| [getSegments()](#getSegments--) | आकार के खंड प्राप्त करता है। |
| [getStartPoint()](#getStartPoint--) | प्रारंभिक आकार बिंदु प्राप्त करता है। |
| [getTension()](#getTension--) | वक्र तनाव को प्राप्त करता है या सेट करता है। |
| [hasSegments()](#hasSegments--) | एक मान प्राप्त करता है जो दर्शाता है कि आकार में खंड हैं या नहीं। |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि आकार बंद है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | इस आकार के बिंदुओं का क्रम उलटता है। |
| [setClosed(boolean value)](#setClosed-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि आकार बंद है या नहीं। |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | वक्र बिंदुओं को प्राप्त करता है या सेट करता है। |
| [setTension(float value)](#setTension-float-) | वक्र तनाव को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


CurveShape वर्ग का नया उदाहरण आरंभ करता है।

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


CurveShape वर्ग का नया उदाहरण आरंभ करता है। डिफ़ॉल्ट तनाव 0.5 उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | बिंदुओं की सरणी। |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


CurveShape वर्ग का नया उदाहरण आरंभ करता है। डिफ़ॉल्ट तनाव 0.5 उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | बिंदुओं की सरणी। |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


CurveShape वर्ग का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | बिंदुओं की सरणी। |
| तनाव | float | वक्र तनाव। |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


CurveShape वर्ग का नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | बिंदुओं की सरणी। |
| तनाव | float | वक्र तनाव। |
| isClosed | boolean | यदि सत्य पर सेट किया जाए तो वक्र बंद हो जाता है। |

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
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


समाप्ति आकार बिंदु प्राप्त करता है।

मान: समाप्ति आकार बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


वक्र बिंदुओं को प्राप्त करता है या सेट करता है।

मान: वक्र बिंदु।

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


आकार के खंड प्राप्त करता है।

मान: आकार खंड।

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


प्रारंभिक आकार बिंदु प्राप्त करता है।

मान: प्रारंभिक आकार बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getTension() {#getTension--}
```
public float getTension()
```


वक्र तनाव को प्राप्त करता है या सेट करता है।

मान: वक्र तनाव।

**Returns:**
float
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
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि आकार बंद है या नहीं।

मान: यदि आकार बंद है तो सत्य; अन्यथा, असत्य।

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reverse() {#reverse--}
```
public void reverse()
```


इस आकार के बिंदुओं का क्रम उलटता है।

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि आकार बंद है या नहीं।

मान: यदि आकार बंद है तो सत्य; अन्यथा, असत्य।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


वक्र बिंदुओं को प्राप्त करता है या सेट करता है।

मान: वक्र बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


वक्र तनाव को प्राप्त करता है या सेट करता है।

मान: वक्र तनाव।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

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


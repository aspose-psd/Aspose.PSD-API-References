---
title: "BezierSegment"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "बीज़ियर सेगमेंट जो एक बिंदु से अगले बिंदु तक जाता है और दो नियंत्रण बिंदुओं का उपयोग करता है।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

बीज़ियर सेगमेंट जो एक बिंदु से अगले बिंदु तक जाता है और दो नियंत्रण बिंदुओं का उपयोग करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | BezierSegment क्लास का एक नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | समाप्ति बिंदु प्राप्त करता है। |
| [getFirstControlPoint()](#getFirstControlPoint--) | बेज़ियर स्प्लाइन का पहला नियंत्रण बिंदु प्राप्त करता है। |
| [getSecondControlPoint()](#getSecondControlPoint--) | बेज़ियर स्प्लाइन का दूसरा नियंत्रण बिंदु प्राप्त करता है। |
| [getStartPoint()](#getStartPoint--) | प्रारंभ बिंदु प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


BezierSegment क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | प्रारंभ बिंदु। |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | पहला नियंत्रण बिंदु। |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | दूसरा नियंत्रण बिंदु। |
| endPoint | [PointF](../../com.aspose.psd/pointf) | समाप्त बिंदु। |

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


समाप्ति बिंदु प्राप्त करता है।

मान: समाप्त बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


बेज़ियर स्प्लाइन का पहला नियंत्रण बिंदु प्राप्त करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


बेज़ियर स्प्लाइन का दूसरा नियंत्रण बिंदु प्राप्त करता है।

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


प्रारंभ बिंदु प्राप्त करता है।

मान: प्रारंभ बिंदु।

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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


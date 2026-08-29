---
title: "BezierSegment"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مقطع بيزيير ينتقل من نقطة إلى النقطة التالية باستخدام نقطتي تحكم."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.shapesegments/beziersegment/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ShapeSegment](../../com.aspose.psd/shapesegment), [com.aspose.psd.shapesegments.LineSegment](../../com.aspose.psd.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

مقطع بيزيير ينتقل من نقطة إلى النقطة التالية باستخدام نقطتي تحكم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.PointF-) | يقوم بإنشاء نسخة جديدة من الفئة  BezierSegment  . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | يحصل على نقطة النهاية. |
| [getFirstControlPoint()](#getFirstControlPoint--) | يحصل على نقطة التحكم الأولى لمنحنى بيزير. |
| [getSecondControlPoint()](#getSecondControlPoint--) | يحصل على نقطة التحكم الثانية لمنحنى بيزير. |
| [getStartPoint()](#getStartPoint--) | يحصل على نقطة البداية. |
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


يقوم بإنشاء نسخة جديدة من الفئة  BezierSegment  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.psd/pointf) | نقطة البداية. |
| firstControlPoint | [PointF](../../com.aspose.psd/pointf) | نقطة التحكم الأولى. |
| secondControlPoint | [PointF](../../com.aspose.psd/pointf) | نقطة التحكم الثانية. |
| endPoint | [PointF](../../com.aspose.psd/pointf) | نقطة النهاية. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على نقطة النهاية.

القيمة: نقطة النهاية.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


يحصل على نقطة التحكم الأولى لمنحنى بيزير.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


يحصل على نقطة التحكم الثانية لمنحنى بيزير.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The second control point.
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


يحصل على نقطة البداية.

القيمة: نقطة البداية.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


---
title: "ArcShape"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل شكل قوس."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

يمثل شكل قوس.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ArcShape()](#ArcShape--) | يُنشئ مثيلاً جديدًا من الفئة ArcShape. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | يُنشئ مثيلاً جديدًا من الفئة ArcShape. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | يُنشئ مثيلاً جديدًا من الفئة ArcShape. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | يحصل على حدود الكائن. |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | يحصل على نقطة النهاية للشكل. |
| [getLeftBottom()](#getLeftBottom--) | يحصل على نقطة المستطيل اليسرى السفلية. |
| [getLeftTop()](#getLeftTop--) | يحصل على نقطة المستطيل اليسرى العليا. |
| [getRectangleHeight()](#getRectangleHeight--) | يحصل على ارتفاع المستطيل. |
| [getRectangleWidth()](#getRectangleWidth--) | يحصل على عرض المستطيل. |
| [getRightBottom()](#getRightBottom--) | يحصل على نقطة المستطيل اليمنى السفلية. |
| [getRightTop()](#getRightTop--) | يحصل على نقطة المستطيل اليمنى العليا. |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [getStartAngle()](#getStartAngle--) | يحصل أو يعيّن زاوية البداية. |
| [getStartPoint()](#getStartPoint--) | يحصل على نقطة البداية للشكل. |
| [getSweepAngle()](#getSweepAngle--) | يحصل أو يعيّن زاوية المسح. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | يعكس ترتيب النقاط لهذا الشكل. |
| [setClosed(boolean value)](#setClosed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. |
| [setStartAngle(float value)](#setStartAngle-float-) | يحصل أو يعيّن زاوية البداية. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | يحصل أو يعيّن زاوية المسح. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


يُنشئ مثيلاً جديدًا من الفئة ArcShape.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


يُنشئ مثيلاً جديدًا من الفئة ArcShape.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل. |
| startAngle | float | زاوية البداية. |
| sweepAngle | float | زاوية المسح. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


يُنشئ مثيلاً جديدًا من الفئة ArcShape.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل. |
| startAngle | float | زاوية البداية. |
| sweepAngle | float | زاوية المسح. |
| isClosed | boolean | إذا تم تعيينه إلى true فإن القوس مغلق. القوس المغلق يتحول فعليًا إلى إهليلج. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


يحصل على حدود الكائن.

القيمة: حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |
| pen | [Pen](../../com.aspose.psd/pen) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


يحصل على مركز الشكل.

القيمة: مركز الشكل.

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


يحصل على نقطة النهاية للشكل.

القيمة: نقطة الشكل النهائية.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


يحصل على نقطة المستطيل اليسرى السفلية.

القيمة: نقطة المستطيل اليسرى السفلية.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


يحصل على نقطة المستطيل اليسرى العليا.

القيمة: نقطة المستطيل اليسرى العليا.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


يحصل على ارتفاع المستطيل.

القيمة: ارتفاع المستطيل.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


يحصل على عرض المستطيل.

القيمة: عرض المستطيل.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


يحصل على نقطة المستطيل اليمنى السفلية.

القيمة: نقطة المستطيل اليمنى السفلية.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


يحصل على نقطة المستطيل اليمنى العليا.

القيمة: نقطة المستطيل اليمنى العليا.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل.

القيمة: مقاطع الشكل.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


يحصل أو يعيّن زاوية البداية.

القيمة: زاوية البداية.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


يحصل على نقطة البداية للشكل.

القيمة: نقطة الشكل الابتدائية.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


يحصل أو يعيّن زاوية المسح.

القيمة: زاوية المسح.

**Returns:**
float
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع.

القيمة:  True  إذا كان الشكل يحتوي على مقاطع؛ وإلا،  false .

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


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة شكل مرتب مغلق لا يكون للنقطة البداية والنهاية أي معنى.

القيمة: True إذا كان هذا الشكل المرتب مغلقًا؛ وإلا false.

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


يعكس ترتيب النقاط لهذا الشكل.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة شكل مرتب مغلق لا يكون للنقطة البداية والنهاية أي معنى.

القيمة: True إذا كان هذا الشكل المرتب مغلقًا؛ وإلا false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


يحصل أو يعيّن زاوية البداية.

القيمة: زاوية البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


يحصل أو يعيّن زاوية المسح.

القيمة: زاوية المسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

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


يطبق التحويل المحدد على الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | التحويل المراد تطبيقه. |

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


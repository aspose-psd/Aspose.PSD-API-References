---
title: "CurveShape"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل شكل منحدر منحني."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

يمثل شكل منحدر منحني.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CurveShape()](#CurveShape--) | يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  . |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  . |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  . |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  . |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  . |
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
| [getPoints()](#getPoints--) | يحصل أو يعيّن نقاط المنحنى. |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [getStartPoint()](#getStartPoint--) | يحصل على نقطة البداية للشكل. |
| [getTension()](#getTension--) | يحصل أو يعيّن توتر المنحنى. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | يعكس ترتيب النقاط لهذا الشكل. |
| [setClosed(boolean value)](#setClosed-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | يحصل أو يعيّن نقاط المنحنى. |
| [setTension(float value)](#setTension-float-) | يحصل أو يعيّن توتر المنحنى. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  .

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  . يتم استخدام التوتر الافتراضي بقيمة 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة النقاط. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  . يتم استخدام التوتر الافتراضي بقيمة 0.5.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة النقاط. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة النقاط. |
| التوتر | float | توتر المنحنى. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


يقوم بتهيئة نسخة جديدة من الفئة  CurveShape  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | مصفوفة النقاط. |
| التوتر | float | توتر المنحنى. |
| isClosed | boolean | إذا تم تعيينه إلى  true  يكون المنحنى مغلقًا. |

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
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


يحصل أو يعيّن نقاط المنحنى.

القيمة: نقاط المنحنى.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل.

القيمة: مقاطع الشكل.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


يحصل على نقطة البداية للشكل.

القيمة: نقطة الشكل الابتدائية.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getTension() {#getTension--}
```
public float getTension()
```


يحصل أو يعيّن توتر المنحنى.

القيمة: توتر المنحنى.

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


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا.

القيمة:  true  إذا كان الشكل مغلقًا؛ وإلا،  false .

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


يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا.

القيمة:  true  إذا كان الشكل مغلقًا؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


يحصل أو يعيّن نقاط المنحنى.

القيمة: نقاط المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


يحصل أو يعيّن توتر المنحنى.

القيمة: توتر المنحنى.

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


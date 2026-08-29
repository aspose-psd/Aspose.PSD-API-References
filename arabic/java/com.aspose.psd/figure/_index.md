---
title: "Figure"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الشكل."
type: docs
weight: 42
url: /ar/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object، [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

الشكل. حاوية للأشكال.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Figure()](#Figure--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | يضيف شكلاً إلى الشكل. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | يضيف مجموعة من الأشكال إلى الشكل. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | يحصل أو يعيّن حدود الكائن. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | يحصل على حدود الكائن. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل الكاملة. |
| [getShapes()](#getShapes--) | يحصل على أشكال الشكل. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | يزيل شكلاً من الشكل. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | يزيل نطاقًا من الأشكال من الشكل. |
| [reverse()](#reverse--) | يعكس ترتيب أشكال هذا الشكل وترتيب نقاط الأشكال. |
| [setClosed(boolean value)](#setClosed-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


يضيف شكلاً إلى الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | الشكل المراد إضافته. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


يضيف مجموعة من الأشكال إلى الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | الأشكال المراد إضافتها. |

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


يحصل أو يعيّن حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل الكاملة.

**Returns:**
com.aspose.psd.ShapeSegment[] - مقاطع الشكل.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


يحصل على أشكال الشكل.

**Returns:**
com.aspose.psd.Shape[] - أشكال الشكل.
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


يحصل على قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. سيحدث الفرق فقط في حالة كون الأشكال الأولى والأخيرة للشكل متصلة بشكل مستمر. في هذه الحالة، سيتم ربط النقطة الأولى للشكل الأول بخط مستقيم من النقطة الأخيرة للشكل الأخير.

**Returns:**
boolean -  صحيح  إذا كان هذا الشكل مغلقًا؛ وإلا،  خطأ .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


يزيل شكلاً من الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | الشكل المراد إزالته. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


يزيل نطاقًا من الأشكال من الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | نطاق الأشكال المراد إزالته. |

### reverse() {#reverse--}
```
public void reverse()
```


يعكس ترتيب أشكال هذا الشكل وترتيب نقاط الأشكال.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. سيحدث الفرق فقط في حالة كون الأشكال الأولى والأخيرة للشكل متصلة بشكل مستمر. في هذه الحالة، سيتم ربط النقطة الأولى للشكل الأول بخط مستقيم من النقطة الأخيرة للشكل الأخير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | صحيح  إذا كان هذا الشكل مغلقًا؛ وإلا،  خطأ . |

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


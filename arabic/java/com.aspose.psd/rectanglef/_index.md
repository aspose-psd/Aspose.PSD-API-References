---
title: "RectangleF"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل."
type: docs
weight: 89
url: /ar/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | ينشئ مثيلاً جديدًا من بنية com.aspose.psd.RectangleF بالموقع والحجم المحددين. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | ينشئ مثيلاً جديدًا من بنية com.aspose.psd.RectangleF بالموقع والحجم المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية com.aspose.psd.RectangleF هذه. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها rect موجودة بالكامل داخل بنية com.aspose.psd.RectangleF هذه. |
| [contains(float x, float y)](#contains-float-float-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية com.aspose.psd.RectangleF هذه. |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | يقسم قيم المستطيل الحالية لتحويل قيم مقياس المصفوفة العمودي والأفقي ويعيد مثيلاً جديدًا من [RectangleF](../../com.aspose.psd/rectanglef) بالقيم الناتجة. |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان obj هو com.aspose.psd.RectangleF بنفس الموقع والحجم لهذا com.aspose.psd.RectangleF. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | ينشئ بنية com.aspose.psd.RectangleF بالزاوية العلوية اليسرى والزاوية السفلية اليمنى في المواقع المحددة. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | ينشئ Rectangle جديدًا من نقطتين محددتين. |
| [getBottom()](#getBottom--) | يحصل أو يعيّن إحداثي y الذي هو مجموع com.aspose.psd.RectangleF.Y و com.aspose.psd.RectangleF.Height لهذا بنية com.aspose.psd.RectangleF. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | يحصل على مثيل جديد من بنية com.aspose.psd.RectangleF التي لديها قيم com.aspose.psd.RectangleF.X و com.aspose.psd.RectangleF.Y و com.aspose.psd.RectangleF.Width و com.aspose.psd.RectangleF.Height مضبوطة على الصفر. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن ارتفاع هذه بنية com.aspose.psd.RectangleF. |
| [getLeft()](#getLeft--) | يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه بنية com.aspose.psd.RectangleF. |
| [getLocation()](#getLocation--) | يحصل أو يعيّن إحداثيات الزاوية العلوية اليسرى لهذه بنية com.aspose.psd.RectangleF. |
| [getRight()](#getRight--) | يحصل أو يعيّن إحداثي x الذي هو مجموع com.aspose.psd.RectangleF.X و com.aspose.psd.RectangleF.Width لهذه بنية com.aspose.psd.RectangleF. |
| [getSize()](#getSize--) | يحصل أو يعيّن حجم هذه بنية com.aspose.psd.RectangleF. |
| [getTop()](#getTop--) | يحصل أو يعيّن إحداثي y للحافة العلوية لهذه بنية com.aspose.psd.RectangleF. |
| [getWidth()](#getWidth--) | يحصل أو يعيّن عرض هذه بنية com.aspose.psd.RectangleF. |
| [getX()](#getX--) | يحصل أو يعيّن إحداثي x للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF. |
| [getY()](#getY--) | يحصل أو يعيّن إحداثي y للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF. |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لهذا  com.aspose.psd.RectangleF  الهيكل. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | ينشئ ويعيد نسخة موسعة من الهيكل المحدد  com.aspose.psd.RectangleF  . |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | يوسع هذا  com.aspose.psd.RectangleF  بالمقدار المحدد. |
| [inflate(float x, float y)](#inflate-float-float-) | يوسع هذا الهيكل  com.aspose.psd.RectangleF  بالمقدار المحدد. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | يستبدل هذا الهيكل  com.aspose.psd.RectangleF  بالتقاطع بينه وبين الهيكل المحدد  com.aspose.psd.RectangleF . |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | يعيد هيكل  com.aspose.psd.RectangleF  يمثل تقاطع مستطيلين. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | يحدد ما إذا كان هذا المستطيل يتقاطع مع  rect . |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كانت الخاصية  com.aspose.psd.RectangleF.Width  أو  com.aspose.psd.RectangleF.Height  لهذا  com.aspose.psd.RectangleF  لها قيمة صفر. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | يضرب قيم المستطيل الحالية لتحويل قيم مقياس المصفوفة العمودية والأفقية ويعيد نسخة جديدة من [RectangleF](../../com.aspose.psd/rectanglef) بالقيم الناتجة. |
| [normalize()](#normalize--) | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أعلى من الأسفل. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(float x, float y)](#offset-float-float-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | ينفّذ العامل /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | يفحص ما إذا كان هيكلان  com.aspose.psd.RectangleF  لهما موقع وحجم متساويين. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | يفحص ما إذا كان هيكلان  com.aspose.psd.RectangleF  يختلفان في الموقع أو الحجم. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | ينفّذ العامل \*. |
| [setBottom(float value)](#setBottom-float-) | يحصل أو يعيّن إحداثي y الذي هو مجموع com.aspose.psd.RectangleF.Y و com.aspose.psd.RectangleF.Height لهذا بنية com.aspose.psd.RectangleF. |
| [setHeight(float value)](#setHeight-float-) | يحصل أو يعيّن ارتفاع هذه بنية com.aspose.psd.RectangleF. |
| [setLeft(float value)](#setLeft-float-) | يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه بنية com.aspose.psd.RectangleF. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | يحصل أو يعيّن إحداثيات الزاوية العلوية اليسرى لهذه بنية com.aspose.psd.RectangleF. |
| [setRight(float value)](#setRight-float-) | يحصل أو يعيّن إحداثي x الذي هو مجموع com.aspose.psd.RectangleF.X و com.aspose.psd.RectangleF.Width لهذه بنية com.aspose.psd.RectangleF. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | يحصل أو يعيّن حجم هذه بنية com.aspose.psd.RectangleF. |
| [setTop(float value)](#setTop-float-) | يحصل أو يعيّن إحداثي y للحافة العلوية لهذه بنية com.aspose.psd.RectangleF. |
| [setWidth(float value)](#setWidth-float-) | يحصل أو يعيّن عرض هذه بنية com.aspose.psd.RectangleF. |
| [setX(float value)](#setX-float-) | يحصل أو يعيّن إحداثي x للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF. |
| [setY(float value)](#setY-float-) | يحصل أو يعيّن إحداثي y للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF. |
| [toRectangle_internalized()](#toRectangle-internalized--) | يحوّل [RectangleF](../../com.aspose.psd/rectanglef) إلى هيكل [Rectangle](../../com.aspose.psd/rectangle) بقيم مستطيل مقصوصة. |
| [toString()](#toString--) | يحوّل سمات هذا  com.aspose.psd.RectangleF  إلى سلسلة قابلة للقراءة للإنسان. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | يحوّل الهيكل المحدد  com.aspose.psd.Rectangle  إلى هيكل  com.aspose.psd.RectangleF . |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء مستطيلين يشكلان اتحادًا. |
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


ينشئ مثيلاً جديدًا من بنية com.aspose.psd.RectangleF بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل. |
| ص | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل. |
| العرض | float | عرض المستطيل. |
| الارتفاع | float | ارتفاع المستطيل. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


ينشئ مثيلاً جديدًا من بنية com.aspose.psd.RectangleF بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | كائن  com.aspose.psd.PointF  يمثل الزاوية العليا اليسرى للمنطقة المستطيلة. |
| size | [SizeF](../../com.aspose.psd/sizef) | كائن  com.aspose.psd.SizeF  يمثل عرض وارتفاع المنطقة المستطيلة. |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية com.aspose.psd.RectangleF هذه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | الـ  com.aspose.psd.PointF  للاختبار. |

**Returns:**
منطقي - تُرجِع هذه الطريقة true إذا كانت النقطة الممثلة بالمعامل  point  موجودة داخل بنية  com.aspose.psd.RectangleF  هذه؛ وإلا false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها rect موجودة بالكامل داخل بنية com.aspose.psd.RectangleF هذه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | الـ  com.aspose.psd.RectangleF  للاختبار. |

**Returns:**
منطقي - تُرجِع هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بالمعامل  rect  موجودة بالكامل داخل المنطقة المستطيلة الممثلة بهذه  com.aspose.psd.RectangleF ؛ وإلا false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل بنية com.aspose.psd.RectangleF هذه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للنقطة للاختبار. |
| ص | float | الإحداثي الصادي للنقطة للاختبار. |

**Returns:**
منطقي - تُرجِع هذه الطريقة true إذا كانت النقطة المعرفة بـ  x  و  y  موجودة داخل بنية  com.aspose.psd.RectangleF  هذه؛ وإلا false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float |  |
| ص | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


يقسم قيم المستطيل الحالية لتحويل قيم مقياس المصفوفة العمودي والأفقي ويعيد مثيلاً جديدًا من [RectangleF](../../com.aspose.psd/rectanglef) بالقيم الناتجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transformMatrix | double[] | مصفوفة تحويل الطبقة. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان obj هو com.aspose.psd.RectangleF بنفس الموقع والحجم لهذا com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ  System.Object  للاختبار. |

**Returns:**
منطقي - تُرجِع هذه الطريقة true إذا كان  obj  من نوع  com.aspose.psd.RectangleF  وكانت خصائصه X و Y و Width و Height مساوية للخصائص المقابلة في هذه  com.aspose.psd.RectangleF ؛ وإلا false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


ينشئ بنية com.aspose.psd.RectangleF بالزاوية العلوية اليسرى والزاوية السفلية اليمنى في المواقع المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | float | الإحداثي السيني للزاوية العليا اليسرى للمنطقة المستطيلة. |
| top | float | الإحداثي الصادي للزاوية العليا اليسرى للمنطقة المستطيلة. |
| right | float | الإحداثي السيني للزاوية السفلى اليمنى للمنطقة المستطيلة. |
| bottom | float | الإحداثي الصادي للزاوية السفلى اليمنى للمنطقة المستطيلة. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


ينشئ  Rectangle  جديدًا من نقطتين محددتين. سيكون رأسا الـ  Rectangle  المُنشأ مساويين للنقطتين  point1  و  point2 . عادةً ما تكون هذه رؤوسًا متقابلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | النقطة الأولى  Point  للمستطيل الجديد. |
| point2 | [PointF](../../com.aspose.psd/pointf) | النقطة الثانية  Point  للمستطيل الجديد. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


يحصل أو يعيّن إحداثي y الذي هو مجموع com.aspose.psd.RectangleF.Y و com.aspose.psd.RectangleF.Height لهذا بنية com.aspose.psd.RectangleF.

**Returns:**
float - الإحداثي الصادي الذي هو مجموع  com.aspose.psd.RectangleF.Y  و  com.aspose.psd.RectangleF.Height  لهذه بنية  com.aspose.psd.RectangleF .
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


يحصل على مثيل جديد من بنية com.aspose.psd.RectangleF التي لديها قيم com.aspose.psd.RectangleF.X و com.aspose.psd.RectangleF.Y و com.aspose.psd.RectangleF.Width و com.aspose.psd.RectangleF.Height مضبوطة على الصفر.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


يحصل أو يعيّن ارتفاع هذه بنية com.aspose.psd.RectangleF.

**Returns:**
float - الارتفاع لهذه بنية  com.aspose.psd.RectangleF .
### getLeft() {#getLeft--}
```
public float getLeft()
```


يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه بنية com.aspose.psd.RectangleF.

**Returns:**
float - الإحداثي السيني للحافة اليسرى لهذه بنية  com.aspose.psd.RectangleF .
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


يحصل أو يعيّن إحداثيات الزاوية العلوية اليسرى لهذه بنية com.aspose.psd.RectangleF.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


يحصل أو يعيّن إحداثي x الذي هو مجموع com.aspose.psd.RectangleF.X و com.aspose.psd.RectangleF.Width لهذه بنية com.aspose.psd.RectangleF.

**Returns:**
float - إحداثي x الذي هو مجموع  com.aspose.psd.RectangleF.X  و  com.aspose.psd.RectangleF.Width  لهذا الهيكل  com.aspose.psd.RectangleF .
### getSize() {#getSize--}
```
public SizeF getSize()
```


يحصل أو يعيّن حجم هذه بنية com.aspose.psd.RectangleF.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


يحصل أو يعيّن إحداثي y للحافة العلوية لهذه بنية com.aspose.psd.RectangleF.

**Returns:**
float - إحداثي y للحافة العلوية لهذا الهيكل  com.aspose.psd.RectangleF .
### getWidth() {#getWidth--}
```
public float getWidth()
```


يحصل أو يعيّن عرض هذه بنية com.aspose.psd.RectangleF.

**Returns:**
float - عرض هذا الهيكل  com.aspose.psd.RectangleF .
### getX() {#getX--}
```
public float getX()
```


يحصل أو يعيّن إحداثي x للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF.

**Returns:**
float - إحداثي x للزاوية العليا اليسرى لهذا الهيكل  com.aspose.psd.RectangleF .
### getY() {#getY--}
```
public float getY()
```


يحصل أو يعيّن إحداثي y للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF.

**Returns:**
float - إحداثي y للزاوية العليا اليسرى لهذا الهيكل  com.aspose.psd.RectangleF .
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على رمز التجزئة لهذا  com.aspose.psd.RectangleF  الهيكل.

**Returns:**
int - رمز التجزئة لهذا  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


ينشئ ويعيد نسخة موسعة من الهيكل  com.aspose.psd.RectangleF  المحدد. يتم توسيع النسخة بالمقدار المحدد. يظل المستطيل الأصلي غير معدل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | الـ  com.aspose.psd.RectangleF  المراد نسخه. هذا المستطيل غير معدل. |
| س | float | المقدار لتوسيع نسخة المستطيل أفقياً. |
| ص | float | المقدار لتوسيع نسخة المستطيل عمودياً. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


يوسع هذا  com.aspose.psd.RectangleF  بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | المقدار لتوسيع هذا المستطيل. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


يوسع هذا الهيكل  com.aspose.psd.RectangleF  بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | المقدار لتوسيع هذا الهيكل  com.aspose.psd.RectangleF  أفقياً. |
| ص | float | المقدار لتوسيع هذا الهيكل  com.aspose.psd.RectangleF  عمودياً. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


يستبدل هذا الهيكل  com.aspose.psd.RectangleF  بالتقاطع بينه وبين الهيكل المحدد  com.aspose.psd.RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل للتقاطع. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


يعيد هيكل  com.aspose.psd.RectangleF  يمثل تقاطع مستطيلين. إذا لم يكن هناك تقاطع، يتم إرجاع  com.aspose.psd.RectangleF  فارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الأول للتقاطع. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الثاني للتقاطع. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


يحدد ما إذا كان هذا المستطيل يتقاطع مع  rect .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل للاختبار. |

**Returns:**
boolean - تُرجع هذه الطريقة true إذا كان هناك أي تقاطع.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كانت الخاصية  com.aspose.psd.RectangleF.Width  أو  com.aspose.psd.RectangleF.Height  لهذا  com.aspose.psd.RectangleF  لها قيمة صفر.

**Returns:**
boolean - تُرجع هذه الخاصية true إذا كان خاصية  com.aspose.psd.RectangleF.Width  أو  com.aspose.psd.RectangleF.Height  لهذا  com.aspose.psd.RectangleF  تساوي صفر؛ وإلا false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


يضرب قيم المستطيل الحالية لتحويل قيم مقياس المصفوفة العمودية والأفقية ويعيد نسخة جديدة من [RectangleF](../../com.aspose.psd/rectanglef) بالقيم الناتجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transformMatrix | double[] | مصفوفة تحويل الطبقة. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أعلى من الأسفل.

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


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | المقدار لإزاحة الموقع. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | المقدار لإزاحة الموقع أفقياً. |
| ص | float | المقدار لإزاحة الموقع عمودياً. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


ينفّذ العامل /.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل. |
| فاصل | float | الفاصل. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


يفحص ما إذا كان هيكلان  com.aspose.psd.RectangleF  لهما موقع وحجم متساويين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | الهيكل  com.aspose.psd.RectangleF  الذي يقع إلى يسار عامل المساواة. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | الهيكل  com.aspose.psd.RectangleF  الذي يقع إلى يمين عامل المساواة. |

**Returns:**
boolean - يرجع هذا العامل true إذا كان الهيكلان  com.aspose.psd.RectangleF  المحددان يمتلكان خصائص  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , و  com.aspose.psd.RectangleF.Height  متساوية.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


يفحص ما إذا كان هيكلان  com.aspose.psd.RectangleF  يختلفان في الموقع أو الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | الهيكل  com.aspose.psd.RectangleF  الذي يقع إلى يسار عامل عدم المساواة. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | الهيكل  com.aspose.psd.RectangleF  الذي يقع إلى يمين عامل عدم المساواة. |

**Returns:**
boolean - يرجع هذا العامل true إذا كان أي من خصائص  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width أو  com.aspose.psd.RectangleF.Height  للهيكلين  com.aspose.psd.RectangleF  غير متساوية؛ وإلا false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


ينفّذ العامل \*.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل. |
| المضاعف | float | المضاعف. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


يحصل أو يعيّن إحداثي y الذي هو مجموع com.aspose.psd.RectangleF.Y و com.aspose.psd.RectangleF.Height لهذا بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


يحصل أو يعيّن ارتفاع هذه بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


يحصل أو يعيّن إحداثي x للحافة اليسرى لهذه بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


يحصل أو يعيّن إحداثيات الزاوية العلوية اليسرى لهذه بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


يحصل أو يعيّن إحداثي x الذي هو مجموع com.aspose.psd.RectangleF.X و com.aspose.psd.RectangleF.Width لهذه بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


يحصل أو يعيّن حجم هذه بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


يحصل أو يعيّن إحداثي y للحافة العلوية لهذه بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


يحصل أو يعيّن عرض هذه بنية com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


يحصل أو يعيّن إحداثي x للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


يحصل أو يعيّن إحداثي y للزاوية العلوية اليسرى لهذه بنية com.aspose.psd RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


يحوّل [RectangleF](../../com.aspose.psd/rectanglef) إلى هيكل [Rectangle](../../com.aspose.psd/rectangle) بقيم مستطيل مقصوصة.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


يحوّل سمات هذا  com.aspose.psd.RectangleF  إلى سلسلة قابلة للقراءة للإنسان.

**Returns:**
java.lang.String - سلسلة تحتوي على الموضع والعرض والارتفاع لهذا الهيكل  com.aspose.psd.RectangleF.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


يحوّل الهيكل المحدد  com.aspose.psd.Rectangle  إلى هيكل  com.aspose.psd.RectangleF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | الهيكل  com.aspose.psd.Rectangle  المراد تحويله. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


ينشئ أصغر مستطيل ثالث ممكن يمكنه احتواء مستطيلين يشكلان اتحادًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الأول للدمج. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | المستطيل الثاني للدمج. |

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


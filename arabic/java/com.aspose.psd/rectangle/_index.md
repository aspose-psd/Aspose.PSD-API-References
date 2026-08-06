---
title: "مستطيل"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل."
type: docs
weight: 88
url: /ar/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | ينشئ نسخة جديدة من هيكل  com.aspose.psd.Rectangle  بالموقع والحجم المحددين. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | ينشئ نسخة جديدة من هيكل  com.aspose.psd.Rectangle  بالموقع والحجم المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | يحوّل الهيكل  com.aspose.psd.RectangleF  المحدد إلى هيكل  com.aspose.psd.Rectangle  عن طريق تقريب قيم  com.aspose.psd.RectangleF  إلى القيم الصحيحة الأعلى. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل  com.aspose.psd.Rectangle . |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها  rect  موجودة بالكامل داخل هذا الهيكل  com.aspose.psd.Rectangle . |
| [contains(int x, int y)](#contains-int-int-) | يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل  com.aspose.psd.Rectangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | يفحص ما إذا كان  obj  هو هيكل  com.aspose.psd.Rectangle  له نفس الموقع والحجم لهذا الهيكل  com.aspose.psd.Rectangle . |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | ينشئ هيكل  com.aspose.psd.Rectangle  بالمواقع المحددة للحواف. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | ينشئ Rectangle جديدًا من نقطتين محددتين. |
| [getBottom()](#getBottom--) | يحصل أو يعيّن إحداثي الصادي الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Height لهذا الهيكل com.aspose.psd.Rectangle. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | يحصل على نسخة جديدة من هيكل com.aspose.psd.Rectangle تكون قيم com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Width و com.aspose.psd.Rectangle.Height فيها صفر. |
| [getHeight()](#getHeight--) | يحصل أو يعيّن ارتفاع هذا الهيكل com.aspose.psd.Rectangle. |
| [getLeft()](#getLeft--) | يحصل أو يعيّن إحداثي السين للحد الأيسر لهذا الهيكل com.aspose.psd.Rectangle. |
| [getLocation()](#getLocation--) | يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle. |
| [getRight()](#getRight--) | يحصل أو يعيّن إحداثي السين الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Width لهذا الهيكل com.aspose.psd.Rectangle. |
| [getSize()](#getSize--) | يحصل أو يعيّن حجم هذا الهيكل com.aspose.psd.Rectangle. |
| [getTop()](#getTop--) | يحصل أو يعيّن إحداثي الصادي للحد العلوي لهذا الهيكل com.aspose.psd.Rectangle. |
| [getWidth()](#getWidth--) | يحصل على عرض هذا الهيكل com.aspose.psd.Rectangle. |
| [getX()](#getX--) | يحصل أو يعيّن إحداثي السين للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle. |
| [getY()](#getY--) | يحصل أو يعيّن إحداثي الصادي للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle. |
| [hashCode()](#hashCode--) | يرجع رمز التجزئة لهذا الهيكل com.aspose.psd.Rectangle. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | ينشئ ويرجع نسخة موسعة من هيكل com.aspose.psd.Rectangle المحدد. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | يوسّع هذا الهيكل com.aspose.psd.Rectangle بالمقدار المحدد. |
| [inflate(int width, int height)](#inflate-int-int-) | يوسّع هذا الهيكل com.aspose.psd.Rectangle بالمقدار المحدد. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | يستبدل هذا الهيكل com.aspose.psd.Rectangle بالتقاطع بينه وبين الهيكل com.aspose.psd.Rectangle المحدد. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | يرجع هيكلاً ثالثًا من نوع com.aspose.psd.Rectangle يمثل تقاطع هيكلين آخرين من نوع com.aspose.psd.Rectangle. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | يحدد ما إذا كان هذا المستطيل يتقاطع مع  rect . |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا الهيكل com.aspose.psd.Rectangle لها قيم صفر. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | يحصل على قيمة تشير إلى ما إذا كان هذا Rectangle مرئيًا جزئيًا على الأقل |
| [normalize()](#normalize--) | يُعَدِّل المستطيل بجعل عرضه وارتفاعه إيجابيين، واليسار أصغر من اليمين، والعلو أعلى من الأسفل. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [offset(int x, int y)](#offset-int-int-) | يضبط موقع هذا المستطيل بالمقدار المحدد. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | يفحص ما إذا كان هيكلا com.aspose.psd.Rectangle لهما موقع وحجم متساويين. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | يفحص ما إذا كان هيكلا com.aspose.psd.Rectangle يختلفان في الموقع أو الحجم. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | يحوّل الـ com.aspose.psd.RectangleF المحدد إلى com.aspose.psd.Rectangle عن طريق تقريب قيم com.aspose.psd.RectangleF إلى أقرب قيم صحيحة. |
| [setBottom(int value)](#setBottom-int-) | يحصل أو يعيّن إحداثي الصادي الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Height لهذا الهيكل com.aspose.psd.Rectangle. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن ارتفاع هذا الهيكل com.aspose.psd.Rectangle. |
| [setLeft(int value)](#setLeft-int-) | يحصل أو يعيّن إحداثي السين للحد الأيسر لهذا الهيكل com.aspose.psd.Rectangle. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle. |
| [setRight(int value)](#setRight-int-) | يحصل أو يعيّن إحداثي السين الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Width لهذا الهيكل com.aspose.psd.Rectangle. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | يحصل أو يعيّن حجم هذا الهيكل com.aspose.psd.Rectangle. |
| [setTop(int value)](#setTop-int-) | يحصل أو يعيّن إحداثي الصادي للحد العلوي لهذا الهيكل com.aspose.psd.Rectangle. |
| [setWidth(int value)](#setWidth-int-) | يعيّن عرض هذا الهيكل com.aspose.psd.Rectangle. |
| [setX(int value)](#setX-int-) | يحصل أو يعيّن إحداثي السين للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle. |
| [setY(int value)](#setY-int-) | يحصل أو يعيّن إحداثي الصادي للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle. |
| [toString()](#toString--) | يحوّل سمات هذا الهيكل com.aspose.psd.Rectangle إلى سلسلة قابلة للقراءة البشرية. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | يحوّل الـ com.aspose.psd.RectangleF المحدد إلى com.aspose.psd.Rectangle عن طريق قطع قيم com.aspose.psd.RectangleF. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | يحصل على هيكل com.aspose.psd.Rectangle يحتوي على اتحاد هيكلين من نوع com.aspose.psd.Rectangle. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


ينشئ نسخة جديدة من هيكل  com.aspose.psd.Rectangle  بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل. |
| ص | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل. |
| العرض | int | عرض المستطيل. |
| الارتفاع | int | ارتفاع المستطيل. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


ينشئ نسخة جديدة من هيكل  com.aspose.psd.Rectangle  بالموقع والحجم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | نقطة com.aspose.psd.Point تمثل الزاوية العلوية اليسرى للمنطقة المستطيلة. |
| size | [Size](../../com.aspose.psd/size) | حجم com.aspose.psd.Size يمثل العرض والارتفاع للمنطقة المستطيلة. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


يحوّل الهيكل  com.aspose.psd.RectangleF  المحدد إلى هيكل  com.aspose.psd.Rectangle  عن طريق تقريب قيم  com.aspose.psd.RectangleF  إلى القيم الصحيحة الأعلى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | هيكل com.aspose.psd.RectangleF المراد تحويله. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل  com.aspose.psd.Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | نقطة com.aspose.psd.Point للاختبار. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كانت النقطة الممثلة بـ point موجودة داخل هيكل com.aspose.psd.Rectangle هذا؛ وإلا false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


يحدد ما إذا كانت المنطقة المستطيلة التي يمثلها  rect  موجودة بالكامل داخل هذا الهيكل  com.aspose.psd.Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل com.aspose.psd.Rectangle للاختبار. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كانت المنطقة المستطيلة الممثلة بـ rect موجودة بالكامل داخل هيكل com.aspose.psd.Rectangle هذا؛ وإلا false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا الهيكل  com.aspose.psd.Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للنقطة للاختبار. |
| ص | int | الإحداثي الصادي للنقطة للاختبار. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كانت النقطة المعرفة بـ x و y موجودة داخل هيكل com.aspose.psd.Rectangle هذا؛ وإلا false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يفحص ما إذا كان  obj  هو هيكل  com.aspose.psd.Rectangle  له نفس الموقع والحجم لهذا الهيكل  com.aspose.psd.Rectangle .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ  System.Object  للاختبار. |

**Returns:**
منطقية - تُعيد هذه الطريقة true إذا كان obj هو هيكل com.aspose.psd.Rectangle وكانت خصائصه com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Width و com.aspose.psd.Rectangle.Height مساوية للخصائص المقابلة في هيكل com.aspose.psd.Rectangle هذا؛ وإلا false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


ينشئ هيكل  com.aspose.psd.Rectangle  بالمواقع المحددة للحواف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | int | الإحداثي السيني للزاوية العلوية اليسرى لهذا هيكل com.aspose.psd.Rectangle. |
| top | int | الإحداثي الصادي للزاوية العلوية اليسرى لهذا هيكل com.aspose.psd.Rectangle. |
| right | int | الإحداثي السيني للزاوية السفلية اليمنى لهذا هيكل com.aspose.psd.Rectangle. |
| bottom | int | الإحداثي الصادي للزاوية السفلية اليمنى لهذا هيكل com.aspose.psd.Rectangle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


ينشئ مستطيلًا جديدًا Rectangle من نقطتين محددتين. ستكون الرأسان العموديان للمستطيل المُنشأ مساويين للنقطتين point1 و point2 الممررتين. عادةً ما تكون هاتان النقطتان الرؤوس المتقابلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | النقطة الأولى  Point  للمستطيل الجديد. |
| point2 | [Point](../../com.aspose.psd/point) | النقطة الثانية  Point  للمستطيل الجديد. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


يحصل أو يعيّن إحداثي الصادي الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Height لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - الإحداثي الصادي الذي هو مجموع com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Height لهذا com.aspose.psd.Rectangle.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


يحصل على نسخة جديدة من هيكل com.aspose.psd.Rectangle تكون قيم com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Width و com.aspose.psd.Rectangle.Height فيها صفر.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل أو يعيّن ارتفاع هذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - ارتفاع هذا هيكل com.aspose.psd.Rectangle.
### getLeft() {#getLeft--}
```
public int getLeft()
```


يحصل أو يعيّن إحداثي السين للحد الأيسر لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - الإحداثي السيني للحافة اليسرى لهذا هيكل com.aspose.psd.Rectangle.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


يحصل أو يعيّن إحداثي السين الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Width لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - الإحداثي السيني الذي هو مجموع com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Width لهذا com.aspose.psd.Rectangle.
### getSize() {#getSize--}
```
public Size getSize()
```


يحصل أو يعيّن حجم هذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


يحصل أو يعيّن إحداثي الصادي للحد العلوي لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - الإحداثي الصادي للحافة العلوية لهذا هيكل com.aspose.psd.Rectangle.
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض هذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - عرض هذا هيكل com.aspose.psd.Rectangle.
### getX() {#getX--}
```
public int getX()
```


يحصل أو يعيّن إحداثي السين للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - الإحداثي السيني للزاوية العلوية اليسرى لهذا هيكل com.aspose.psd.Rectangle.
### getY() {#getY--}
```
public int getY()
```


يحصل أو يعيّن إحداثي الصادي للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - الإحداثي الصادي للزاوية العلوية اليسرى لهذا هيكل com.aspose.psd.Rectangle.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز التجزئة لهذا الهيكل com.aspose.psd.Rectangle.

**Returns:**
int - عدد صحيح يمثل رمز التجزئة لهذا المستطيل.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


ينشئ ويعيد نسخة موسعة من هيكل com.aspose.psd.Rectangle المحدد. يتم توسيع النسخة بالمقدار المحدد. يظل هيكل com.aspose.psd.Rectangle الأصلي غير معدل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | هيكل com.aspose.psd.Rectangle للبدء به. هذا المستطيل غير معدل. |
| س | int | المقدار لتوسيع هذا  com.aspose.psd.Rectangle  أفقياً. |
| ص | int | المقدار لتوسيع هذا  com.aspose.psd.Rectangle  عمودياً. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


يوسّع هذا الهيكل com.aspose.psd.Rectangle بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | المقدار لتوسيع هذا المستطيل. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


يوسّع هذا الهيكل com.aspose.psd.Rectangle بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | المقدار لتوسيع هذا  com.aspose.psd.Rectangle  أفقياً. |
| الارتفاع | int | المقدار لتوسيع هذا  com.aspose.psd.Rectangle  عمودياً. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


يستبدل هذا الهيكل com.aspose.psd.Rectangle بالتقاطع بينه وبين الهيكل com.aspose.psd.Rectangle المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | الـ  com.aspose.psd.Rectangle  الذي سيتم التقاطع معه. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


يرجع بنية  com.aspose.psd.Rectangle  ثالثة تمثل تقاطع بنيتين أخريين من نوع  com.aspose.psd.Rectangle . إذا لم يكن هناك تقاطع، يتم إرجاع  com.aspose.psd.Rectangle  فارغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الأول للتقاطع. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الثاني للتقاطع. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


يحدد ما إذا كان هذا المستطيل يتقاطع مع  rect .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل للاختبار. |

**Returns:**
منطقي - تُرجع هذه الطريقة true إذا كان هناك أي تقاطع، وإلا false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كانت جميع الخصائص الرقمية لهذا الهيكل com.aspose.psd.Rectangle لها قيم صفر.

**Returns:**
منطقي - تُرجع هذه الخاصية true إذا كانت خصائص  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X , و  com.aspose.psd.Rectangle.Y  لهذا  com.aspose.psd.Rectangle  جميعها تساوي الصفر؛ وإلا false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


يحصل على قيمة تشير إلى ما إذا كان هذا Rectangle مرئيًا جزئيًا على الأقل

**Returns:**
منطقي -  true  إذا كان هذا  Rectangle  مرئياً جزئياً على الأقل؛ وإلا  false .
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | المقدار لإزاحة الموقع. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


يضبط موقع هذا المستطيل بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإزاحة الأفقية. |
| ص | int | الإزاحة العمودية. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


يفحص ما إذا كان هيكلا com.aspose.psd.Rectangle لهما موقع وحجم متساويين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | بنية  com.aspose.psd.Rectangle  التي تقع إلى يسار عامل المساواة. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | بنية  com.aspose.psd.Rectangle  التي تقع إلى يمين عامل المساواة. |

**Returns:**
منطقي - يُرجع هذا العامل true إذا كانت بنية  com.aspose.psd.Rectangle  الاثنين تمتلك خصائص  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , و  com.aspose.psd.Rectangle.Height  متساوية.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


يفحص ما إذا كان هيكلا com.aspose.psd.Rectangle يختلفان في الموقع أو الحجم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | بنية  com.aspose.psd.Rectangle  التي تقع إلى يسار عامل عدم المساواة. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | بنية  com.aspose.psd.Rectangle  التي تقع إلى يمين عامل عدم المساواة. |

**Returns:**
منطقي - يُرجع هذا العامل true إذا كان أي من خصائص  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  أو  com.aspose.psd.Rectangle.Height  للبنيتين  com.aspose.psd.Rectangle  غير متساوية؛ وإلا false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


يحوّل الـ com.aspose.psd.RectangleF المحدد إلى com.aspose.psd.Rectangle عن طريق تقريب قيم com.aspose.psd.RectangleF إلى أقرب قيم صحيحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | الـ  com.aspose.psd.RectangleF  المراد تحويله. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


يحصل أو يعيّن إحداثي الصادي الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.Y و com.aspose.psd.Rectangle.Height لهذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي y الذي هو مجموع  com.aspose.psd.Rectangle.Y  و  com.aspose.psd.Rectangle.Height  لهذا  com.aspose.psd.Rectangle . |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


يحصل أو يعيّن ارتفاع هذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | ارتفاع هذه بنية  com.aspose.psd.Rectangle . |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


يحصل أو يعيّن إحداثي السين للحد الأيسر لهذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي x للحافة اليسرى لهذه بنية  com.aspose.psd.Rectangle . |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


يحصل أو يعيّن إحداثيات الزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | نقطة  Point  تمثل الزاوية العليا اليسرى لهذه بنية  com.aspose.psd.Rectangle . |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


يحصل أو يعيّن إحداثي السين الذي هو مجموع قيمتي الخاصيتين com.aspose.psd.Rectangle.X و com.aspose.psd.Rectangle.Width لهذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي x الذي هو مجموع  com.aspose.psd.Rectangle.X  و  com.aspose.psd.Rectangle.Width  لهذا  com.aspose.psd.Rectangle . |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


يحصل أو يعيّن حجم هذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | كائن  com.aspose.psd.Size  يمثل العرض والارتفاع لهذه بنية  com.aspose.psd.Rectangle . |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


يحصل أو يعيّن إحداثي الصادي للحد العلوي لهذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي y للحافة العليا لهذه بنية  com.aspose.psd.Rectangle . |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


يعيّن عرض هذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | عرض هذه بنية  com.aspose.psd.Rectangle . |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


يحصل أو يعيّن إحداثي السين للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي السيني للزاوية العلوية اليسرى لهذا هيكل com.aspose.psd.Rectangle. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


يحصل أو يعيّن إحداثي الصادي للزاوية العليا اليسرى لهذا الهيكل com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الإحداثي الصادي للزاوية العلوية اليسرى لهذا هيكل com.aspose.psd.Rectangle. |

### toString() {#toString--}
```
public String toString()
```


يحوّل سمات هذا الهيكل com.aspose.psd.Rectangle إلى سلسلة قابلة للقراءة البشرية.

**Returns:**
java.lang.String - سلسلة تحتوي على الموضع والعرض والارتفاع لهذا الهيكل com.aspose.psd.Rectangle.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


يحوّل الـ com.aspose.psd.RectangleF المحدد إلى com.aspose.psd.Rectangle عن طريق قطع قيم com.aspose.psd.RectangleF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | الـ  com.aspose.psd.RectangleF  المراد تحويله. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


يحصل على هيكل com.aspose.psd.Rectangle يحتوي على اتحاد هيكلين من نوع com.aspose.psd.Rectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الأول للدمج. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | المستطيل الثاني للدمج. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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


---
title: "Point"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل زوجًا مرتبًا من إحداثيات x و y الصحيحة التي تحدد نقطة في مستوى ثنائي الأبعاد."
type: docs
weight: 82
url: /ar/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

يمثل زوجًا مرتبًا من إحداثيات x و y الصحيحة التي تحدد نقطة في مستوى ثنائي الأبعاد.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | ينشئ نسخة جديدة من بنية  Aspose.Imaging.Point  مع الإحداثيات المحددة. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | ينشئ نسخة جديدة من بنية  Aspose.Imaging.Point  من بنية  Aspose.Imaging.Size . |
| [Point(int dw)](#Point-int-) | ينشئ نسخة جديدة من بنية  Aspose.Imaging.Point  باستخدام إحداثيات محددة بقيمة عدد صحيح. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | يمثّل تنسيق النقطة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | يضيف الـ  Aspose.Imaging.Size  المحدد إلى الـ  Aspose.Imaging.Point  المحدد. |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | يحوّل الـ  Aspose.Imaging.PointF  المحدد إلى  Aspose.Imaging.Point  عن طريق تقريب قيم الـ  Aspose.Imaging.PointF  إلى القيم الصحيحة الأعلى التالية. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان هذا  Aspose.Imaging.Point  يحتوي على نفس الإحداثيات كما هو محدد في  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | يحصل على نسخة جديدة من بنية  Aspose.Imaging.Point  التي تحتوي على قيم  Aspose.Imaging.Point.X  و  Aspose.Imaging.Point.Y  مضبوطة على الصفر. |
| [getX()](#getX--) | يحصل أو يضبط إحداثي x لهذا  Aspose.Imaging.Point . |
| [getY()](#getY--) | يحصل أو يضبط إحداثي y لهذا  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذا  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | يحصل على قيمة تشير إلى ما إذا كان هذا  Aspose.Imaging.Point  فارغًا. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | ينقل هذا  Aspose.Imaging.Point  بواسطة  Aspose.Imaging.Point  المحدد. |
| [offset(int dx, int dy)](#offset-int-int-) | ينقل هذا  Aspose.Imaging.Point  بالمقدار المحدد. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | ينقل  Aspose.Imaging.Point  بواسطة  Aspose.Imaging.Size  المعطى. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | يقارن كائنين من نوع  Aspose.Imaging.Point . |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | يقارن كائنين من نوع  Aspose.Imaging.Point . |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | ينقل  Aspose.Imaging.Point  بالسالب من  Aspose.Imaging.Size  المعطى. |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | يحوّل  Aspose.Imaging.PointF  المحدد إلى كائن  Aspose.Imaging.Point  عن طريق تقريب قيم  Aspose.Imaging.Point  إلى أقرب عدد صحيح. |
| [setX(int value)](#setX-int-) | يحصل أو يضبط إحداثي x لهذا  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | يحصل أو يضبط إحداثي y لهذا  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | يرجع نتيجة طرح  Aspose.Imaging.Size  المحدد من  Aspose.Imaging.Point  المحدد. |
| [toString()](#toString--) | يحوّل هذا  Aspose.Imaging.Point  إلى سلسلة قابلة للقراءة من قبل الإنسان. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | يحوّل بنية  Point  المحددة إلى بنية  PointF . |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | يحوّل بنية  Aspose.Imaging.Point  المحددة إلى بنية  Aspose.Imaging.Size . |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | يحوّل  Aspose.Imaging.PointF  المحدد إلى  Aspose.Imaging.Point  عن طريق قطع قيم  Aspose.Imaging.Point . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


ينشئ نسخة جديدة من بنية  Aspose.Imaging.Point  مع الإحداثيات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الموضع الأفقي للنقطة. |
| ص | int | الموضع العمودي للنقطة. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


ينشئ نسخة جديدة من بنية  Aspose.Imaging.Point  من بنية  Aspose.Imaging.Size .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | يحتوي على إحداثيات النقطة الجديدة. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


ينشئ نسخة جديدة من بنية  Aspose.Imaging.Point  باستخدام إحداثيات محددة بقيمة عدد صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dw | int | عدد صحيح 32‑بت يحدد الإحداثيات للنقطة الجديدة. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


يمثّل تنسيق النقطة.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


يضيف الـ  Aspose.Imaging.Size  المحدد إلى الـ  Aspose.Imaging.Point  المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | الـ  Aspose.Imaging.Point  للإضافة إليه. |
| size | [Size](../../com.aspose.psd/size) | الـ  Aspose.Imaging.Size  للإضافة إلى الـ نقطة . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


يحوّل الـ  Aspose.Imaging.PointF  المحدد إلى  Aspose.Imaging.Point  عن طريق تقريب قيم الـ  Aspose.Imaging.PointF  إلى القيم الصحيحة الأعلى التالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | الـ  Aspose.Imaging.PointF  للتحويل. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان هذا  Aspose.Imaging.Point  يحتوي على نفس الإحداثيات كما هو محدد في  System.Object .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ  System.Object  للاختبار. |

**Returns:**
منطقي - صحيح إذا كان  obj  هو  Aspose.Imaging.Point  ويملك نفس الإحداثيات كما هذا  Aspose.Imaging.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


يحصل على نسخة جديدة من بنية  Aspose.Imaging.Point  التي تحتوي على قيم  Aspose.Imaging.Point.X  و  Aspose.Imaging.Point.Y  مضبوطة على الصفر.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


يحصل أو يضبط إحداثي x لهذا  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


يحصل أو يضبط إحداثي y لهذا  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذا  Aspose.Imaging.Point .

**Returns:**
int - رمز تجزئة لهذا الكائن، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يحصل على قيمة تشير إلى ما إذا كان هذا  Aspose.Imaging.Point  فارغًا.

**Returns:**
منطقي - صحيح إذا كان كل من  Aspose.Imaging.Point.X  و  Aspose.Imaging.Point.Y  يساويان 0؛ وإلا، خطأ.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

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




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


ينقل هذا  Aspose.Imaging.Point  بواسطة  Aspose.Imaging.Point  المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | نقطة Aspose.Imaging.Point المستخدمة لإزاحة هذه النقطة Aspose.Imaging.Point. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


ينقل هذا  Aspose.Imaging.Point  بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | int | القيمة لإزاحة إحداثي x. |
| dy | int | القيمة لإزاحة إحداثي y. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


ينقل  Aspose.Imaging.Point  بواسطة  Aspose.Imaging.Size  المعطى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | نقطة Aspose.Imaging.Point للتحويل. |
| size | [Size](../../com.aspose.psd/size) | حجم Aspose.Imaging.Size يحدد زوج الأرقام لإضافتها إلى إحداثيات النقطة. |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


يقارن كائنين من نوع Aspose.Imaging.Point. النتيجة تحدد ما إذا كانت قيم خصائص Aspose.Imaging.Point.X و Aspose.Imaging.Point.Y لكائنين Aspose.Imaging.Point متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | النقطة الأولى Aspose.Imaging.Point للمقارنة. |
| point2 | [Point](../../com.aspose.psd/point) | النقطة الثانية Aspose.Imaging.Point للمقارنة. |

**Returns:**
منطقي - صحيح إذا كانت قيم Aspose.Imaging.Point.X و Aspose.Imaging.Point.Y للنقطة point1 والنقطة point2 متساوية؛ وإلا، خطأ.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


يقارن كائنين من نوع Aspose.Imaging.Point. النتيجة تحدد ما إذا كانت قيم خصائص Aspose.Imaging.Point.X أو Aspose.Imaging.Point.Y لكائنين Aspose.Imaging.Point غير متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | النقطة الأولى Aspose.Imaging.Point للمقارنة. |
| point2 | [Point](../../com.aspose.psd/point) | النقطة الثانية Aspose.Imaging.Point للمقارنة. |

**Returns:**
منطقي - صحيح إذا كانت قيم إما خصائص Aspose.Imaging.Point.X أو خصائص Aspose.Imaging.Point.Y للنقطة point1 والنقطة point2 مختلفة؛ وإلا، خطأ.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


ينقل  Aspose.Imaging.Point  بالسالب من  Aspose.Imaging.Size  المعطى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | نقطة Aspose.Imaging.Point للتحويل. |
| size | [Size](../../com.aspose.psd/size) | حجم Aspose.Imaging.Size يحدد زوج الأرقام لطرحها من إحداثيات النقطة. |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


يحوّل  Aspose.Imaging.PointF  المحدد إلى كائن  Aspose.Imaging.Point  عن طريق تقريب قيم  Aspose.Imaging.Point  إلى أقرب عدد صحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | الـ  Aspose.Imaging.PointF  للتحويل. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


يحصل أو يضبط إحداثي x لهذا  Aspose.Imaging.Point .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


يحصل أو يضبط إحداثي y لهذا  Aspose.Imaging.Point .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


يرجع نتيجة طرح  Aspose.Imaging.Size  المحدد من  Aspose.Imaging.Point  المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | نقطة Aspose.Imaging.Point التي سيتم الطرح منها. |
| size | [Size](../../com.aspose.psd/size) | حجم Aspose.Imaging.Size للطرح من النقطة. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


يحوّل هذا  Aspose.Imaging.Point  إلى سلسلة قابلة للقراءة من قبل الإنسان.

**Returns:**
java.lang.String - سلسلة System.String تمثل هذه الحالة.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


يحوّل بنية  Point  المحددة إلى بنية  PointF .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | النقطة Point التي سيتم تحويلها. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


يحوّل بنية  Aspose.Imaging.Point  المحددة إلى بنية  Aspose.Imaging.Size .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | نقطة Aspose.Imaging.Point التي سيتم تحويلها. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


يحوّل  Aspose.Imaging.PointF  المحدد إلى  Aspose.Imaging.Point  عن طريق قطع قيم  Aspose.Imaging.Point .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | الـ  Aspose.Imaging.PointF  للتحويل. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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


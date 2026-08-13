---
title: "الفئة Point"
type: docs
weight: 3530
url: /ar/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Point()](#Point__1) | يُنشئ نسخة جديدة من الفئة Point |
| [Point(dw)](#Point_dw_2) | يُنشئ نسخة جديدة من بنية [Point](/psd/python-net/aspose.psd/point/) باستخدام إحداثيات محددة بقيمة عدد صحيح. |
| [Point(size)](#Point_size_3) | يُنشئ نسخة جديدة من بنية [Point](/psd/python-net/aspose.psd/point/) من بنية [Size](/psd/python-net/aspose.psd/size/). |
| [Point(x, y)](#Point_x_y_4) | يُنشئ نسخة جديدة من بنية [Point](/psd/python-net/aspose.psd/point/) بالإحداثيات المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | يحصل على نسخة جديدة من بنية [Point](/psd/python-net/aspose.psd/point/) التي تكون قيم [Point.x](/psd/python-net/aspose.psd/point/) و[Point.y](/psd/python-net/aspose.psd/point/) فيها صفر. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Point](/psd/python-net/aspose.psd/point/) فارغًا. |
| x | int | r/w | يحصل أو يعيّن الإحداثي x لهذا [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | يحصل أو يعيّن الإحداثي y لهذا [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | يضيف الـ[Size](/psd/python-net/aspose.psd/size/) المحدد إلى الـ[Point](/psd/python-net/aspose.psd/point/) المحدد. |
| [ceiling(point)](#ceiling_point_2) | يقوم بتحويل الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد إلى [Point](/psd/python-net/aspose.psd/point/) عن طريق تقريب قيم الـ [PointF](/psd/python-net/aspose.psd/pointf/) إلى القيم الصحيحة الأعلى. |
| [offset(dx, dy)](#offset_dx_dy_3) | ينقل هذا الـ [Point](/psd/python-net/aspose.psd/point/) بالمقدار المحدد. |
| [offset(point)](#offset_point_4) | ينقل هذا الـ [Point](/psd/python-net/aspose.psd/point/) بالـ [Point](/psd/python-net/aspose.psd/point/) المحدد. |
| [round(point)](#round_point_5) | يقوم بتحويل الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد إلى كائن [Point](/psd/python-net/aspose.psd/point/) عن طريق تقريب قيم الـ [Point](/psd/python-net/aspose.psd/point/) إلى أقرب عدد صحيح. |
| [subtract(point, size)](#subtract_point_size_6) | يعيد نتيجة طرح الـ [Size](/psd/python-net/aspose.psd/size/) المحدد من الـ [Point](/psd/python-net/aspose.psd/point/) المحدد. |
| [truncate(point)](#truncate_point_7) | يقوم بتحويل الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد إلى [Point](/psd/python-net/aspose.psd/point/) عن طريق قطع قيم الـ [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

يُنشئ نسخة جديدة من الفئة Point

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

يُنشئ نسخة جديدة من بنية [Point](/psd/python-net/aspose.psd/point/) باستخدام إحداثيات محددة بقيمة عدد صحيح.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dw | int | عدد صحيح 32‑بت يحدد إحداثيات النقطة الجديدة. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

يُنشئ نسخة جديدة من بنية [Point](/psd/python-net/aspose.psd/point/) من بنية [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | يحتوي على إحداثيات النقطة الجديدة. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

يُنشئ نسخة جديدة من بنية [Point](/psd/python-net/aspose.psd/point/) بالإحداثيات المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| x | int | الموضع الأفقي للنقطة. |
| y | int | الموضع الرأسي للنقطة. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

يضيف الـ[Size](/psd/python-net/aspose.psd/size/) المحدد إلى الـ[Point](/psd/python-net/aspose.psd/point/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) للإضافة إليه. |
| size | [Size](/psd/python-net/aspose.psd/size) | الـ [Size](/psd/python-net/aspose.psd/size/) للإضافة إلى <paramref name="point" />. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) الناتج عن عملية الجمع. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

يقوم بتحويل الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد إلى [Point](/psd/python-net/aspose.psd/point/) عن طريق تقريب قيم الـ [PointF](/psd/python-net/aspose.psd/pointf/) إلى القيم الصحيحة الأعلى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) للتحويل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) الذي تقوم هذه الطريقة بتحويله. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

ينقل هذا الـ [Point](/psd/python-net/aspose.psd/point/) بالمقدار المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| dx | int | القيمة لإزاحة إحداثي x. |
| dy | int | القيمة لإزاحة إحداثي y. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

ينقل هذا الـ [Point](/psd/python-net/aspose.psd/point/) بالـ [Point](/psd/python-net/aspose.psd/point/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) المستخدم لإزاحة هذا الـ [Point](/psd/python-net/aspose.psd/point/). |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

يقوم بتحويل الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد إلى كائن [Point](/psd/python-net/aspose.psd/point/) عن طريق تقريب قيم الـ [Point](/psd/python-net/aspose.psd/point/) إلى أقرب عدد صحيح.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) للتحويل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) الذي تقوم هذه الطريقة بتحويله. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

يعيد نتيجة طرح الـ [Size](/psd/python-net/aspose.psd/size/) المحدد من الـ [Point](/psd/python-net/aspose.psd/point/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) ليُطرح منه. |
| size | [Size](/psd/python-net/aspose.psd/size) | الـ [Size](/psd/python-net/aspose.psd/size/) ليُطرح من <paramref name="point" />. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) الناتج عن عملية الطرح. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

يقوم بتحويل الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد إلى [Point](/psd/python-net/aspose.psd/point/) عن طريق قطع قيم الـ [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) للتحويل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | الـ [Point](/psd/python-net/aspose.psd/point/) الذي تقوم هذه الطريقة بتحويله. |



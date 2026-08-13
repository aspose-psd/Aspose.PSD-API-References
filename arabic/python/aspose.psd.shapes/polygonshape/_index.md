---
title: "PolygonShape فئة"
type: docs
weight: 60
url: /ar/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | يُنشئ مثلاً جديداً من الفئة [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | يُنشئ مثلاً جديداً من الفئة [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | يُنشئ مثلاً جديداً من الفئة [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل على حدود الكائن. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على مركز الشكل. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة النهاية للشكل. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| is_closed | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | يحصل أو يضبط نقاط المنحنى. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | يحصل على مقاطع الشكل. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة بداية الشكل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| reverse() | يعكس ترتيب النقاط لهذا الشكل. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

يُنشئ مثلاً جديداً من الفئة [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

يُنشئ مثلاً جديداً من الفئة [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة النقاط. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

يُنشئ مثلاً جديداً من الفئة [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة النقاط. |
| is_closed | bool | إذا تم تعيينها إلى <c>true</c> يكون المضلع مغلقًا. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | سيتم حساب المصفوفة التي ستُطبق قبل الحدود. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | حدود الكائن المقدرة. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | سيتم حساب المصفوفة التي ستُطبق قبل الحدود. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | حدود الكائن المقدرة. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | التحويل الذي سيُطبق. |


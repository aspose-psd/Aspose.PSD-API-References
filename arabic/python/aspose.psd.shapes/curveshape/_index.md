---
title: "فئة CurveShape"
type: docs
weight: 30
url: /ar/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). يتم استخدام شد افتراضي قدره 0.5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). يتم استخدام شد افتراضي قدره 0.5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
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
| الشد | float | r/w | يحصل أو يضبط شد المنحنى. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| reverse() | يعكس ترتيب النقاط لهذا الشكل. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). يتم استخدام شد افتراضي قدره 0.5.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة النقاط. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). يتم استخدام شد افتراضي قدره 0.5.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة النقاط. |
| is_closed | bool | إذا تم تعيينها إلى <c>true</c> يكون المنحنى مغلقًا. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة النقاط. |
| الشد | float | شد المنحنى. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

ينشئ مثيلًا جديدًا من الفئة [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | مصفوفة النقاط. |
| الشد | float | شد المنحنى. |
| is_closed | bool | إذا تم تعيينها إلى <c>true</c> يكون المنحنى مغلقًا. |

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


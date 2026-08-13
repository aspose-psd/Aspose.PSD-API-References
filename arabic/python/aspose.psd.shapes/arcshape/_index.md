---
title: "فئة ArcShape"
type: docs
weight: 10
url: /ar/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | ينشئ مثيلاً جديداً من الفئة [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | ينشئ مثيلاً جديداً من الفئة [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | ينشئ مثيلاً جديداً من الفئة [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل على حدود الكائن. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على مركز الشكل. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة النهاية للشكل. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| is_closed | bool | r/w | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان الشكل المرتب مغلقًا. عند معالجة الشكل المرتب المغلق لا يكون للنقطة البداية والنهاية أي معنى. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية السفلية اليسرى للمستطيل. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية العلوية اليسرى للمستطيل. |
| rectangle_height | double | r | يحصل على ارتفاع المستطيل. |
| rectangle_width | double | r | يحصل على عرض المستطيل. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية السفلية اليمنى للمستطيل. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية العلوية اليمنى للمستطيل. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | يحصل على مقاطع الشكل. |
| start_angle | float | r/w | يسترجع أو يعيّن زاوية البداية. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة بداية الشكل. |
| sweep_angle | float | r/w | يسترجع أو يعيّن زاوية المسح. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| reverse() | يعكس ترتيب النقاط لهذا الشكل. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

ينشئ مثيلاً جديداً من الفئة [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

ينشئ مثيلاً جديداً من الفئة [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل. |
| start_angle | float | زاوية البداية. |
| sweep_angle | float | زاوية المسح. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

ينشئ مثيلاً جديداً من الفئة [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل. |
| start_angle | float | زاوية البداية. |
| sweep_angle | float | زاوية المسح. |
| is_closed | bool | إذا تم تعيينه إلى <c>true</c> فإن القوس مغلق. القوس المغلق يتحول فعليًا إلى إهليلج. |

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


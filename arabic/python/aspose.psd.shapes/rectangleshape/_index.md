---
title: "فئة RectangleShape"
type: docs
weight: 80
url: /ar/python-net/aspose.psd.shapes/rectangleshape/
---

**Summary:** Represents a rectangular shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [RectangleShape()](#RectangleShape__1) | ينشئ مثيلاً جديداً من الفئة [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/). |
| [RectangleShape(rectangle)](#RectangleShape_rectangle_2) | ينشئ مثيلاً جديداً من الفئة [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل على حدود الكائن. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على مركز الشكل. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية السفلية اليسرى للمستطيل. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية العلوية اليسرى للمستطيل. |
| rectangle_height | double | r | يحصل على ارتفاع المستطيل. |
| rectangle_width | double | r | يحصل على عرض المستطيل. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية السفلية اليمنى للمستطيل. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية العلوية اليمنى للمستطيل. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | يحصل على مقاطع الشكل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: RectangleShape() {#RectangleShape__1}


```
 RectangleShape() 
```

ينشئ مثيلاً جديداً من الفئة [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/).

### Constructor: RectangleShape(rectangle) {#RectangleShape_rectangle_2}


```
 RectangleShape(rectangle) 
```

ينشئ مثيلاً جديداً من الفئة [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | المستطيل. |

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


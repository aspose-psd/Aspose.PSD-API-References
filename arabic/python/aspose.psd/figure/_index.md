---
title: "فئة Figure"
type: docs
weight: 1220
url: /ar/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Figure()](#Figure__1) | ينشئ نسخة جديدة من فئة Figure |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل أو يضبط حدود الكائن. |
| is_closed | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. سيُحدث الشكل المغلق فرقًا فقط في الحالة التي<br/>            تكون فيها الأشكال الأولى والأخيرة للشكل متصلة بشكل مستمر. في هذه الحالة، سيتم ربط النقطة الأولى للشكل الأول<br/>            بخط مستقيم من النقطة الأخيرة للشكل الأخير. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | يحصل على جميع مقاطع الشكل. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | يحصل على أشكال الشكل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | يضيف شكلاً إلى الشكل. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | يضيف مجموعة من الأشكال إلى الشكل. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | يحصل على حدود الكائن. |
| [remove_shape(shape)](#remove_shape_shape_5) | يزيل شكلاً من الشكل. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | يزيل مجموعة من الأشكال من الشكل. |
| reverse() | يعكس ترتيب الأشكال في هذا الشكل وترتيب نقاط الأشكال. |
| [transform(transform)](#transform_transform_7) | يطبق التحويل المحدد على الشكل. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

ينشئ نسخة جديدة من فئة Figure

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

يضيف شكلاً إلى الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | الشكل للإضافة. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

يضيف مجموعة من الأشكال إلى الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | الأشكال للإضافة. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

يزيل شكلاً من الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | الشكل للإزالة. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

يزيل مجموعة من الأشكال من الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | مجموعة الأشكال للإزالة. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | التحويل الذي سيُطبق. |


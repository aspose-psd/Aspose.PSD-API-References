---
title: "RectangleShape 类"
type: docs
weight: 80
url: /zh/python-net/aspose.psd.shapes/rectangleshape/
---

**Summary:** Represents a rectangular shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleShape()](#RectangleShape__1) | 初始化 [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) 类的新实例。 |
| [RectangleShape(rectangle)](#RectangleShape_rectangle_2) | 初始化 [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取对象的边界。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的中心。 |
| has_segments | bool | r | 获取指示形状是否具有段的值。 |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取左下矩形点。 |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取左上矩形点。 |
| rectangle_height | double | r | 获取矩形高度。 |
| rectangle_width | double | r | 获取矩形宽度。 |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取右下矩形点。 |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取右上矩形点。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 获取形状段。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: RectangleShape() {#RectangleShape__1}


```
 RectangleShape() 
```

初始化 [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) 类的新实例。

### Constructor: RectangleShape(rectangle) {#RectangleShape_rectangle_2}


```
 RectangleShape(rectangle) 
```

初始化 [RectangleShape](/psd/python-net/aspose.psd.shapes/rectangleshape/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

获取对象的边界。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 将在计算边界之前应用的矩阵。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 估计的对象边界。 |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

获取对象的边界。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 将在计算边界之前应用的矩阵。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于对象的笔。这可能影响对象边界的大小。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 估计的对象边界。 |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 要应用的变换。 |


---
title: "PieShape 类"
type: docs
weight: 50
url: /zh/python-net/aspose.psd.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PieShape

**Inheritance:** EllipseShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PieShape()](#PieShape__1) | 初始化一个新的 [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) 类实例。 |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | 初始化一个新的 [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) 类实例。 |
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
| start_angle | float | 读/写 | 获取或设置起始角度。 |
| sweep_angle | float | 读/写 | 获取或设置扫掠角度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

初始化一个新的 [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) 类实例。

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

初始化一个新的 [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形。 |
| start_angle | float | 起始角度。 |
| sweep_angle | float | 扫掠角度。 |

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


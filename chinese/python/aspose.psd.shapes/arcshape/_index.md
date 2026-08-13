---
title: "ArcShape 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | 初始化 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 类的新实例。 |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | 初始化 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 类的新实例。 |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | 初始化 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取对象的边界。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的中心。 |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的结束点。 |
| has_segments | bool | r | 获取指示形状是否具有段的值。 |
| is_closed | bool | 读/写 | 获取或设置一个值，指示有序形状是否闭合。处理闭合的有序形状时，起始点和结束点没有意义。 |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取左下矩形点。 |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取左上矩形点。 |
| rectangle_height | double | r | 获取矩形高度。 |
| rectangle_width | double | r | 获取矩形宽度。 |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取右下矩形点。 |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取右上矩形点。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 获取形状段。 |
| start_angle | float | 读/写 | 获取或设置起始角度。 |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的起始点。 |
| sweep_angle | float | 读/写 | 获取或设置扫掠角度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| reverse() | 反转此形状的点的顺序。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

初始化 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 类的新实例。

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

初始化 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形。 |
| start_angle | float | 起始角度。 |
| sweep_angle | float | 扫掠角度。 |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

初始化 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形。 |
| start_angle | float | 起始角度。 |
| sweep_angle | float | 扫掠角度。 |
| is_closed | bool | 如果设置为 <c>true</c>，弧线将闭合。闭合的弧线实际上会退化为椭圆。 |

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


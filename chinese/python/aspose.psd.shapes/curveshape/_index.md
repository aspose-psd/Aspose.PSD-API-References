---
title: "CurveShape 类"
type: docs
weight: 30
url: /zh/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | 初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。 |
| [CurveShape(points)](#CurveShape_points_2) | 初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。使用默认张力 0.5。 |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | 初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。使用默认张力 0.5。 |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | 初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。 |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | 初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取对象的边界。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的中心。 |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的结束点。 |
| has_segments | bool | r | 获取指示形状是否具有段的值。 |
| is_closed | bool | 读/写 | 获取或设置指示形状是否闭合的值。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | 获取或设置曲线点。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 获取形状段。 |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的起始点。 |
| 张力 | float | 读/写 | 获取或设置曲线张力。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| reverse() | 反转此形状的点的顺序。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。使用默认张力 0.5。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 点数组。 |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。使用默认张力 0.5。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 点数组。 |
| is_closed | bool | 如果设置为 <c>true</c>，曲线将闭合。 |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 点数组。 |
| 张力 | float | 曲线张力。 |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

初始化一个新的 [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 点数组。 |
| 张力 | float | 曲线张力。 |
| is_closed | bool | 如果设置为 <c>true</c>，曲线将闭合。 |

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


---
title: "PolygonShape 类"
type: docs
weight: 60
url: /zh/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | 初始化 [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) 类的新实例。 |
| [PolygonShape(points)](#PolygonShape_points_2) | 初始化 [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) 类的新实例。 |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | 初始化 [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) 类的新实例。 |
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
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| reverse() | 反转此形状的点的顺序。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

初始化 [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) 类的新实例。

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

初始化 [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 点数组。 |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

初始化 [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 点数组。 |
| is_closed | bool | 如果设置为 <c>true</c>，多边形将闭合。 |

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


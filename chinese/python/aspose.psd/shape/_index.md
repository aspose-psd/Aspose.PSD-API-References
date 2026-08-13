---
title: "Shape 类"
type: docs
weight: 4020
url: /zh/python-net/aspose.psd/shape/
---

**Summary:** The shape. A continuous set of points connected using a specific rule.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Shape

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取对象的边界。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取形状的中心。 |
| has_segments | bool | r | 获取指示形状是否具有段的值。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 获取形状段。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


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


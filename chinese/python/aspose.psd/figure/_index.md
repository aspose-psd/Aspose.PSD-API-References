---
title: "Figure 类"
type: docs
weight: 1220
url: /zh/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | 初始化 Figure 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取或设置对象的边界。 |
| is_closed | bool | 读/写 | 获取或设置一个值，指示此图形是否闭合。闭合图形仅在以下情况会产生差异：<br/>            第一个和最后一个图形的形状是连续形状时。在这种情况下，第一个形状的起点将会<br/>            通过一条直线与最后一个形状的终点相连。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 获取整个图形的段。 |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | 获取图形的形状。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | 向图形添加一个形状。 |
| [add_shapes(shapes)](#add_shapes_shapes_2) | 向图形添加一系列形状。 |
| [get_bounds(matrix)](#get_bounds_matrix_3) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | 获取对象的边界。 |
| [remove_shape(shape)](#remove_shape_shape_5) | 从图形中移除一个形状。 |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | 从图形中移除一系列形状。 |
| reverse() | 反转此图形的形状顺序和形状点顺序。 |
| [transform(transform)](#transform_transform_7) | 对形状应用指定的变换。 |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

初始化 Figure 类的新实例

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

向图形添加一个形状。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | 要添加的形状。 |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

向图形添加一系列形状。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | 要添加的形状。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

从图形中移除一个形状。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | 要移除的形状。 |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

从图形中移除一系列形状。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | 要移除的形状范围。 |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 要应用的变换。 |


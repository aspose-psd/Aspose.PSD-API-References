---
title: "Point 类"
type: docs
weight: 3530
url: /zh/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | 初始化 Point 类的新实例 |
| [Point(dw)](#Point_dw_2) | 使用整数值指定的坐标初始化 [Point](/psd/python-net/aspose.psd/point/) 结构的新实例。 |
| [Point(size)](#Point_size_3) | 从 [Size](/psd/python-net/aspose.psd/size/) 结构初始化 [Point](/psd/python-net/aspose.psd/point/) 结构的新实例。 |
| [Point(x, y)](#Point_x_y_4) | 使用指定的坐标初始化 [Point](/psd/python-net/aspose.psd/point/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | 获取一个新的 [Point](/psd/python-net/aspose.psd/point/) 结构实例，其 [Point.x](/psd/python-net/aspose.psd/point/) 和 [Point.y](/psd/python-net/aspose.psd/point/) 值均为零。 |
| is_empty | bool | r | 获取一个值，指示此 [Point](/psd/python-net/aspose.psd/point/) 是否为空。 |
| x | int | r/w | 获取或设置此 [Point](/psd/python-net/aspose.psd/point/) 的 x 坐标。 |
| y | int | r/w | 获取或设置此 [Point](/psd/python-net/aspose.psd/point/) 的 y 坐标。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 将指定的 [Size](/psd/python-net/aspose.psd/size/) 添加到指定的 [Point](/psd/python-net/aspose.psd/point/)。 |
| [ceiling(point)](#ceiling_point_2) | 通过将 [PointF](/psd/python-net/aspose.psd/pointf/) 的值向上取整到下一个更高的整数，将指定的 [PointF] 转换为 [Point](/psd/python-net/aspose.psd/point/)。 |
| [offset(dx, dy)](#offset_dx_dy_3) | 按指定的量平移此 [Point](/psd/python-net/aspose.psd/point/)。 |
| [offset(point)](#offset_point_4) | 按指定的 [Point](/psd/python-net/aspose.psd/point/) 平移此 [Point](/psd/python-net/aspose.psd/point/)。 |
| [round(point)](#round_point_5) | 通过将 [Point](/psd/python-net/aspose.psd/point/) 的值四舍五入到最近的整数，将指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 转换为 [Point](/psd/python-net/aspose.psd/point/) 对象。 |
| [subtract(point, size)](#subtract_point_size_6) | 返回从指定的 [Point](/psd/python-net/aspose.psd/point/) 中减去指定的 [Size](/psd/python-net/aspose.psd/size/) 的结果。 |
| [truncate(point)](#truncate_point_7) | 通过截断 [Point](/psd/python-net/aspose.psd/point/) 的值，将指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 转换为 [Point](/psd/python-net/aspose.psd/point/)。 |


### Constructor: Point() {#Point__1}


```
 Point() 
```

初始化 Point 类的新实例

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

使用整数值指定的坐标初始化 [Point](/psd/python-net/aspose.psd/point/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dw | int | 一个指定新点坐标的 32 位整数。 |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

从 [Size](/psd/python-net/aspose.psd/size/) 结构初始化 [Point](/psd/python-net/aspose.psd/point/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | 包含新点坐标。 |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

使用指定的坐标初始化 [Point](/psd/python-net/aspose.psd/point/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 点的水平位置。 |
| y | int | 点的垂直位置。 |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

将指定的 [Size](/psd/python-net/aspose.psd/size/) 添加到指定的 [Point](/psd/python-net/aspose.psd/point/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 要添加的 [Point](/psd/python-net/aspose.psd/point/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 要添加到 <paramref name="point" /> 的 [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 加法运算的结果 [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

通过将 [PointF](/psd/python-net/aspose.psd/pointf/) 的值向上取整到下一个更高的整数，将指定的 [PointF] 转换为 [Point](/psd/python-net/aspose.psd/point/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要转换的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 此方法转换为的 [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

按指定的量平移此 [Point](/psd/python-net/aspose.psd/point/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | int | 用于偏移 x 坐标的量。 |
| dy | int | 用于偏移 y 坐标的量。 |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

按指定的 [Point](/psd/python-net/aspose.psd/point/) 平移此 [Point](/psd/python-net/aspose.psd/point/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 用于偏移此 [Point](/psd/python-net/aspose.psd/point/) 的 [Point](/psd/python-net/aspose.psd/point/)。 |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

通过将 [Point](/psd/python-net/aspose.psd/point/) 的值四舍五入到最近的整数，将指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 转换为 [Point](/psd/python-net/aspose.psd/point/) 对象。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要转换的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 此方法转换为的 [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

返回从指定的 [Point](/psd/python-net/aspose.psd/point/) 中减去指定的 [Size](/psd/python-net/aspose.psd/size/) 的结果。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 要从中减去的 [Point](/psd/python-net/aspose.psd/point/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 要从 <paramref name="point" /> 中减去的 [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 减法运算的结果 [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

通过截断 [Point](/psd/python-net/aspose.psd/point/) 的值，将指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 转换为 [Point](/psd/python-net/aspose.psd/point/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要转换的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 此方法转换为的 [Point](/psd/python-net/aspose.psd/point/)。 |



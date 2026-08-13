---
title: "RectangleF 类"
type: docs
weight: 3830
url: /zh/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | 初始化 RectangleF 类的新实例 |
| [RectangleF(location, size)](#RectangleF_location_size_2) | 使用指定的位置和大小初始化 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的新实例。 |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | 使用指定的位置和大小初始化 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的 y 坐标，该坐标为该结构的 [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) 与 [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) 的和。 |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取一个新的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构实例，其 [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/)、[RectangleF.y](/psd/python-net/aspose.psd/rectanglef/)、[RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) 和 [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) 的值均为零。 |
| height | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的高度。 |
| is_empty | bool | r | 获取一个值，指示此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 的 [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) 或 [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) 属性是否为零。 |
| left | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构左边缘的 x 坐标。 |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构左上角的坐标。 |
| right | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的 x 坐标，该坐标为该结构的 [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) 与 [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) 的和。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 的大小。 |
| top | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构顶部边缘的 y 坐标。 |
| width | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的宽度。 |
| x | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构左上角的 x 坐标。 |
| y | float | r/w | 获取或设置此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构左上角的 y 坐标。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | 确定指定的点是否包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中。 |
| [contains(rect)](#contains_rect_2) | 确定由 <paramref name="rect" /> 表示的矩形区域是否完全包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中。 |
| [contains(x, y)](#contains_x_y_3) | 确定指定的点是否包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中。 |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | 使用指定位置的左上角和右下角创建一个 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| [from_points(point1, point2)](#from_points_point1_point2_5) | 从两个指定的点创建一个新的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 。创建的 [Rectangle] 的两个顶点将等于传入的 <paramref name="point1" /> 和 <paramref name="point2" />。这些通常是相对的顶点。 |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | 创建并返回指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的膨胀副本。副本按指定的量进行膨胀。原始矩形保持不变。 |
| [inflate(size)](#inflate_size_7) | 按指定的量膨胀此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| [inflate(x, y)](#inflate_x_y_8) | 按指定的量膨胀此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| [intersect(a, b)](#intersect_a_b_9) | 返回一个表示两个矩形交集的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。如果没有交集，则返回空的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| [intersect(rect)](#intersect_rect_10) | 用自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的交集替换此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| [intersects_with(rect)](#intersects_with_rect_11) | 确定此矩形是否与 <paramref name="rect" /> 相交。 |
| normalize() | 通过使宽度和高度为正、左小于右、上小于下，对矩形进行规范化。 |
| [offset(pos)](#offset_pos_12) | 按指定的量调整此矩形的位置。 |
| [offset(x, y)](#offset_x_y_13) | 按指定的量调整此矩形的位置。 |
| [union(a, b)](#union_a_b_14) | 创建能够容纳两个矩形并形成并集的最小可能的第三个矩形。 |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

初始化 RectangleF 类的新实例

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

使用指定的位置和大小初始化 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | 表示矩形区域左上角的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 表示矩形区域宽度和高度的 [SizeF](/psd/python-net/aspose.psd/sizef/)。 |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

使用指定的位置和大小初始化 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 矩形左上角的 x 坐标。 |
| y | float | 矩形左上角的 y 坐标。 |
| width | float | 矩形的宽度。 |
| height | float | 矩形的高度。 |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

确定指定的点是否包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 用于测试的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果 <paramref name="point" /> 参数表示的点包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中，则此方法返回 true；否则返回 false。 |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

确定由 <paramref name="rect" /> 表示的矩形区域是否完全包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 用于测试的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果由 <paramref name="rect" /> 表示的矩形区域完全包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 表示的矩形区域中，则此方法返回 true；否则返回 false。 |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

确定指定的点是否包含在此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果由 <paramref name="x" /> 和 <paramref name="y" /> 定义的点位于此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构中，则此方法返回 true；否则返回 false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

使用指定位置的左上角和右下角创建一个 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| left | float | 矩形区域左上角的 x 坐标. |
| top | float | 矩形区域左上角的 y 坐标. |
| right | float | 矩形区域右下角的 x 坐标. |
| 底部 | float | 矩形区域右下角的 y 坐标. |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 此方法创建的新的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

从两个指定的点创建一个新的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 。创建的 [Rectangle] 的两个顶点将等于传入的 <paramref name="point1" /> 和 <paramref name="point2" />。这些通常是相对的顶点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | 新矩形的第一个 [Point](/psd/python-net/aspose.psd/point/). |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | 新矩形的第二个 [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 新创建的 [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

创建并返回指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的膨胀副本。副本按指定的量进行膨胀。原始矩形保持不变。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要复制的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。此矩形不会被修改. |
| x | float | 水平膨胀矩形副本的量. |
| y | float | 垂直膨胀矩形副本的量. |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 膨胀后的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

按指定的量膨胀此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 膨胀此矩形的量. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

按指定的量膨胀此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 水平膨胀此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的量. |
| y | float | 垂直膨胀此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的量. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

返回一个表示两个矩形交集的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。如果没有交集，则返回空的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 第一个要相交的矩形. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 第二个要相交的矩形. |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 第三个 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构，其大小表示两个指定矩形的重叠区域. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

用自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的交集替换此 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要相交的矩形. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

确定此矩形是否与 <paramref name="rect" /> 相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要测试的矩形. |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果存在任何交集，此方法返回 true. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

按指定的量调整此矩形的位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | 偏移位置的量. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

按指定的量调整此矩形的位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 水平偏移位置的量. |
| y | float | 垂直偏移位置的量. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

创建能够容纳两个矩形并形成并集的最小可能的第三个矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 第一个用于合并的矩形。 |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 第二个用于合并的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 第三个 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构，包含形成合并的两个矩形。 |



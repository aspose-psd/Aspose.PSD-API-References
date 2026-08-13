---
title: "Rectangle 类"
type: docs
weight: 3810
url: /zh/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | 初始化 Rectangle 类的新实例 |
| [Rectangle(location, size)](#Rectangle_location_size_2) | 使用指定的位置和大小初始化 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的新实例。 |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | 使用指定的位置和大小初始化 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中 y 坐标，该坐标为 [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) 与 [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) 属性值之和。 |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 获取一个新的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构实例，其 [Rectangle.x]、[Rectangle.y]、[Rectangle.width] 和 [Rectangle.height] 的值均为零。 |
| height | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的高度。 |
| is_empty | bool | r | 获取一个值，指示此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 的所有数值属性是否为零。 |
| left | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构左边缘的 x 坐标。 |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构左上角的坐标。 |
| right | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中 x 坐标，该坐标为 [Rectangle.x] 与 [Rectangle.width] 属性值之和。 |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的大小。 |
| top | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构顶部边缘的 y 坐标。 |
| width | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的宽度。 |
| x | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构左上角的 x 坐标。 |
| y | int | r/w | 获取或设置此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构左上角的 y 坐标。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | 通过将 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 的值向上取整为更大的整数，将指定的 [RectangleF] 结构转换为 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。 |
| [contains(point)](#contains_point_2) | 确定指定的点是否包含在此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中。 |
| [contains(rect)](#contains_rect_3) | 确定由 <paramref name=\"rect\" /> 表示的矩形区域是否完全包含在此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中。 |
| [contains(x, y)](#contains_x_y_4) | 确定指定的点是否包含在此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中。 |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | 使用指定的边缘位置创建一个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。 |
| [from_points(point1, point2)](#from_points_point1_point2_6) | 从两个指定的点创建一个新的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。创建的 [Rectangle] 的两个垂直边将等于传入的 <paramref name=\"point1\" /> 和 <paramref name=\"point2\" />。这些通常是相对的顶点。 |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | 创建并返回指定的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的膨胀副本。该副本按指定的量进行膨胀。原始的 [Rectangle] 结构保持不变。 |
| [inflate(size)](#inflate_size_8) | 按指定的量膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| [inflate(width, height)](#inflate_width_height_9) | 按指定的量膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| [intersect(a, b)](#intersect_a_b_10) | 返回一个第三个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构，表示另外两个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的交集。如果没有交集，则返回一个空的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| [intersect(rect)](#intersect_rect_11) | 用自身与指定的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 的交集替换此 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| [intersects_with(rect)](#intersects_with_rect_12) | 确定此矩形是否与 <paramref name="rect" /> 相交。 |
| normalize() | 通过使宽度和高度为正、左小于右、上小于下，对矩形进行规范化。 |
| [offset(pos)](#offset_pos_13) | 按指定的量调整此矩形的位置。 |
| [offset(x, y)](#offset_x_y_14) | 按指定的量调整此矩形的位置。 |
| [round(value)](#round_value_15) | 通过将指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 值四舍五入到最近的整数，将其转换为 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| [truncate(value)](#truncate_value_16) | 通过截断指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 值，将其转换为 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| [union(a, b)](#union_a_b_17) | 获取一个包含两个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构并集的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。 |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

初始化 Rectangle 类的新实例

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

使用指定的位置和大小初始化 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | 表示矩形区域左上角的 [Point](/psd/python-net/aspose.psd/point/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 表示矩形区域宽度和高度的 [Size](/psd/python-net/aspose.psd/size/)。 |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

使用指定的位置和大小初始化 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 矩形左上角的 x 坐标。 |
| y | int | 矩形左上角的 y 坐标。 |
| width | int | 矩形的宽度。 |
| height | int | 矩形的高度。 |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

通过将 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 的值向上取整为更大的整数，将指定的 [RectangleF] 结构转换为 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要转换的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 返回一个 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

确定指定的点是否包含在此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 要测试的 [Point](/psd/python-net/aspose.psd/point/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果 <paramref name=\"point\" /> 表示的点位于此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构内，则此方法返回 true；否则返回 false。 |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

确定由 <paramref name=\"rect\" /> 表示的矩形区域是否完全包含在此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 要测试的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果 <paramref name=\"rect\" /> 表示的矩形区域完全位于此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构内，则此方法返回 true；否则返回 false。 |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

确定指定的点是否包含在此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果由 <paramref name=\"x\" /> 和 <paramref name=\"y\" /> 定义的点位于此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构内，则此方法返回 true；否则返回 false。 |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

使用指定的边缘位置创建一个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| left | int | 此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构左上角的 x 坐标。 |
| top | int | 此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构左上角的 y 坐标。 |
| right | int | 此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构右下角的 x 坐标。 |
| bottom | int | 此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构右下角的 y 坐标。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 此方法创建的新 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

从两个指定的点创建一个新的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。创建的 [Rectangle] 的两个垂直边将等于传入的 <paramref name=\"point1\" /> 和 <paramref name=\"point2\" />。这些通常是相对的顶点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | 新矩形的第一个 [Point](/psd/python-net/aspose.psd/point/). |
| point2 | [Point](/psd/python-net/aspose.psd/point) | 新矩形的第二个 [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 新创建的 [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

创建并返回指定的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的膨胀副本。该副本按指定的量进行膨胀。原始的 [Rectangle] 结构保持不变。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于开始的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。此矩形不会被修改。 |
| x | int | 水平膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 的量。 |
| y | int | 垂直膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 的量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 已膨胀的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

按指定的量膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | 膨胀此矩形的量. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

按指定的量膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 水平膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 的量。 |
| height | int | 垂直膨胀此 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 的量。 |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

返回一个第三个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构，表示另外两个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的交集。如果没有交集，则返回一个空的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 第一个要相交的矩形. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 第二个要相交的矩形. |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 表示 <paramref name=\"a\" /> 与 <paramref name=\"b\" /> 交集的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

用自身与指定的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 的交集替换此 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于相交的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

确定此矩形是否与 <paramref name="rect" /> 相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 要测试的矩形. |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果存在任何相交，则此方法返回 true，否则返回 false。 |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

按指定的量调整此矩形的位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | 位置的偏移量。 |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

按指定的量调整此矩形的位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 水平偏移量。 |
| y | int | 垂直偏移量。 |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

通过将指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 值四舍五入到最近的整数，将其转换为 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要转换的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 一个新的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

通过截断指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 值，将其转换为 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要转换的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 一个新的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

获取一个包含两个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构并集的 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 第一个用于合并的矩形。 |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 第二个用于合并的矩形。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 一个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构，用于界定两个 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 结构的并集。 |



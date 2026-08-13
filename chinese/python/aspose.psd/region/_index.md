---
title: "Region 类"
type: docs
weight: 3870
url: /zh/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Region()](#Region__1) | 初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。 |
| [Region(path)](#Region_path_2) | 使用指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。 |
| [Region(rect)](#Region_rect_3) | 从指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。 |
| [Region(rect)](#Region_rect_4) | 从指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [complement(path)](#complement_path_1) | 更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。 |
| [complement(rect)](#complement_rect_2) | 更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。 |
| [complement(rect)](#complement_rect_3) | 更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。 |
| [complement(region)](#complement_region_4) | 更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[Region](/psd/python-net/aspose.psd/region/)中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。 |
| [deep_clone()](#deep_clone__5) | 创建此[Region](/psd/python-net/aspose.psd/region/)的精确深拷贝。 |
| [exclude(path)](#exclude_path_6) | 更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)相交的部分。 |
| [exclude(rect)](#exclude_rect_7) | 更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构相交的部分。 |
| [exclude(rect)](#exclude_rect_8) | 更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构相交的部分。 |
| [exclude(region)](#exclude_region_9) | 更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[Region](/psd/python-net/aspose.psd/region/)相交的部分。 |
| [intersect(path)](#intersect_path_10) | 将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)的交集。 |
| [intersect(rect)](#intersect_rect_11) | 将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的交集。 |
| [intersect(rect)](#intersect_rect_12) | 将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的交集。 |
| [intersect(region)](#intersect_region_13) | 将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[Region](/psd/python-net/aspose.psd/region/)的交集。 |
| [is_empty(g)](#is_empty_g_14) | 测试此[Region](/psd/python-net/aspose.psd/region/)在指定绘图表面上是否具有空的内部。 |
| [is_infinite(g)](#is_infinite_g_15) | 测试此[Region](/psd/python-net/aspose.psd/region/)在指定绘图表面上是否具有无限的内部。 |
| [is_visible(point)](#is_visible_point_16) | 测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(point)](#is_visible_point_17) | 测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(point, g)](#is_visible_point_g_18) | 在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(point, g)](#is_visible_point_g_19) | 在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(rect)](#is_visible_rect_20) | 测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(rect)](#is_visible_rect_21) | 测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(rect, g)](#is_visible_rect_g_22) | 在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(rect, g)](#is_visible_rect_g_23) | 在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(x, y)](#is_visible_x_y_24) | 测试指定的点是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | 在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的点是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | 在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的点是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。 |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | 测试指定矩形的任何部分是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。 |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | 测试指定矩形的任何部分是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。 |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | 测试指定矩形的任何部分在使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。 |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | 测试指定矩形的任何部分在使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。 |
| make_empty() | 将此 [Region](/psd/python-net/aspose.psd/region/) 初始化为空内部。 |
| make_infinite() | 将此 [Region](/psd/python-net/aspose.psd/region/) 对象初始化为无限内部。 |
| [transform(matrix)](#transform_matrix_31) | 通过指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 转换此 [Region](/psd/python-net/aspose.psd/region/)。 |
| [translate(dx, dy)](#translate_dx_dy_32) | 按指定的量偏移此 [Region](/psd/python-net/aspose.psd/region/) 的坐标。 |
| [translate(dx, dy)](#translate_dx_dy_33) | 按指定的量偏移此 [Region](/psd/python-net/aspose.psd/region/) 的坐标。 |
| [union(path)](#union_path_34) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的并集。 |
| [union(rect)](#union_rect_35) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集。 |
| [union(rect)](#union_rect_36) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集。 |
| [union(region)](#union_region_37) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [Region](/psd/python-net/aspose.psd/region/) 的并集。 |
| [xor(path)](#xor_path_38) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的并集减去交集。 |
| [xor(rect)](#xor_rect_39) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集减去交集。 |
| [xor(rect)](#xor_rect_40) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集减去交集。 |
| [xor(region)](#xor_region_41) | 将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [Region](/psd/python-net/aspose.psd/region/) 的并集减去交集。 |


### Constructor: Region() {#Region__1}


```
 Region() 
```

初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

使用指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 用于定义新 [Region](/psd/python-net/aspose.psd/region/) 的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

从指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 用于定义新 [Region](/psd/python-net/aspose.psd/region/) 内部的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

从指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构初始化一个新的[Region](/psd/python-net/aspose.psd/region/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于定义新 [Region](/psd/python-net/aspose.psd/region/) 内部的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 用于补充此 [Region](/psd/python-net/aspose.psd/region/) 的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 用于补充此 [Region](/psd/python-net/aspose.psd/region/) 的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 用于补充此 [Region](/psd/python-net/aspose.psd/region/) 的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，使其包含指定的[Region](/psd/python-net/aspose.psd/region/)中未与此[Region](/psd/python-net/aspose.psd/region/)相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 用于补充此 [Region](/psd/python-net/aspose.psd/region/) 对象的 [Region](/psd/python-net/aspose.psd/region/) 对象。 |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

创建此[Region](/psd/python-net/aspose.psd/region/)的精确深拷贝。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | 此方法创建的 [Region](/psd/python-net/aspose.psd/region/)。 |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 从此 [Region](/psd/python-net/aspose.psd/region/) 中排除的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 从此 [Region](/psd/python-net/aspose.psd/region/) 中排除的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 从此 [Region](/psd/python-net/aspose.psd/region/) 中排除的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

更新此[Region](/psd/python-net/aspose.psd/region/)，仅保留其内部未与指定的[Region](/psd/python-net/aspose.psd/region/)相交的部分。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 从此 [Region](/psd/python-net/aspose.psd/region/) 中排除的 [Region](/psd/python-net/aspose.psd/region/)。 |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)的交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 与此 [Region](/psd/python-net/aspose.psd/region/) 相交的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 与此 [Region](/psd/python-net/aspose.psd/region/) 相交的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 与此 [Region](/psd/python-net/aspose.psd/region/) 相交的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

将此[Region](/psd/python-net/aspose.psd/region/)更新为其自身与指定的[Region](/psd/python-net/aspose.psd/region/)的交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 与此 [Region](/psd/python-net/aspose.psd/region/) 相交的 [Region](/psd/python-net/aspose.psd/region/)。 |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

测试此[Region](/psd/python-net/aspose.psd/region/)在指定绘图表面上是否具有空的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示绘图表面的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果在应用与 <paramref name="g" /> 关联的变换时，此 [Region](/psd/python-net/aspose.psd/region/) 的内部为空，则为 true；否则为 false。 |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

测试此[Region](/psd/python-net/aspose.psd/region/)在指定绘图表面上是否具有无限的内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示绘图表面的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果在应用与 <paramref name="g" /> 关联的变换时，此 [Region](/psd/python-net/aspose.psd/region/) 的内部是无限的，则为 true；否则为 false。 |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要测试的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="point" /> 位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 要测试的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="point" /> 位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要测试的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="point" /> 位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[PointF](/psd/python-net/aspose.psd/pointf/)结构是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 要测试的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="point" /> 位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要测试的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="rect" /> 的任何部分位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 要测试的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="rect" /> 的任何部分位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 要测试的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="rect" /> 位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的[RectangleF](/psd/python-net/aspose.psd/rectanglef/)结构的任何部分是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 要测试的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当 <paramref name="rect" /> 位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

测试指定的点是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当指定的点位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 True；否则为 false。 |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的点是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当指定的点位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 True；否则为 false。 |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

在使用指定的[Graphics](/psd/python-net/aspose.psd/graphics/)绘制时，测试指定的点是否包含在此[Region](/psd/python-net/aspose.psd/region/)中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当指定的点位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 True；否则为 false。 |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

测试指定矩形的任何部分是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| width | float | 要测试的矩形的宽度。 |
| height | float | 要测试的矩形的高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/psd/python-net/aspose.psd/region/) 对象内部时为 true；否则为 false。 |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

测试指定矩形的任何部分是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| width | int | 要测试的矩形的宽度。 |
| height | int | 要测试的矩形的高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/psd/python-net/aspose.psd/region/) 对象内部时为 true；否则为 false。 |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

测试指定矩形的任何部分在使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 要测试的矩形左上角的 x 坐标。 |
| y | float | 要测试的矩形左上角的 y 坐标。 |
| width | float | 要测试的矩形的宽度。 |
| height | float | 要测试的矩形的高度。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

测试指定矩形的任何部分在使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时是否包含在此 [Region](/psd/python-net/aspose.psd/region/) 中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 要测试的矩形左上角的 x 坐标。 |
| y | int | 要测试的矩形左上角的 y 坐标。 |
| width | int | 要测试的矩形的宽度。 |
| height | int | 要测试的矩形的高度。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 表示图形上下文的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 当指定矩形的任何部分位于此 [Region](/psd/python-net/aspose.psd/region/) 内部时为 true；否则为 false。 |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

通过指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 转换此 [Region](/psd/python-net/aspose.psd/region/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于转换此 [Region](/psd/python-net/aspose.psd/region/) 的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

按指定的量偏移此 [Region](/psd/python-net/aspose.psd/region/) 的坐标。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | 此 [Region](/psd/python-net/aspose.psd/region/) 水平偏移的量。 |
| dy | float | 此 [Region](/psd/python-net/aspose.psd/region/) 垂直偏移的量。 |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

按指定的量偏移此 [Region](/psd/python-net/aspose.psd/region/) 的坐标。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | int | 此 [Region](/psd/python-net/aspose.psd/region/) 水平偏移的量。 |
| dy | int | 此 [Region](/psd/python-net/aspose.psd/region/) 垂直偏移的量。 |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的并集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 与此 [Region](/psd/python-net/aspose.psd/region/) 合并的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 与此 [Region](/psd/python-net/aspose.psd/region/) 合并的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 与此 [Region](/psd/python-net/aspose.psd/region/) 合并的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [Region](/psd/python-net/aspose.psd/region/) 的并集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 与此 [Region](/psd/python-net/aspose.psd/region/) 合并的 [Region](/psd/python-net/aspose.psd/region/)。 |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的并集减去交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 与此 [Region](/psd/python-net/aspose.psd/region/) 进行异或的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集减去交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 与此 [Region](/psd/python-net/aspose.psd/region/) 进行异或的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构的并集减去交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 与此 [Region](/psd/python-net/aspose.psd/region/) 进行异或的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

将此 [Region](/psd/python-net/aspose.psd/region/) 更新为自身与指定的 [Region](/psd/python-net/aspose.psd/region/) 的并集减去交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 与此 [Region](/psd/python-net/aspose.psd/region/) 进行异或的 [Region](/psd/python-net/aspose.psd/region/)。 |


---
title: "GraphicsPath 类"
type: docs
weight: 1570
url: /zh/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | 初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。 |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | 初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。 |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | 初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。 |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | 初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取或设置对象的边界。 |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | 获取路径图形。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | 获取或设置一个 [FillMode](/psd/python-net/aspose.psd/fillmode/) 枚举，用于确定此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中形状内部的填充方式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | 添加一个新图形。 |
| [add_figures(figures)](#add_figures_figures_2) | 添加新图形。 |
| [add_path(adding_path)](#add_path_adding_path_3) | 将指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 追加到此路径。 |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | 将指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 追加到此路径。 |
| [deep_clone()](#deep_clone__5) | 对该图形路径执行深度克隆。 |
| flatten() | 将此路径中的每条曲线转换为一系列相连的线段。 |
| [flatten(matrix)](#flatten_matrix_6) | 应用指定的变换，然后将此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中的每条曲线转换为一系列相连的线段。 |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | 将此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中的每条曲线转换为一系列相连的线段。 |
| [get_bounds(matrix)](#get_bounds_matrix_8) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | 获取对象的边界。 |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | 指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。 |
| [is_visible(point)](#is_visible_point_18) | 指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。 |
| [is_visible(point)](#is_visible_point_19) | 指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。 |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | 指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。 |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | 指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。 |
| [is_visible(x, y)](#is_visible_x_y_22) | 指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。 |
| [is_visible(x, y)](#is_visible_x_y_23) | 指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。 |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | 指示指定的点是否位于指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 可见裁剪区域内的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中。 |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | 指示指定的点是否位于指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 可见裁剪区域内的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中。 |
| [remove_figure(figure)](#remove_figure_figure_26) | 移除一个图形。 |
| [remove_figures(figures)](#remove_figures_figures_27) | 移除图形。 |
| reset() | 清空图形路径并将 [FillMode](/psd/python-net/aspose.psd/fillmode/) 设置为 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)。 |
| reverse() | 颠倒此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中每个形状的图形、形状和点的顺序。 |
| [transform(transform)](#transform_transform_28) | 对形状应用指定的变换。 |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | 对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | 对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | 对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | 对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。 |
| [widen(pen)](#widen_pen_33) | 为路径添加额外的轮廓。 |
| [widen(pen, matrix)](#widen_pen_matrix_34) | 为 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 添加额外的轮廓。 |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | 使用在使用指定笔绘制此路径时填充的区域所包围的曲线替换此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 用于初始化的图形。 |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 用于初始化的图形。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 填充模式。 |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

初始化 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 填充模式。 |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

添加一个新图形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | 要添加的图形。 |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

添加新图形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 要添加的图形。 |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

将指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 追加到此路径。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 要添加的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

将指定的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 追加到此路径。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 要添加的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |
| 连接 | bool | 一个布尔值，指定在添加的路径中的第一个图形是否是此路径中最后一个图形的一部分。值为 true 表示添加的路径中的第一个图形是此路径中最后一个图形的一部分。值为 false 表示添加的路径中的第一个图形与此路径中最后一个图形分离。 |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

对该图形路径执行深度克隆。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 图形路径的深度克隆。 |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

应用指定的变换，然后将此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中的每条曲线转换为一系列相连的线段。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 在展平之前，用于转换此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

将此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中的每条曲线转换为一系列相连的线段。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 在展平之前，用于转换此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| 平整度 | float | 指定曲线与其展平近似之间允许的最大误差。默认值为 0.25。降低平整度值会增加近似中的线段数量。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


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


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 指定要测试位置的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 指定要测试位置的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | 指定要测试位置的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓下方，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | 指定要测试位置的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓下方，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓下方，则此方法返回 true；否则返回 false。 |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

指示在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 并使用指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 绘制时，指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓内部（下方）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 用于测试的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点在使用指定的 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 的轮廓下方，则此方法返回 true；否则返回 false。 |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 表示要测试点的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部，则此方法返回 true；否则返回 false。 |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 表示要测试点的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部，则此方法返回 true；否则返回 false。 |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | 表示要测试点的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此内部，则此方法返回 true；否则返回 false。 |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | 表示要测试点的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此内部，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

指示指定的点是否位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

指示指定的点是否位于指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 可见裁剪区域内的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 用于测试的点的 x 坐标。 |
| y | float | 用于测试的点的 y 坐标。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部，则此方法返回 true；否则返回 false。 |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

指示指定的点是否位于指定的 [Graphics](/psd/python-net/aspose.psd/graphics/) 可见裁剪区域内的此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | int | 用于测试的点的 x 坐标。 |
| y | int | 用于测试的点的 y 坐标。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 用于测试可见性的 [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果指定的点位于此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内部，则此方法返回 true；否则返回 false。 |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

移除一个图形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | 要移除的图形。 |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

移除图形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 要移除的多个图形。 |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 要应用的变换。 |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 一个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组，定义将由 <paramref name=\"srcRect\" /> 定义的矩形转换为的平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示被转换为由 <paramref name=\"destPoints\" /> 定义的平行四边形的矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 一个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组，定义将由 <paramref name=\"srcRect\" /> 定义的矩形转换为的平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示被转换为由 <paramref name=\"destPoints\" /> 定义的平行四边形的矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 指定要应用于路径的几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 一个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组，定义将由 <paramref name=\"srcRect\" /> 定义的矩形转换为的平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示被转换为由 <paramref name=\"destPoints\" /> 定义的平行四边形的矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 指定要应用于路径的几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | 指定此扭曲操作使用透视模式还是双线性模式的 [WarpMode](/psd/python-net/aspose.psd/warpmode/) 枚举。 |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

对该 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 应用由矩形和平行四边形定义的扭曲变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 一个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组，定义将由 <paramref name=\"srcRect\" /> 定义的矩形转换为的平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示被转换为由 <paramref name=\"destPoints\" /> 定义的平行四边形的矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 指定要应用于路径的几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | 指定此扭曲操作使用透视模式还是双线性模式的 [WarpMode](/psd/python-net/aspose.psd/warpmode/) 枚举。 |
| flatness | float | 一个介于 0 到 1 之间的值，指定结果路径的平坦程度。更多信息请参阅 [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) 方法。 |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

为路径添加额外的轮廓。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 指定路径原始轮廓与此方法创建的新轮廓之间宽度的 [Pen](/psd/python-net/aspose.psd/pen/)。 |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

为 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 添加额外的轮廓。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 指定路径原始轮廓与此方法创建的新轮廓之间宽度的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 指定在加宽之前要应用于路径的变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

使用在使用指定笔绘制此路径时填充的区域所包围的曲线替换此 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 指定路径原始轮廓与此方法创建的新轮廓之间宽度的 [Pen](/psd/python-net/aspose.psd/pen/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 指定在加宽之前要应用于路径的变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| 平整度 | float | 指定曲线平滑度的值。 |


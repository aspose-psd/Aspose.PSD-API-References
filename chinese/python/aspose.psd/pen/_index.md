---
title: "Pen 类"
type: docs
weight: 3360
url: /zh/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | 使用指定的 [Pen.brush](/psd/python-net/aspose.psd/pen/) 初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。 |
| [Pen(brush, width)](#Pen_brush_width_2) | 使用指定的 [Pen.brush](/psd/python-net/aspose.psd/pen/) 和 [Pen.width](/psd/python-net/aspose.psd/pen/) 初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。 |
| [Pen(color)](#Pen_color_3) | 使用指定的颜色初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。 |
| [Pen(color, width)](#Pen_color_width_4) | 使用指定的 [Pen.color](/psd/python-net/aspose.psd/pen/) 和 [Pen.width](/psd/python-net/aspose.psd/pen/) 属性初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | 获取或设置此 [Pen](/psd/python-net/aspose.psd/pen/) 的对齐方式。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | 获取或设置决定此 [Pen](/psd/python-net/aspose.psd/pen/) 属性的 [Pen.brush](/psd/python-net/aspose.psd/pen/)。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置此 [Pen](/psd/python-net/aspose.psd/pen/) 的颜色。 |
| compound_array | float | 读/写 | 获取或设置指定复合笔的值数组。复合笔绘制由平行线段和间隔组成的复合线。 |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | 获取或设置在使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段末端使用的自定义帽。 |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | 获取或设置在使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段起始端使用的自定义帽。 |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | 获取或设置用于此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的虚线段末端的帽样式。 |
| dash_offset | float | 读/写 | 获取或设置从线段起点到虚线模式起始位置的距离。 |
| dash_pattern | float | 读/写 | 获取或设置自定义虚线和空格的数组。 |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | 获取或设置使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的虚线的样式。 |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | 获取或设置使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段末端使用的帽子样式。 |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | 获取或设置使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的两条连续线段端点的连接样式。 |
| miter_limit | float | 读/写 | 获取或设置斜接拐角处连接处厚度的限制。 |
| opacity | float | 读/写 | 获取或设置对象的不透明度。该值应在 0 到 1 之间。0 表示对象完全可见，1 表示对象完全不透明。 |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | 获取使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线条的样式。 |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | 获取或设置使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段起始端使用的帽子样式。 |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | 获取或设置此 [Pen](/psd/python-net/aspose.psd/pen/) 的几何变换的副本。 |
| width | float | r/w | 获取或设置此 [Pen](/psd/python-net/aspose.psd/pen/) 的宽度，单位为用于绘图的 Graphics 对象的单位。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | 将此 [Pen](/psd/python-net/aspose.psd/pen/) 的变换矩阵乘以指定的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | 按照指定顺序，将此 [Pen](/psd/python-net/aspose.psd/pen/) 的变换矩阵乘以指定的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| reset_transform() | 将此 [Pen](/psd/python-net/aspose.psd/pen/) 的几何变换矩阵重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_3) | 按指定角度旋转局部几何变换。此方法将在变换前置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | 按指定顺序，以指定角度旋转局部几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | 按指定因子缩放局部几何变换。此方法将在变换前置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | 按指定顺序，以指定因子缩放局部几何变换。 |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | 设置决定此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段结束时使用的帽子样式的值。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | 按指定尺寸平移局部几何变换。此方法将在变换前置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | 按指定顺序，以指定尺寸平移局部几何变换。 |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

使用指定的 [Pen.brush](/psd/python-net/aspose.psd/pen/) 初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 一个决定此 [Pen](/psd/python-net/aspose.psd/pen/) 填充属性的 [Pen.brush](/psd/python-net/aspose.psd/pen/)。 |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

使用指定的 [Pen.brush](/psd/python-net/aspose.psd/pen/) 和 [Pen.width](/psd/python-net/aspose.psd/pen/) 初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 一个决定此 [Pen](/psd/python-net/aspose.psd/pen/) 特性的 [Pen.brush](/psd/python-net/aspose.psd/pen/)。 |
| width | float | 新 [Pen](/psd/python-net/aspose.psd/pen/) 的宽度。 |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

使用指定的颜色初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 一个指示此 [Pen](/psd/python-net/aspose.psd/pen/) 颜色的 [Pen.color](/psd/python-net/aspose.psd/pen/) 结构。 |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

使用指定的 [Pen.color](/psd/python-net/aspose.psd/pen/) 和 [Pen.width](/psd/python-net/aspose.psd/pen/) 属性初始化 [Pen](/psd/python-net/aspose.psd/pen/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 一个指示此 [Pen](/psd/python-net/aspose.psd/pen/) 颜色的 [Pen.color](/psd/python-net/aspose.psd/pen/) 结构。 |
| width | float | 一个指示此 [Pen](/psd/python-net/aspose.psd/pen/) 宽度的值。 |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

将此 [Pen](/psd/python-net/aspose.psd/pen/) 的变换矩阵乘以指定的 [Matrix](/psd/python-net/aspose.psd/matrix/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以变换矩阵的 [Matrix](/psd/python-net/aspose.psd/matrix/) 对象。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

按照指定顺序，将此 [Pen](/psd/python-net/aspose.psd/pen/) 的变换矩阵乘以指定的 [Matrix](/psd/python-net/aspose.psd/matrix/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以变换矩阵的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 执行乘法操作的顺序。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

按指定角度旋转局部几何变换。此方法将在变换前置旋转。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

按指定顺序，以指定角度旋转局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置旋转矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

按指定因子缩放局部几何变换。此方法将在变换前置缩放矩阵。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

按指定顺序，以指定因子缩放局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置缩放矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

设置决定此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段结束时使用的帽子样式的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 一个表示使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段起始端的帽子样式的 [LineCap](/psd/python-net/aspose.psd/linecap/)。 |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 一个表示使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的线段结束端的帽子样式的 [LineCap](/psd/python-net/aspose.psd/linecap/)。 |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | 一个表示使用此 [Pen](/psd/python-net/aspose.psd/pen/) 绘制的虚线起始或结束端的帽子样式的 [LineCap](/psd/python-net/aspose.psd/linecap/)。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

按指定尺寸平移局部几何变换。此方法将在变换前置平移。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

按指定顺序，以指定尺寸平移局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 应用平移的顺序（前置或后置）。 |


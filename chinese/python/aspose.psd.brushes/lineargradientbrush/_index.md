---
title: "LinearGradientBrush 类"
type: docs
weight: 20
url: /zh/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | 初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类，使用默认参数。<br/> 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | 初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，使用指定的点和颜色。 |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | 初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，使用指定的点和颜色。 |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | 初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。 |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | 初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。 |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | 初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。 |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | 初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 角度 | float | 读/写 | 获取或设置渐变角度。 |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | 获取或设置一个 [Blend](/psd/python-net/aspose.psd/blend/) ，指定梯度自定义衰减的定位点和因子。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置结束的梯度颜色。 |
| gamma_correction | bool | r/w | 获取或设置一个值，指示是否为此 [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) 启用了伽马校正。 |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | 获取或设置一个定义多色线性渐变的 [ColorBlend](/psd/python-net/aspose.psd/colorblend/)。 |
| is_angle_scalable | bool | r/w | 获取或设置一个值，指示在使用此 [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) 进行变换时，[LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) 是否被更改。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如，设置变换矩阵或<br/> 调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 引入。 |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | 获取或设置梯度的起始和结束颜色。 |
| opacity | float | 读/写 | 获取或设置画笔不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | 获取或设置定义渐变起始点和结束点的矩形区域。 |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置起始的梯度颜色。 |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | 获取或设置一个复制的 [Matrix](/psd/python-net/aspose.psd/matrix/) ，它定义此 [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) 的局部几何变换。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | 获取或设置一个指示此 [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) 包装模式的 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 枚举。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 创建当前 [Brush](/psd/python-net/aspose.psd/brush/) 的深度克隆副本。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | 将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘，方法是将指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 前置。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | 将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_4) | 按指定的量旋转局部几何变换。此方法将在变换前置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | 按指定的量并按照指定顺序旋转局部几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | 按指定的比例缩放局部几何变换。此方法将在变换前置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | 按指定的比例并按照指定顺序缩放局部几何变换。 |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | 创建一个线性渐变，中心颜色为指定颜色，两端线性衰减到单一颜色。 |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | 创建一个线性渐变，中心颜色为指定颜色，两端线性衰减到单一颜色。 |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | 创建基于钟形曲线的渐变衰减。 |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | 创建基于钟形曲线的渐变衰减。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | 按指定的尺寸平移局部几何变换。此方法将在变换前置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | 按指定的尺寸并按照指定顺序平移局部几何变换。 |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类，使用默认参数。<br/> 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，使用指定的点和颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | 表示线性渐变起始点的 [Point](/psd/python-net/aspose.psd/point/) 结构。 |
| point2 | [Point](/psd/python-net/aspose.psd/point) | 表示线性渐变终止点的 [Point](/psd/python-net/aspose.psd/point/) 结构。 |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示线性渐变的起始颜色。 |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示线性渐变的结束颜色。 |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，使用指定的点和颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | 表示线性渐变起始点的 [Point](/psd/python-net/aspose.psd/point/) 结构。 |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | 表示线性渐变终止点的 [Point](/psd/python-net/aspose.psd/point/) 结构。 |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示线性渐变的起始颜色。 |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示线性渐变的结束颜色。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 指定线性渐变边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示梯度的起始颜色。 |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 用于表示渐变结束颜色的 [Color](/psd/python-net/aspose.psd/color/) 结构。 |
| 角度 | float | 渐变方向线相对于 x 轴顺时针测量的角度（单位为度）。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 指定线性渐变边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示梯度的起始颜色。 |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 用于表示渐变结束颜色的 [Color](/psd/python-net/aspose.psd/color/) 结构。 |
| 角度 | float | 渐变方向线相对于 x 轴顺时针测量的角度（单位为度）。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 指定线性渐变边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示梯度的起始颜色。 |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 用于表示渐变结束颜色的 [Color](/psd/python-net/aspose.psd/color/) 结构。 |
| 角度 | float | 渐变方向线相对于 x 轴顺时针测量的角度（单位为度）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，在使用此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 进行变换时角度会被改变。 |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

初始化 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 类的新实例，基于矩形、起始和结束颜色以及方向角度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 指定线性渐变边界的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 一个 [Color](/psd/python-net/aspose.psd/color/) 结构，表示梯度的起始颜色。 |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 用于表示渐变结束颜色的 [Color](/psd/python-net/aspose.psd/color/) 结构。 |
| 角度 | float | 渐变方向线相对于 x 轴顺时针测量的角度（单位为度）。 |
| is_angle_scalable | bool | 如果设置为 <c>true</c>，在使用此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 进行变换时角度会被改变。 |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

创建当前 [Brush](/psd/python-net/aspose.psd/brush/) 的深度克隆副本。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | 一个新的 [Brush](/psd/python-net/aspose.psd/brush/)，它是此 [Brush](/psd/python-net/aspose.psd/brush/) 实例的深度克隆。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘，方法是将指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 前置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 按指定顺序相乘。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定两个矩阵相乘顺序的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

按指定的量旋转局部几何变换。此方法将在变换前置旋转。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

按指定的量并按照指定顺序旋转局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置旋转矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放局部几何变换。此方法将在变换前置缩放矩阵。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

按指定的比例并按照指定顺序缩放局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置缩放矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

创建一个线性渐变，中心颜色为指定颜色，两端线性衰减到单一颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即渐变仅由结束颜色组成的点）。 |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

创建一个线性渐变，中心颜色为指定颜色，两端线性衰减到单一颜色。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即渐变仅由结束颜色组成的点）。 |
| scale | float | 一个取值范围为 0 到 1 的值，用于指定颜色从起始颜色到 <paramref name="focus" />（结束颜色）的衰减速度。 |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

创建基于钟形曲线的渐变衰减。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即起始颜色和结束颜色等量混合的点）。 |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

创建基于钟形曲线的渐变衰减。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定渐变的中心（即渐变仅由结束颜色组成的点）。 |
| scale | float | 一个取值范围为 0 到 1 的值，用于指定颜色从 <paramref name="focus" /> 衰减的速度。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移局部几何变换。此方法将在变换前置平移。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

按指定的尺寸并按照指定顺序平移局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 应用平移的顺序（前置或后置）。 |


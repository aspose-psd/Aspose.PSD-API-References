---
title: "PathGradientBrush 类"
type: docs
weight: 50
url: /zh/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | 使用指定的路径初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。 |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | 使用指定的点初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。 |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | 使用指定的点初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。 |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | 使用指定的点和包装模式初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。 |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | 使用指定的点和包装模式初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | 获取或设置一个 [Blend](/psd/python-net/aspose.psd/blend/) ，指定梯度自定义衰减的定位点和因子。 |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置路径渐变中心的颜色。 |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | 获取或设置路径渐变的中心点。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | 获取或设置渐变衰减的焦点。 |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | 获取此画刷所基于的图形路径。 |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | 获取或设置一个定义多色线性渐变的 [ColorBlend](/psd/python-net/aspose.psd/colorblend/)。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如，设置变换矩阵或<br/> 调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 引入。 |
| opacity | float | 读/写 | 获取或设置画笔不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | 获取此画刷所基于的路径点。 |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | 获取或设置一个颜色数组，该数组对应此 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 填充的路径中的点。 |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | 创建一个以中心颜色为起点、线性衰减至一种周围颜色的渐变。 |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | 创建一个以中心颜色为起点、线性衰减至每种周围颜色的渐变。 |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | 创建一种渐变画刷，从路径中心向外至路径边界改变颜色。颜色之间的过渡基于钟形曲线。 |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | 创建一种渐变画刷，从路径中心向外至路径边界改变颜色。颜色之间的过渡基于钟形曲线。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | 按指定的尺寸平移局部几何变换。此方法将在变换前置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | 按指定的尺寸并按照指定顺序平移局部几何变换。 |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

使用指定的路径初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 定义此 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 所填充区域的 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

使用指定的点初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示构成路径顶点的点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

使用指定的点初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示构成路径顶点的点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

使用指定的点和包装模式初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 表示构成路径顶点的点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 一个指定使用此 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 绘制的填充如何平铺的 [WrapMode](/psd/python-net/aspose.psd/wrapmode/)。 |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

使用指定的点和包装模式初始化 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | 表示构成路径顶点的点的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构数组。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 一个指定使用此 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 绘制的填充如何平铺的 [WrapMode](/psd/python-net/aspose.psd/wrapmode/)。 |

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

创建一个以中心颜色为起点、线性衰减至一种周围颜色的渐变。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

创建一个以中心颜色为起点、线性衰减至每种周围颜色的渐变。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |
| scale | float | 一个取值范围为 0 到 1 的值，用于指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

创建一种渐变画刷，从路径中心向外至路径边界改变颜色。颜色之间的过渡基于钟形曲线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

创建一种渐变画刷，从路径中心向外至路径边界改变颜色。颜色之间的过渡基于钟形曲线。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 焦点 | float | 一个取值范围为 0 到 1 的值，用于指定沿从路径中心到路径边界的任意径向，中心颜色达到最高强度的位置。值为 1（默认）时，最高强度位于路径中心。 |
| scale | float | 一个取值范围为 0 到 1 的值，用于指定中心颜色与边界颜色混合时的最大强度。值为 1 时会产生中心颜色的最高可能强度，这是默认值。 |

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


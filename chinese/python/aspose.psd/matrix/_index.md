---
title: "Matrix 类"
type: docs
weight: 3000
url: /zh/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Matrix()](#Matrix__1) | 将 Matrix 类初始化为单位矩阵的新实例。 |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | 将 [Matrix](/psd/python-net/aspose.psd/matrix/) 类初始化为新实例。 |
| [Matrix(origin)](#Matrix_origin_3) | 创建 [Matrix](/psd/python-net/aspose.psd/matrix/) 类的副本。 |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | 将 [Matrix](/psd/python-net/aspose.psd/matrix/) 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | 将 [Matrix](/psd/python-net/aspose.psd/matrix/) 类初始化为由指定矩形和点数组定义的几何变换的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | 此标志位表示此对象定义的变换<br/>            执行关于某轴的镜像翻转，这会将通常的右手坐标系转换为左手坐标系<br/>            并且还会执行其他标志位指示的转换。<br/>            右手坐标系是指正 X 轴逆时针旋转以覆盖正 Y 轴，<br/>            类似于当你正面对拇指时右手手指的卷曲方向。<br/>            左手坐标系是指正 X 轴顺时针旋转以覆盖正 Y 轴，<br/>            类似于左手手指的卷曲方向。<br/>            没有数学方法可以确定原始翻转或镜像变换的角度，因为在适当的调整旋转下，所有翻转角度都是相同的。<br/>            注意：TypeFlip 是在 GENERAL_TRANSFORM 已公开流通后添加的，<br/>            因此无法方便地重新编号标志位而不在外部代码中引入二进制不兼容。 |
| TYPE_GENERAL_ROTATION [static] | int | r | 此标志位表示此对象定义的变换<br/>            执行任意角度的旋转，并且还会执行其他标志位指示的转换。<br/>            旋转会以相同的量改变向量的角度，<br/>            与向量的原始方向无关且不改变向量的长度。<br/>            此标志位与 |
| TYPE_GENERAL_SCALE [static] | int | r | 通用缩放会在 x 和 y 方向上以不同的量乘以向量的长度，<br/>            且不改变垂直向量之间的角度。<br/>            此标志位与 TypeUniformScale 标志互斥。 |
| TYPE_GENERAL_TRANSFORM [static] | int | r | 此常量表示此对象定义的变换<br/>            对输入坐标执行任意转换。<br/>            如果此变换可以由上述任意常量分类，<br/>            类型将是常量 TypeIdentity，或是针对该变换执行的各种坐标转换的相应标志位的组合。 |
| TYPE_IDENTITY [static] | int | r | 恒等变换是指输出坐标始终与输入坐标相同的变换。<br/>            如果此变换不是恒等变换，<br/>            类型将是常量 GENERAL_TRANSFORM，或是针对该变换执行的各种坐标转换的相应标志位的组合。 |
| TYPE_MASK_ROTATION [static] | int | r | 此常量是用于任意旋转标志位的位掩码。 |
| TYPE_MASK_SCALE [static] | int | r | 此常量是用于任意缩放标志位的位掩码。 |
| TYPE_QUADRANT_ROTATION [static] | int | r | 此标志位表示此对象定义的变换<br/>            执行以 90 度的倍数为单位的象限旋转，并且还会执行其他标志位指示的转换。<br/>            旋转会以相同的量改变向量的角度，<br/>            与向量的原始方向无关且不改变向量的长度。<br/>            此标志位与 TypeGeneralRotation 标志互斥。 |
| TYPE_TRANSLATION [static] | int | r | 平移会在 x 和 y 方向上以恒定量移动坐标，且不改变向量的长度或角度。 |
| TYPE_UNIFORM_SCALE [static] | int | r | 统一缩放会在 x 和 y 方向上以相同的量乘以向量的长度，且不改变向量之间的角度。\n            此标志位与 TypeGeneralScale 标志互斥。 |
| elements | float | r | 获取一个浮点数数组，表示此 [Matrix](/psd/python-net/aspose.psd/matrix/) 的元素。 |
| m11 | float | r | 获取矩阵第一行第一列的元素。表示沿 X 轴的缩放。 |
| m12 | float | r | 获取矩阵第一行第二列的元素。表示沿 Y 轴的剪切。 |
| m21 | float | r | 获取矩阵第二行第一列的元素。表示沿 X 轴的剪切。 |
| m22 | float | r | 获取矩阵第二行第二列的元素。表示沿 Y 轴的缩放。 |
| m31 | float | r | 获取矩阵第三行第一列的元素。表示沿 X 轴的平移。 |
| m32 | float | r | 获取矩阵第三行第一列的元素。表示沿 Y 轴的平移。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_elements()](#get_elements__1) | 获取矩阵元素的副本。 |
| [multiply(tx)](#multiply_tx_2) | 使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。 |
| [multiply(tx, order)](#multiply_tx_order_3) | 将此 Matrix 与 matrix 参数中指定的矩阵相乘，并使用 order 参数中指定的顺序。 |
| reset() | 将此 Matrix 重置为单位矩阵的元素。 |
| [rotate(angle)](#rotate_angle_4) | 在默认（Prepend）顺序下，对此 Matrix 应用以 angle 参数指定的角度的顺时针旋转，围绕原点（零 x 和 y 坐标）。 |
| [rotate(angle, order)](#rotate_angle_order_5) | 在指定的顺序下，对此 Matrix 应用以 angle 参数指定的角度的顺时针旋转，围绕原点（零 x 和 y 坐标）。 |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | 在默认（Prepend）顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。 |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | 在指定的顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。 |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | 使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| [scale(sx, sy)](#scale_sx_sy_9) | 使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。 |
| [transform_points(points)](#transform_points_points_10) | 将此 [Matrix](/psd/python-net/aspose.psd/matrix/) 所表示的几何变换应用于指定的点数组。 |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | 在指定的顺序下，将指定的平移向量应用于此 Matrix。 |
| [translate(tx, ty)](#translate_tx_ty_12) | 使用（默认）Prepend 顺序，将指定的平移向量应用于此 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

将 Matrix 类初始化为单位矩阵的新实例。

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

将 [Matrix](/psd/python-net/aspose.psd/matrix/) 类初始化为新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| m11 | float | m00     M11     缩放 X |
| m12 | float | m10     M12     剪切 Y |
| m21 | float | m01     M21     剪切 X |
| m22 | float | m11     M22     缩放 Y |
| m31 | float | m02     M31     平移 X |
| m32 | float | m12     M32     平移 Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

创建 [Matrix](/psd/python-net/aspose.psd/matrix/) 类的副本。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于复制的基础矩阵 |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

将 [Matrix](/psd/python-net/aspose.psd/matrix/) 类初始化为由指定矩形和点数组定义的几何变换的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 一个表示要变换的矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | 一个包含三个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的点。平行四边形的右下角由前三个角暗示。 |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

将 [Matrix](/psd/python-net/aspose.psd/matrix/) 类初始化为由指定矩形和点数组定义的几何变换的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 一个表示要变换的矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | 一个包含三个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构的数组，表示要将矩形的左上、右上和左下角变换到的平行四边形的点。平行四边形的右下角由前三个角暗示。 |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

获取矩阵元素的副本。

**Returns**

| 类型 | 描述 |
| :- | :- |
| float | 矩阵元素的副本。 |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于相乘的矩阵。 |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

将此 Matrix 与 matrix 参数中指定的矩阵相乘，并使用 order 参数中指定的顺序。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | 该 tx. 该 tx. 该 tx. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 该顺序. 该顺序. 该顺序. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

在默认（Prepend）顺序下，对此 Matrix 应用以 angle 参数指定的角度的顺时针旋转，围绕原点（零 x 和 y 坐标）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 该旋转角度。 |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

在指定的顺序下，对此 Matrix 应用以 angle 参数指定的角度的顺时针旋转，围绕原点（零 x 和 y 坐标）。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 该旋转角度。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 该矩阵顺序。 |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

在默认（Prepend）顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 该角度。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 该点。 |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

在指定的顺序下，对此 Matrix 应用围绕指定点的顺时针旋转。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 该角度。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 该点。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 该顺序。 |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 [Matrix](/psd/python-net/aspose.psd/matrix/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scale_x | float | 该 X 缩放。 |
| scale_y | float | 该 Y 缩放。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 该顺序。 |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 该 sx. 该 sx. 该 sx. |
| sy | float | 该 sy. 该 sy. 该 sy。 |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

将此 [Matrix](/psd/python-net/aspose.psd/matrix/) 所表示的几何变换应用于指定的点数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 这些点。 |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

在指定的顺序下，将指定的平移向量应用于此 Matrix。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| offset_x | float | 该 X 偏移。 |
| offset_y | float | 该 Y 偏移。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 该顺序。 |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

使用（默认）Prepend 顺序，将指定的平移向量应用于此 [Matrix](/psd/python-net/aspose.psd/matrix/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tx | float | 该 tx. 该 tx. 该 tx. |
| ty | float | 该 ty. 该 ty. 该 ty。 |


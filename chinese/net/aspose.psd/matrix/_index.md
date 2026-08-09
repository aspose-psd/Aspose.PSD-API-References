---
title: "类 Matrix"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Matrix 类。取代 GDI Matrix"
type: docs
weight: 5580
url: /zh/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

替换 GDI+ 矩阵。

```csharp
public class Matrix
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Matrix](matrix/#constructor)() | 将 Matrix 类的新实例初始化为单位矩阵。 |
| [Matrix](matrix/#constructor_1)(Matrix) | 创建 `Matrix` 类的副本。 |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | 将 `Matrix` 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | 将 `Matrix` 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | 将 `Matrix` 类的新实例初始化。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | 获取一个浮点值数组，表示此 `Matrix` 的元素。 |
| [M11](../../aspose.psd/matrix/m11/) { get; } | 获取第一行第一列的矩阵元素。表示沿 X 轴的缩放。 |
| [M12](../../aspose.psd/matrix/m12/) { get; } | 获取第一行第二列的矩阵元素。表示沿 Y 轴的剪切。 |
| [M21](../../aspose.psd/matrix/m21/) { get; } | 获取第二行第一列的矩阵元素。表示沿 X 轴的剪切。 |
| [M22](../../aspose.psd/matrix/m22/) { get; } | 获取第二行第二列的矩阵元素。表示沿 Y 轴的缩放。 |
| [M31](../../aspose.psd/matrix/m31/) { get; } | 获取第三行第一列的矩阵元素。表示沿 X 轴的平移。 |
| [M32](../../aspose.psd/matrix/m32/) { get; } | 获取第三行第一列的矩阵元素。表示沿 Y 轴的平移。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | 确定指定的对象是否等于此实例。 |
| [GetElements](../../aspose.psd/matrix/getelements/)() | 获取矩阵元素的副本。 |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | 返回此实例的哈希码。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | 使用（默认）前置顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | 将此 Matrix 与 matrix 参数中指定的矩阵相乘，并按照 order 参数中指定的顺序进行。 |
| [Reset](../../aspose.psd/matrix/reset/)() | 将此 Matrix 重置为具有单位矩阵的元素。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | 对该 Matrix 按默认（Prepend）顺序，在原点（零 x 和 y 坐标）周围应用角度参数指定的顺时针旋转。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | 对该 Matrix 按指定顺序，在原点（零 x 和 y 坐标）周围应用角度参数指定的顺时针旋转。 |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | 对该 Matrix 按默认（Prepend）顺序，围绕指定点应用顺时针旋转。 |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | 对该 Matrix 按指定顺序，围绕指定点应用顺时针旋转。 |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | 使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用于该 Matrix。 |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | 使用指定顺序，将指定的缩放向量（scaleX 和 scaleY）应用于该 `Matrix`。 |
| override [ToString](../../aspose.psd/matrix/tostring/)() | 返回一个表示此实例的字符串。 |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | 将此 `Matrix` 表示的几何变换应用于指定的点数组。 |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | 使用（默认）Prepend 顺序，将指定的平移向量应用于该 `Matrix`。 |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | 按指定顺序，将指定的平移向量应用于该 Matrix。 |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | 确定两个矩阵是否相等。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | 此标志位表示，由此对象定义的变换在执行其他标志位指示的转换之外，还会围绕某一轴进行镜像翻转，从而将通常的右手坐标系转换为左手坐标系。右手坐标系是指正 X 轴逆时针旋转以覆盖正 Y 轴，类似于当你正面对拇指时右手手指的卷曲方向。左手坐标系是指正 X 轴顺时针旋转以覆盖正 Y 轴，类似于左手手指的卷曲方向。由于在适当的调整旋转下所有翻转角度相同，无法通过数学方法确定原始翻转或镜像变换的角度。注意：TypeFlip 是在 GENERAL_TRANSFORM 已公开流通后添加的，标志位已无法方便地重新编号，否则会在外部代码中引入二进制不兼容性。 |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | 此标志位表示，由此对象定义的变换在执行其他标志位指示的转换之外，还会进行任意角度的旋转。旋转会在不改变向量长度的前提下，使向量的角度统一改变相同的量，无论向量的原始方向如何。此标志位与 |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | 一般缩放会在 x 和 y 方向上以不同的比例乘以向量的长度，而不改变垂直向量之间的角度。此标志位与 TypeUniformScale 标志互斥。 |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | 此常量表示，由此对象定义的变换对输入坐标执行任意转换。如果此变换可以归类于上述任意常量，则其类型将是常量 TypeIdentity，或是对应于该变换执行的各种坐标转换的适当标志位的组合。 |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | 恒等变换是指输出坐标始终与输入坐标相同的变换。如果此变换不是恒等变换，则其类型将是常量 GENERAL_TRANSFORM，或是对应于该变换执行的各种坐标转换的适当标志位的组合。 |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | 此常量是用于任意旋转标志位的位掩码。 |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | 此常量是用于任意缩放标志位的位掩码。 |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | 此标志位表示，由此对象定义的变换在执行其他标志位指示的转换之外，还会进行以 90 度的若干倍为单位的象限旋转。旋转会在不改变向量长度的前提下，使向量的角度统一改变相同的量，无论向量的原始方向如何。此标志位与 TypeGeneralRotation 标志互斥。 |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | 平移会在 x 和 y 方向上以恒定量移动坐标，而不改变向量的长度或角度。 |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | 统一缩放会在 x 和 y 方向上以相同的比例乘以向量的长度，而不改变向量之间的角度。此标志位与 TypeGeneralScale 标志互斥。 |

## 备注

大多数算法取自 Sun 的 AffineTransform.java。Java 用于内部的矩阵元素名称。Java 名称到 .net 名称的映射及说明：m00 M11 缩放 X m10 M12 剪切 Y m01 M21 剪切 X m11 M22 缩放 Y m02 M31 平移 X m12 M32 平移 Y

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)



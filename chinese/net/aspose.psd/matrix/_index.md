---
title: Class Matrix
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Matrix 班级. 替换 GDI 矩阵
type: docs
weight: 5090
url: /zh/net/aspose.psd/matrix/
---
## Matrix class

替换 GDI+ 矩阵。

```csharp
public class Matrix
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Matrix](matrix/#constructor)() | 将 Matrix 类的新实例初始化为单位矩阵。 |
| [Matrix](matrix/#constructor_1)(Matrix) | 复制`Matrix`类. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | 初始化一个新的实例`Matrix`类到由指定矩形和点数组定义的几何变换。 |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | 初始化一个新的实例`Matrix`类到由指定矩形和点数组定义的几何变换。 |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | 初始化一个新的实例`Matrix`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | 获取表示此元素的浮点值数组`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | 获取第一行第一列的矩阵元素。表示沿 X 轴的比例。 |
| [M12](../../aspose.psd/matrix/m12/) { get; } | 获取第一行第二列的矩阵元素。表示沿 Y 轴的剪切。 |
| [M21](../../aspose.psd/matrix/m21/) { get; } | 获取第二行第一列的矩阵元素。表示沿 X 轴的剪切。 |
| [M22](../../aspose.psd/matrix/m22/) { get; } | 获取第二行第二列的矩阵元素。表示沿 Y 轴的比例。 |
| [M31](../../aspose.psd/matrix/m31/) { get; } | 获取第三行第一列的矩阵元素。表示沿 X 轴平移. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | 获取第三行第一列的矩阵元素。表示沿Y轴平移. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | 判断指定的是否Object等于这个实例. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | 获取矩阵元素的副本。 |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | 返回此实例的哈希码。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | 使用（默认）前置顺序将此矩阵乘以矩阵参数中指定的矩阵。 |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | 将此 Matrix 乘以 matrix 参数中指定的矩阵，并按照 order 参数中指定的顺序。 |
| [Reset](../../aspose.psd/matrix/reset/)() | 重置此矩阵以具有单位矩阵的元素。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | 以默认（前置）顺序围绕此矩阵的原点（零 x 和 y 坐标）应用角度参数中指定的量的顺时针旋转。 |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | 以指定顺序围绕此矩阵的原点（零 x 和 y 坐标）应用角度参数中指定量的顺时针旋转。 |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | 以默认（前置）顺序将指定点的顺时针旋转应用于此矩阵。 |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | 以指定顺序将指定点的顺时针旋转应用到此矩阵。 |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | 使用（默认）前置顺序将指定的比例向量（scaleX 和 scaleY）应用于此矩阵。 |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | 将指定的比例矢量（scaleX 和 scaleY）应用于此`Matrix`使用指定的顺序. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | 返回一个String代表这个实例. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | 应用由此表示的几何变换`Matrix`到指定的点数组。 |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | 将指定的翻译向量应用于此`Matrix`使用（默认）前置顺序. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | 按指定顺序将指定的平移向量应用于此矩阵。 |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | 判断两个矩阵是否相等。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | 此标志位表示此对象 定义的变换执行围绕某个轴的镜像翻转，除了其他标志位指示的转换之外， 通常右手坐标系变为左手 系统。 右手坐标系是一个正 X 轴逆时针旋转以覆盖正 Y 轴 的方向，类似于当你盯着你的拇指时右手的手指 卷曲的方向。 左手坐标系是一个正 X 轴旋转的坐标系顺时针方向叠加正 Y 轴，与左手手指卷曲的方向相似 。没有数学方法可以确定原始翻转或镜像变换的角度，因为在适当调整旋转的情况下，翻转的所有角度 都是相同的。 注意：在 GENERAL_TRANSFORM 之后添加了 TypeFlip在 public 流通中，如果不在 outside 代码中引入二进制不兼容，标志位将无法再方便地 重新编号。 |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | 此标志位表示此对象 定义的变换除了由其他标志位指示的 转换之外还执行任意角度的旋转。 旋转将矢量的角度更改相同的量 而不管矢量的原始方向如何and without changing the length of vector. 这个标志位与 互斥 |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | 通用尺度将向量的长度乘以 x 和 y 方向上不同的 量，而不改变垂直向量之间的角度 。 此标志位与 TypeUniformScale 标志互斥。 |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | 此常量表示此对象 定义的变换执行输入坐标的任意转换。 如果此变换可以按上述任何常量分类， 类型将为常量 TypeIdentity 或 a 适当标志的组合此转换执行的各种 coordinate 转换的位。 |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | 恒等变换是输出坐标 始终与输入坐标相同的变换。 如果此变换不是恒等变换， 类型将是常量 GENERAL_TRANSFORM 或 a 适当标志位的组合此转换执行的各种 coordinate 转换。 |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | 此常量是任何旋转标志位的位掩码。 |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | 此常量是任何标度标志位的位掩码。 |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | 此标志位表示此对象 定义的变换执行象限旋转 90 度的某个倍数 in 除了其他标志位指示的转换。 旋转将矢量的角度改变相同的量 而不管原始方向如何向量的长度并且没有 改变向量的长度。 这个标志位与TypeGeneralRotation标志互斥。 |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | 翻译将坐标在 x 和 y 中移动一个常数，而不改变矢量的长度或角度。 |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | 统一比例在 x 和 y 方向上将向量的长度乘以相同的量 ，而不改变 向量之间的角度。 此标志位与 TypeGeneralScale 标志互斥。 |

### 评论

大多数算法取自 Sun 的 AffineTransform.java。 Java 内部使用的矩阵元素的名称。 java 名称到 .net 的映射到描述： m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 Y_00 Scale翻译 X m12 M32 翻译 Y

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)



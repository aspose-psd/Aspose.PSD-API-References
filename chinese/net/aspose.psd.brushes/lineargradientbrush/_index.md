---
title: LinearGradientBrush
second_title: Aspose.PSD for .NET API 参考
description: 用线性渐变封装Brush../aspose.psd/brush这个类不能被继承
type: docs
weight: 140
url: /zh/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

用线性渐变封装[`Brush`](../../aspose.psd/brush)。这个类不能被继承。

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | 使用默认参数初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1)。 |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | 使用指定的点和颜色初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | 使用指定的点和颜色初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | 基于矩形、开始和结束颜色以及方向角度初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | 基于矩形、开始和结束颜色以及方向角度初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | 基于矩形、起始颜色和结束颜色以及方向角度初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | 基于矩形、起始颜色和结束颜色以及方向角度初始化[`LinearGradientBrush`](../lineargradientbrush)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle) { get; set; } | 获取或设置渐变角度。 |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend) { get; set; } | 获取或设置一个[`Blend`](../../aspose.psd/blend)，它指定定义渐变自定义衰减的位置和因子。 |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor) { get; set; } | 获取或设置结束渐变颜色。 |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | 获取或设置一个值，该值指示是否为此[`LinearGradientBrushBase`](../lineargradientbrushbase)启用伽马校正。 |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | 获取或设置一个值，该值指示[`Angle`](../lineargradientbrushbase/angle)在使用此LinearGradientBrushBase。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示是否以某种方式更改了转换。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+。 |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle) { get; set; } | 获取或设置定义渐变起点和终点的矩形区域。 |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor) { get; set; } | 获取或设置起始渐变颜色。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform) { get; set; } | 获取或设置一个副本[`Matrix`](../../aspose.psd/matrix)，它为此TransformBrush定义了一个局部几何变换。 |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode) { get; set; } | 获取或设置一个[`WrapMode`](../../aspose.psd/wrapmode)枚举，指示此[`TransformBrush`](../transformbrush) 的环绕模式. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | 创建当前[`Brush`](../../aspose.psd/brush)的新深层克隆。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 释放当前实例。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix) | 将表示此[`LinearGradientBrush`](../lineargradientbrush)的局部几何变换的[`Matrix`](../../aspose.psd/matrix)乘以指定的[`Matrix`](../../aspose.psd/matrix)前面加上指定的[`Matrix`](../../aspose.psd/matrix)。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | 将表示此[`LinearGradientBrush`](../lineargradientbrush)的局部几何变换的[`Matrix`](../../aspose.psd/matrix)乘以以指定顺序指定的[`Matrix`](../../aspose.psd/matrix)。 |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform)() | 将[`Transform`](../transformbrush/transform)属性重置为标识。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float) | 将局部几何变换旋转指定的量。此方法将旋转添加到变换中。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | 按指定顺序将局部几何变换旋转指定量。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到变换中。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | 按指定顺序按指定量缩放局部几何变换。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | 使用中心颜色和两端的单一颜色线性衰减创建线性渐变。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | 使用中心颜色和两端的单一颜色线性衰减创建线性渐变。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | 基于钟形曲线创建渐变衰减。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | 基于钟形曲线创建渐变衰减。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 按指定顺序按指定维度平移局部几何变换。 |

### 也可以看看

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

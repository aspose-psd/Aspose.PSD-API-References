---
title: Class LinearGradientBrush
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Brushes.LinearGradientBrush 班级. 封装了一个Brush具有线性渐变此类不能被继承
type: docs
weight: 140
url: /zh/net/aspose.psd.brushes/lineargradientbrush/
---
## LinearGradientBrush class

封装了一个[`Brush`](../../aspose.psd/brush/)具有线性渐变。此类不能被继承。

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush/#constructor)() | 初始化一个新的实例`LinearGradientBrush`具有默认参数的类。 起始颜色为黑色，结束颜色为白色，角度为 45 度，矩形位于 (0,0)，大小为 (1,1). |
| [LinearGradientBrush](lineargradientbrush/#constructor_1)(Point, Point, Color, Color) | 初始化一个新的实例`LinearGradientBrush`具有指定点和颜色的类。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_2)(PointF, PointF, Color, Color) | 初始化一个新的实例`LinearGradientBrush`具有指定点和颜色的类。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_3)(Rectangle, Color, Color, float) | 初始化一个新的实例`LinearGradientBrush`基于矩形、开始和结束颜色以及方向角的类。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_5)(RectangleF, Color, Color, float) | 初始化一个新的实例`LinearGradientBrush`基于矩形、开始和结束颜色以及方向角的类。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_4)(Rectangle, Color, Color, float, bool) | 初始化一个新的实例`LinearGradientBrush`基于矩形、开始和结束颜色以及方向角的类。 |
| [LinearGradientBrush](lineargradientbrush/#constructor_6)(RectangleF, Color, Color, float, bool) | 初始化一个新的实例`LinearGradientBrush`基于矩形、开始和结束颜色以及方向角的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | 获取或设置渐变角度。 |
| [Blend](../../aspose.psd.brushes/lineargradientbrush/blend/) { get; set; } | 获取或设置一个[`Blend`](../../aspose.psd/blend/)指定定义渐变自定义衰减的位置和因子。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，该值表示该实例是否被释放。 |
| [EndColor](../../aspose.psd.brushes/lineargradientbrush/endcolor/) { get; set; } | 获取或设置结束渐变色。 |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | 获取或设置一个值，指示是否为此启用伽玛校正[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | 获取或设置一个值指示是否[`Angle`](../lineargradientbrushbase/angle/)在转换过程中被更改[`LinearGradientBrushBase`](../lineargradientbrushbase/) . |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取指示转换是否以某种方式更改的值。例如设置转换矩阵或 调用任何改变转换矩阵的方法。引入该属性是为了向后兼容 GDI+. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值为 0 表示画笔完全可见，值为 1 表示画笔完全不透明。 |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | 获取或设置一个矩形区域，该区域定义渐变的起点和终点。 |
| [StartColor](../../aspose.psd.brushes/lineargradientbrush/startcolor/) { get; set; } | 获取或设置起始渐变色。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | 获取或设置副本[`Matrix`](../../aspose.psd/matrix/)为此定义了局部几何变换[`TransformBrush`](../transformbrush/) . |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | 获取或设置一个[`WrapMode`](../../aspose.psd/wrapmode/)指示此包装模式的枚举[`TransformBrush`](../transformbrush/) . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 创建当前的新深度克隆[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 处理当前实例。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | 乘以[`Matrix`](../../aspose.psd/matrix/)表示这个的局部几何变换`LinearGradientBrush`由指定的[`Matrix`](../../aspose.psd/matrix/)通过预先指定[`Matrix`](../../aspose.psd/matrix/) . |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 乘以[`Matrix`](../../aspose.psd/matrix/)表示这个的局部几何变换`LinearGradientBrush`由指定的[`Matrix`](../../aspose.psd/matrix/)按指定顺序. |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | 重置[`Transform`](../transformbrush/transform/)属性到身份. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 按指定量旋转局部几何变换。此方法将旋转添加到 transform. |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 按指定顺序按指定量旋转局部几何变换。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到 transform. |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 按指定顺序按指定数量缩放局部几何变换。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 创建一个线性渐变，中心颜色和线性衰减到两端的单一颜色。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/lineargradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 创建一个线性渐变，中心颜色和线性衰减到两端的单一颜色。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape)(float) | 基于钟形曲线创建渐变衰减。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/lineargradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | 基于钟形曲线创建渐变衰减。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 按指定尺寸平移局部几何变换。此方法将翻译添加到 transform. |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 按指定顺序按指定尺寸平移局部几何变换。 |

### 也可以看看

* class [LinearGradientBrushBase](../lineargradientbrushbase/)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* 部件 [Aspose.PSD](../../)



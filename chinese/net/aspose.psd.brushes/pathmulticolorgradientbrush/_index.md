---
title: PathMulticolorGradientBrush
second_title: Aspose.PSD for .NET API 参考
description: 用渐变封装Brush../aspose.psd/brush对象这个类不能被继承
type: docs
weight: 190
url: /zh/net/aspose.psd.brushes/pathmulticolorgradientbrush/
---
## PathMulticolorGradientBrush class

用渐变封装[`Brush`](../../aspose.psd/brush)对象。这个类不能被继承。

```csharp
public sealed class PathMulticolorGradientBrush : PathGradientBrushBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor)(GraphicsPath) | 使用指定路径初始化[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush)类的新实例。 |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_1)(PointF[]) | 使用指定点初始化[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush)类的新实例。 |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_3)(Point[]) | 使用指定的点初始化[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush)类的新实例。 |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_2)(PointF[], WrapMode) | 使用指定的点和环绕模式初始化[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush)类的新实例。 |
| [PathMulticolorGradientBrush](pathmulticolorgradientbrush#constructor_4)(Point[], WrapMode) | 使用指定的点和环绕模式初始化[`PathMulticolorGradientBrush`](../pathmulticolorgradientbrush)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath) { get; } | 获取此画笔所基于的图形路径。 |
| [InterpolationColors](../../aspose.psd.brushes/pathmulticolorgradientbrush/interpolationcolors) { get; set; } | 获取或设置定义多色线性渐变的[`ColorBlend`](../../aspose.psd/colorblend)。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示是否以某种方式更改了转换。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+。 |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints) { get; } | 获取此画笔所基于的路径点。 |
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
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | 按指定顺序按指定维度平移局部几何变换。 |

### 也可以看看

* class [PathGradientBrushBase](../pathgradientbrushbase)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

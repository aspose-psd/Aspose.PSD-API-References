---
title: TransformBrush
second_title: Aspose.PSD for .NET API 参考
description: Brush../aspose.psd/brush具有转换功能
type: docs
weight: 220
url: /zh/net/aspose.psd.brushes/transformbrush/
---
## TransformBrush class

[`Brush`](../../aspose.psd/brush)具有转换功能。

```csharp
public abstract class TransformBrush : Brush
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | 获取一个值，该值指示该实例是否被释放。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged) { get; } | 获取一个值，该值指示是否以某种方式更改了转换。例如设置变换矩阵或 调用任何改变变换矩阵的方法。引入该属性是为了向后兼容 GDI+。 |
| [Opacity](../../aspose.psd/brush/opacity) { get; set; } | 获取或设置画笔不透明度。该值应介于 0 和 1 之间。值 0 表示画笔完全可见，值 1 表示画笔完全不透明。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform) { get; set; } | 获取或设置一个副本[`Matrix`](../../aspose.psd/matrix)，它为此TransformBrush定义了一个局部几何变换。 |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode) { get; set; } | 获取或设置一个[`WrapMode`](../../aspose.psd/wrapmode)枚举，指示此[`TransformBrush`](../transformbrush) 的环绕模式. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone)() | 创建当前[`Brush`](../../aspose.psd/brush)的新深层克隆。 |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | 释放当前实例。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform#multiplytransform)(Matrix) | 将表示此[`LinearGradientBrush`](../lineargradientbrush)的局部几何变换的[`Matrix`](../../aspose.psd/matrix)乘以指定的[`Matrix`](../../aspose.psd/matrix)前面加上指定的[`Matrix`](../../aspose.psd/matrix)。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | 将表示此[`LinearGradientBrush`](../lineargradientbrush)的局部几何变换的[`Matrix`](../../aspose.psd/matrix)乘以以指定顺序指定的[`Matrix`](../../aspose.psd/matrix)。 |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform)() | 将[`Transform`](./transform)属性重置为标识。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform#rotatetransform)(float) | 将局部几何变换旋转指定的量。此方法将旋转添加到变换中。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform#rotatetransform_1)(float, MatrixOrder) | 按指定顺序将局部几何变换旋转指定量。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform#scaletransform)(float, float) | 按指定量缩放局部几何变换。此方法将缩放矩阵添加到变换中。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序按指定量缩放局部几何变换。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform#translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序按指定维度平移局部几何变换。 |

### 也可以看看

* class [Brush](../../aspose.psd/brush)
* 命名空间 [Aspose.PSD.Brushes](../../aspose.psd.brushes)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->

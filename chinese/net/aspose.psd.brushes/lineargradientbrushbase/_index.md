---
title: "类 LinearGradientBrushBase"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Brushes.LinearGradientBrushBase 类。表示具有渐变功能和相应属性的 Brush"
type: docs
weight: 150
url: /zh/net/aspose.psd.brushes/lineargradientbrushbase/
---
{{< psd/tize >}}
## LinearGradientBrushBase class

表示具有渐变功能和相应属性的 [`Brush`](../../aspose.psd/brush/)

```csharp
public abstract class LinearGradientBrushBase : TransformBrush
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Angle](../../aspose.psd.brushes/lineargradientbrushbase/angle/) { get; set; } | 获取或设置渐变角度。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [GammaCorrection](../../aspose.psd.brushes/lineargradientbrushbase/gammacorrection/) { get; set; } | 获取或设置一个值，指示是否为此 `LinearGradientBrushBase` 启用了伽马校正。 |
| [IsAngleScalable](../../aspose.psd.brushes/lineargradientbrushbase/isanglescalable/) { get; set; } | 获取或设置一个值，指示在使用此 `LinearGradientBrushBase` 进行变换时是否更改了 [`Angle`](./angle/)。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示转换是否以某种方式被更改。例如设置转换矩阵或调用任何修改转换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画刷的不透明度。值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。 |
| [Rectangle](../../aspose.psd.brushes/lineargradientbrushbase/rectangle/) { get; set; } | 获取或设置定义渐变起始点和结束点的矩形区域。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | 获取或设置一个复制的 [`Matrix`](../../aspose.psd/matrix/)，该矩阵定义此 [`TransformBrush`](../transformbrush/) 的局部几何变换。 |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | 获取或设置一个 [`WrapMode`](../../aspose.psd/wrapmode/) 枚举，用于指示此 [`TransformBrush`](../transformbrush/) 的换行模式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.psd/brush/) 的新深度克隆。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 的本地几何变换的 [`Matrix`](../../aspose.psd/matrix/) 与指定的 [`Matrix`](../../aspose.psd/matrix/) 相乘，方法是将指定的 [`Matrix`](../../aspose.psd/matrix/) 前置。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/)(Matrix, MatrixOrder) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 的本地几何变换的 [`Matrix`](../../aspose.psd/matrix/) 与指定的 [`Matrix`](../../aspose.psd/matrix/) 相乘，按照指定的顺序。 |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | 将 [`Transform`](../transformbrush/transform/) 属性重置为单位矩阵。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float) | 按指定的角度旋转本地几何变换。此方法将旋转前置到变换中。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/)(float, MatrixOrder) | 按指定的角度并按照指定的顺序旋转本地几何变换。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float) | 按指定的比例缩放本地几何变换。此方法将缩放矩阵前置到变换中。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/)(float, float, MatrixOrder) | 按指定的比例并按照指定的顺序缩放本地几何变换。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 按指定的尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 按指定的尺寸并按照指定的顺序平移本地几何变换。 |

### 另请参阅

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



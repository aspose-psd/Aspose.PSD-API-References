---
title: "类 PathGradientBrushBase"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Brushes.PathGradientBrushBase 类。表示具有基础路径渐变功能的 Brush。"
type: docs
weight: 180
url: /zh/net/aspose.psd.brushes/pathgradientbrushbase/
---
{{< psd/tize >}}
## PathGradientBrushBase class

表示具有基础路径渐变功能的 [`Brush`](../../aspose.psd/brush/)。

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 获取此 Brush 所基于的图形路径。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示转换是否以某种方式被更改。例如设置转换矩阵或调用任何修改转换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画刷的不透明度。值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。 |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | 获取此 Brush 所基于的路径点。 |
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

## 备注

请注意，在创建 `PathGradientBrushBase` 类时，至少应使用 2 个点进行初始化。创建的内部路径始终是封闭图形，最后一个点连接到第一个点。该形状使用此 `PathGradientBrushBase` 填充。GDI+ 实现会在传入空数组或点集合具有相同坐标时抛出 OutOfMemoryException。`PathGradientBrushBase` 在点数组少于 2 个点时会抛出异常，且在点数组不可接受时抛出 ArgumentException 而不是 OutOfMemoryException。默认情况下，中心点根据传入的点计算为质心。用户可以稍后更改此点。默认情况下，焦点比例是空点 (0.0, 0.0)。

### 另请参阅

* class [TransformBrush](../transformbrush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



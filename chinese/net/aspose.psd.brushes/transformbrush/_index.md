---
title: "类 TransformBrush"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Brushes.TransformBrush 类。具有变换功能的 Brush"
type: docs
weight: 220
url: /zh/net/aspose.psd.brushes/transformbrush/
---
{{< psd/tize >}}
## TransformBrush class

具有变换功能的 [`Brush`](../../aspose.psd/brush/)。

```csharp
public abstract class TransformBrush : Brush
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示转换是否以某种方式被更改。例如设置转换矩阵或调用任何修改转换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画刷的不透明度。值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。 |
| [Transform](../../aspose.psd.brushes/transformbrush/transform/) { get; set; } | 获取或设置一个定义此 `TransformBrush` 本地几何变换的复制 [`Matrix`](../../aspose.psd/matrix/)。 |
| [WrapMode](../../aspose.psd.brushes/transformbrush/wrapmode/) { get; set; } | 获取或设置一个指示此 `TransformBrush` 包装模式的 [`WrapMode`](../../aspose.psd/wrapmode/) 枚举。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.psd/brush/) 的新深度克隆。 |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 释放当前实例。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform)(Matrix) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 的本地几何变换的 [`Matrix`](../../aspose.psd/matrix/) 与指定的 [`Matrix`](../../aspose.psd/matrix/) 相乘，方法是将指定的 [`Matrix`](../../aspose.psd/matrix/) 前置。 |
| [MultiplyTransform](../../aspose.psd.brushes/transformbrush/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 将表示此 [`LinearGradientBrush`](../lineargradientbrush/) 的本地几何变换的 [`Matrix`](../../aspose.psd/matrix/) 与指定的 [`Matrix`](../../aspose.psd/matrix/) 相乘，按照指定的顺序。 |
| [ResetTransform](../../aspose.psd.brushes/transformbrush/resettransform/)() | 将 [`Transform`](./transform/) 属性重置为单位矩阵。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform)(float) | 按指定的角度旋转本地几何变换。此方法将旋转前置到变换中。 |
| [RotateTransform](../../aspose.psd.brushes/transformbrush/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 按指定的角度并按照指定的顺序旋转本地几何变换。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform)(float, float) | 按指定的比例缩放本地几何变换。此方法将缩放矩阵前置到变换中。 |
| [ScaleTransform](../../aspose.psd.brushes/transformbrush/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 按指定的比例并按照指定的顺序缩放本地几何变换。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform)(float, float) | 按指定的尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 按指定的尺寸并按照指定的顺序平移本地几何变换。 |

### 另请参阅

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)



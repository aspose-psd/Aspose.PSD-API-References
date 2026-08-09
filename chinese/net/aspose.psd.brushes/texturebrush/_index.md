---
title: "类 TextureBrush"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Brushes.TextureBrush 类。TextureBrush 类的每个属性都是使用图像填充形状内部的 Brush 对象。此类不能被继承"
type: docs
weight: 210
url: /zh/net/aspose.psd.brushes/texturebrush/
---
{{< psd/tize >}}
## TextureBrush class

每个 `TextureBrush` 类的属性都是一个使用图像填充形状内部的 [`Brush`](../../aspose.psd/brush/) 对象。此类不能被继承。

```csharp
public sealed class TextureBrush : TransformBrush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextureBrush](texturebrush/#constructor)(Image) | 初始化 `TextureBrush` 类的一个使用指定图像的新实例。 |
| [TextureBrush](texturebrush/#constructor_1)(Image, Rectangle) | 初始化 `TextureBrush` 类的一个使用指定图像和边界矩形的新实例。 |
| [TextureBrush](texturebrush/#constructor_3)(Image, RectangleF) | 初始化 `TextureBrush` 类的一个使用指定图像和边界矩形的新实例。 |
| [TextureBrush](texturebrush/#constructor_5)(Image, WrapMode) | 初始化 `TextureBrush` 类的一个使用指定图像和包装模式的新实例。 |
| [TextureBrush](texturebrush/#constructor_2)(Image, Rectangle, ImageAttributes) | 初始化 `TextureBrush` 类的一个使用指定图像、边界矩形和图像属性的新实例。 |
| [TextureBrush](texturebrush/#constructor_4)(Image, RectangleF, ImageAttributes) | 初始化 `TextureBrush` 类的一个使用指定图像、边界矩形和图像属性的新实例。 |
| [TextureBrush](texturebrush/#constructor_6)(Image, WrapMode, Rectangle) | 初始化 `TextureBrush` 类的一个使用指定图像、包装模式和边界矩形的新实例。 |
| [TextureBrush](texturebrush/#constructor_7)(Image, WrapMode, RectangleF) | 初始化 `TextureBrush` 类的一个使用指定图像、包装模式和边界矩形的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Image](../../aspose.psd.brushes/texturebrush/image/) { get; } | 获取与此 `TextureBrush` 对象关联的 [`Image`](../../aspose.psd/image/) 对象。 |
| [ImageAttributes](../../aspose.psd.brushes/texturebrush/imageattributes/) { get; } | 获取与此 `TextureBrush` 关联的 [`ImageAttributes`](./imageattributes/)。 |
| [ImageRectangle](../../aspose.psd.brushes/texturebrush/imagerectangle/) { get; } | 获取与此 `TextureBrush` 关联的 [`Rectangle`](../../aspose.psd/rectangle/)。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示转换是否以某种方式被更改。例如设置转换矩阵或调用任何修改转换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画刷的不透明度。值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。 |
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



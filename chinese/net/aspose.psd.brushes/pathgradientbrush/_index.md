---
title: "类 PathGradientBrush"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Brushes.PathGradientBrush 类。封装具有渐变的 Brush 对象。此类不可被继承"
type: docs
weight: 170
url: /zh/net/aspose.psd.brushes/pathgradientbrush/
---
{{< psd/tize >}}
## PathGradientBrush class

封装具有渐变的 [`Brush`](../../aspose.psd/brush/) 对象。此类不可被继承。

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PathGradientBrush](pathgradientbrush/#constructor)(GraphicsPath) | 使用指定的路径初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_1)(PointF[]) | 使用指定的点初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_3)(Point[]) | 使用指定的点初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_2)(PointF[], WrapMode) | 使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。 |
| [PathGradientBrush](pathgradientbrush/#constructor_4)(Point[], WrapMode) | 使用指定的点和包装模式初始化 `PathGradientBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Blend](../../aspose.psd.brushes/pathgradientbrush/blend/) { get; set; } | 获取或设置一个 [`Blend`](../../aspose.psd/blend/)，它指定用于定义渐变自定义衰减的位置信息和因子。 |
| [CenterColor](../../aspose.psd.brushes/pathgradientbrush/centercolor/) { get; set; } | 获取或设置路径渐变中心的颜色。 |
| [CenterPoint](../../aspose.psd.brushes/pathgradientbrushbase/centerpoint/) { get; set; } | 获取或设置路径渐变的中心点。 |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [FocusScales](../../aspose.psd.brushes/pathgradientbrushbase/focusscales/) { get; set; } | 获取或设置渐变衰减的焦点。 |
| [GraphicsPath](../../aspose.psd.brushes/pathgradientbrushbase/graphicspath/) { get; } | 获取此 Brush 所基于的图形路径。 |
| [InterpolationColors](../../aspose.psd.brushes/pathgradientbrush/interpolationcolors/) { get; set; } | 获取或设置一个定义多色线性渐变的 [`ColorBlend`](../../aspose.psd/colorblend/)。 |
| [IsTransformChanged](../../aspose.psd.brushes/transformbrush/istransformchanged/) { get; } | 获取一个值，指示转换是否以某种方式被更改。例如设置转换矩阵或调用任何修改转换矩阵的方法。此属性为向后兼容 GDI+ 而引入。 |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | 获取或设置画刷的不透明度。值应在 0 到 1 之间。0 表示画刷完全可见，1 表示画刷完全不透明。 |
| [PathPoints](../../aspose.psd.brushes/pathgradientbrushbase/pathpoints/) { get; } | 获取此 Brush 所基于的路径点。 |
| [SurroundColors](../../aspose.psd.brushes/pathgradientbrush/surroundcolors/) { get; set; } | 获取或设置一个颜色数组，该数组对应于此 `PathGradientBrush` 填充的路径中的点。 |
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
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape)(float) | 创建一个以中心颜色为起点、线性衰减到单个周围颜色的渐变。 |
| [SetBlendTriangularShape](../../aspose.psd.brushes/pathgradientbrush/setblendtriangularshape/#setblendtriangularshape_1)(float, float) | 创建一个以中心颜色为起点、线性衰减到每个周围颜色的渐变。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape)(float) | 创建一个渐变画刷，从路径中心向外到路径边界改变颜色。颜色之间的过渡基于钟形曲线。 |
| [SetSigmaBellShape](../../aspose.psd.brushes/pathgradientbrush/setsigmabellshape/#setsigmabellshape_1)(float, float) | 创建一个渐变画刷，从路径中心向外到路径边界改变颜色。颜色之间的过渡基于钟形曲线。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float) | 按指定的尺寸平移本地几何变换。此方法将平移前置到变换中。 |
| [TranslateTransform](../../aspose.psd.brushes/transformbrush/translatetransform/)(float, float, MatrixOrder) | 按指定的尺寸并按照指定的顺序平移本地几何变换。 |

## 备注

默认情况下，中心颜色为白色。用户可以在以后随时更改此值。

默认情况下，环绕颜色数组以包含白色的单个元素进行初始化。环绕颜色以后可以更改，但在设置环绕颜色时至少需要一个元素。

有关其初始化的更多细节，请参阅 [`Blend`](./blend/)。

### 另请参阅

* class [PathGradientBrushBase](../pathgradientbrushbase/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


